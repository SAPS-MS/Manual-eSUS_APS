---
layout: default
title: Certificado HTTPS Linux
parent: Apoio a Implantação
nav_order: 5
has_children: false
has_toc: true
last_modified_date: "25/09/2023"
---

# Como incluir um certificado SSL (HTTPS) no e-SUS APS [LINUX]?
{: .no_toc }

Arquivo .PDF do Tutorial: <br><br>
<a href="https://saps-ms.github.io/Manual-eSUS_APS/Configuração_Linux.pdf" target="_blank">Configuração https no Linux</a>

Vídeo de apresentação: <br>

<video width="800" height="520" controls="controls" poster="capa_linux.png">
  <source src="https://saps-ms.github.io/Manual-eSUS_APS/linux.mp4" type="video/mp4">
</video>

Um certificado SSL é um certificado digital que autentica a identidade de um site e permite uma conexão criptografada. SSL significa Secure Sockets Layer, um protocolo de segurança que cria um link criptografado entre um servidor web e um navegador web.

Neste artigo, apresentaremos o passo-a-passo para inclusão de um certificado SSL no e-SUS APS (no Linux) e garantir ainda mais segurança no acesso à sua instalação. É válido ressaltar que o Let's Encrypt não emite certificados para endereços IP simples, apenas nomes de domínio. Para estes casos, você precisará registrar um nome de domínio para obter um certificado Let's Encrypt ou encontrar alguma outra certificadora que emita para endereços de IP simples.

É válido ressaltar que os passos abaixo de geração de certificado através do Let's Encrypt são apenas sugestões, neste caso, você poderá utilizar a certificadora que desejar para geração.

## Gerando um certificado SSL

Caso ainda não possua um certificado SSL, mostraremos como obtê-lo usando o Certbot do Let's Encrypt, uma Autoridade Certificadora gratuita, automatizada e aberta, que fornece certificados digitais necessários para habilitar HTTPS em websites. O processo abaixo é destinado para instalações LINUX, porém, você poderá gerar por qualquer outra certificadora para utilização em Windows.

Caso já possua um certificado SSL, basta pular esta seção e ir para "Instalando o certificado SSL".

Como o PEC vem configurado para o protocolo HTTP na porta 8080 por padrão e o Certbot precisa que o servidor esteja rodando na porta 80 para funcionar, será necessário alterar essa configuração do e-SUS APS. 
 
Em PASTA_DE_INSTALACAO_eSUS/webserver/config, modifique o arquivo application.properties para adicionar a seguinte linha: 

    server.port=80

Após a inclusão, é necessário que o serviço do e-SUS APS seja reiniciado:

    systemctl stop e-SUS-PEC.servicesystemctl start e-SUS-PEC.service

 É preciso ter o snapd instalado, caso ainda não o possua. Ele vem pré-instalado no Ubuntu 18, 20 e 21, e no Manjaro, dentre outros. Porém, se você utiliza ArchLinux, Debian ou Fedora, por exemplo, será necessário instalá-lo. A lista completa de distribuições que vêm ou não com snapd pré-instalado pode ser encontrada aqui. Neste link você também encontra as instruções para instalação em cada caso.

 Com o snapd instalado, execute o comando abaixo:

 sudo snap install core; sudo snap refresh core

 Se você tiver algum pacote do Certbot instalado através de um gerenciador de pacotes do sistema (como apt, dnf ou yum), você deve removê-lo antes de prosseguir. O comando exato para fazer isso depende da sua distribuição Linux, mas exemplos comuns são:

    •	sudo apt-get remove certbot
    •	sudo dnf remove certbot
    •	sudo yum remove certbot

Se você já usou o Certbot no passado por meio do script certbot-auto, você também deve remover sua instalação seguindo as instruções desta página.

 Finalmente, instale o Certbot executando o comando abaixo:

    sudo snap install --classic certbot

 E então rode o comando a seguir para garantir que o Certbot poderá ser executado:

    sudo ln -s /snap/bin/certbot /usr/bin/certbot

Por fim, execute-o por meio do comando e preencha as informações solicitadas:

    sudo certbot certonly --webroot

Obs: Através deste comando, solicitará o domínio que você gostaria de inserir o protocolo, neste caso, é válido ressaltar que o Let's Encrypt não emite certificados para endereços IP simples, apenas nomes de domínio. Para estes casos, você precisará registrar um nome de domínio para obter um certificado Let's Encrypt ou encontrar alguma outra certificadora que emita para endereços de IP simples.

## Instalando o certificado SSL

Uma vez que você já possui um certificado SSL, vamos armazená-lo em uma keystore. Primeiramente, navegue até a pasta de configuração do e-SUS APS:
cd PASTA_DE_INSTALACAO_eSUS/webserver/config


E então use o comando abaixo para importar o certificado e criar a keystore, substituindo:

- "CAMINHO_COMPLETO" pelo caminho completo até a pasta onde se encontra o certificado (/etc/letsencrypt se você criou o certificado seguindo este tutorial);

- "CERTIFICADO" pelo nome do arquivo; e

- "SENHA" pela senha que deseja utilizar para proteger a keystore.

        keytool -import -alias esusaps -file CAMINHO_COMPLETO/CERTIFICADO.crt -keystore esus

Parametrizando no PEC

Agora, é necessário fazer com que o e-SUS APS utilize o certificado salvo na keystore. Em PASTA_DE_INSTALACAO_eSUS/webserver/config, modifique o arquivo application.properties, copiando as seguintes propriedades para o final do arquivo:

    server.port=443   
    server.ssl.key-store-type=PKCS12  #OPCIONAL! Depende do tipo de certificado a ser utilizado.
    server.ssl.key-store=
    server.ssl.key-store-password=
    server.ssl.key-alias=
    security.require-ssl=true   #Sempre deve ser passado verdadeiro para habilitar o uso de SSL.

O significado de cada propriedade pode ser observado a seguir:

- server.port: A porta que representa o protocolo HTTPS; utiliza-se como padrão a porta 443. Também é possível utilizar a porta 8443 (para sinalizar desenvolvimento ou homologação).

- server.ssl.key-store-type: Indica o tipo de Key Store. Caso o tipo seja .p12 (como neste tutorial), é necessário manter esta propriedade e após o = indicar que é PKCS12. Mas, se o tipo for JKS, essa propriedade pode ser omitida.

- server.ssl.key-store: Este é o caminho relativo ao .jar da aplicação (pec-bundle.jar) de onde se encontra a Key Store. Por exemplo, se a Key Store estiver dentro da pasta config como sugerido nos últimos passos, utilizar: server.ssl.key-store=config/esusaps.p12

- server.ssl.key-store-password: Senha indicada no momento da criação da Key Store.

- server.ssl.key-alias: "Apelido" indicado no momento da criação da Key Store.

- security.require-ssl: Propriedade que indica ao Spring se desejamos fazer uso do protocolo SSL.

Após incluir essas propriedades no arquivo e salvá-lo, é necessário reiniciar o serviço do servidor:

    systemctl stop e-SUS-PEC.servicesystemctl start e-SUS-PEC.service

Pronto, o certificado SSL já deve ter sido incluído na sua instalação do e-SUS APS! Para confirmar que o processo funcionou, acesse a URL da instalação em seu navegador e procure pelo ícone de cadeado na barra de endereço.

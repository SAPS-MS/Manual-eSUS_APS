---
layout: default
title: Versão 5.3 (Em Piloto)
parent: Últimas releases
nav_order: 1
has_children: false
has_toc: true
last_modified_date: "17/05/2024"
---

<head>
    <style>
        p{text-align:justify};
    </style>
</head>

# Versão 5.3
## Novidades - Ferramentas Administrativas

- Unificação de bases;
- Parametrização HTTPS automatizada;
- API para recebimento de lotes dos Sistemas Próprios/Terceiros; 
- Histórico de acessos;
- Atualização de terminologias dos envios à RNDS;
- Importar beneficiários do Bolsa Família.

## Novidades - Ferramentas relacionadas aos atendimentos

* Busca ativa de vacinação;
* Acompanhamento do Território - Cadastro de Imóveis e Famílias;
* Acompanhamento das condições de saúde;
* Videochamada do profissional convidado adaptada para telefone celular;
* Videochamada do profissional convidado adaptada para tablet;
* Agendamento entre profissionais;
* Inclusão do nome social do profissional;
* Acesso rápido na agenda;
* Doses fracionadas na prescrição de medicamentos;
* Atestado Digital;
* Garantia do Acesso no Cuidado Compartilhado;
* Participação do cidadão e atendimento compartilhado;


**Unificação de bases**

Esta ferramenta consolida as bases descentralizadas do PEC em uma estrutura única e centralizada. Esse avanço permite que todos os estabelecimentos de saúde integrem e implementem o conceito de Prontuário Eletrônico do Cidadão (PEC e-SUS APS) de forma unificada no âmbito municipal. 

Para especificações desta funcionalidade, consultar o capítulo "Administração e Configurações do Sistema", Unificação de bases.


**Parametrização HTTPS automatizada**

A geração e renovação do Certificado TLS (SSL) / HTTPS no PEC se tornou bem mais fácil, sendo agora gerenciado pela própria aplicação de maneira totalmente automatizada.  

Essa habilitação permite o uso de diversas funcionalidades que fortalecem o trabalho das equipes e o cuidado aos cidadãos, como teleinterconsultas, prescrição digital, acesso ao CadSUS. 

**Histórico de acessos ao sistema** 

Possibilita ver o histórico de acessos ao sistema 

**Atualização de terminologias dos envios à RNDS**

Na aba RNDS:  

Registro de Imunobiológicos Administrado em Campanha (RIA-C) ou Rotina (RIA-R) 

Registro de Atendimento Clínico (RAC) 

Registro de Prescrição de Medicamentos (RPM)

**Importar beneficiários do Bolsa Família**

Agora será possível importar um arquivo com os beneficiários do bolsa família de uma vigência específica para que eles sejam identificados em seus prontuários. 

O arquivo poderá ser baixado no e-Gestor e incluído para importação na funcionalidade de Importação do bolsa família, que pode ser acessada pelo menu lateral com o perfil de Instalador.  

É possível importar arquivos de qualquer vigência, inclusive listas complementares. 

![](./media/importacao_beneficiarios_bolsa_familia.gif)

Ao visualizar a folha de rosto de um cidadão que consta como beneficiário no arquivo importado da vigência mais atual, será apresentada uma sinalização de que ele é beneficiário do Programa Bolsa Família. 

![](./media/importacao_beneficiarios_bolsa_familia_1.png)

**Busca ativa de vacinação**

* Implementação do Grupo-alvo de Adultos para Vacinas do calendário vacinal;
* Implementação do Grupo-alvo de Puérperas com Gestantes para Vacinas do calendário vacinal;
* Unificação dos Grupos-alvo de Gestantes e Puérperas para Vacinas do calendário vacinal;
* Inclusão do filtro por Bairro, Tipo de Logradouro e Logradouro de residência do cidadão;
* Inclusão da regra de Identidade de gênero nos relatórios.

**Inclusão dos grupos alvos:**

![](./media/grupo_vacinal.png)

Inclusão do **bairro** nos filtros avançados:

![](./media/bairro.png)

**Acompanhamento do Território - Cadastro de Imóveis e Famílias**

* A versão 5.3 agora permite cadastrar imóveis e famílias de forma mais completa e clara, facilitando a gestão dos cidadãos moradores de cada domicílio adscrito.

* A funcionalidade de Acompanhamento do Território, no menu lateral, foi evoluída para permitir cadastrar e atualizar os imóveis e famílias, condições de moradia e responsabilidades de acompanhamento, tudo isso em uma única interface moderna e intuitiva, sem a necessidade de gerar várias Fichas CDS manualmente. O sistema as gerará automaticamente, apenas para que a sua produção seja consolidada em relatórios e enviada ao Centralizar Nacional.

* Também será possível visualizar e corrigir inconsistências de cadastro através das novas telas, sem a necessidade de se aguardar o processamento após o Envio de Lotes de Fichas.

![](./media/cadastro_imovel.png)


**Acompanhamento das condições de saúde**

* Inclusão da exportação do relatório de busca em formato CSV, permitindo a manipulação dos dados.

* Inclusão da visualização, de até 7 dias, dos relatórios que foram processados e que estão em processamento.

![](./media/55.gif)

**Videochamada do profissional convidado adaptada para telefone celular**

* Os componentes da videochamada foram adaptados para funcionar em telefones celular. O objetivo do módulo é possibilitar que o profissional convidado acesse a videochamada pelo telefone celular. 

* Por outro lado, o profissional anfitrião ainda deve acessar a videochamada através do computador.

* As funcionalidades da videochamada para telefone celular são:

    * Ativar e desativar camera;
    * Ativar e desativar microfone;
    * Chat.

![](./media/video_chamadaa.png)

**Videochamada do profissional convidado adaptada para tablet**

* Os componentes da videochamada foram adaptados para funcionar corretamente em tablets. O objetivo do módulo é adaptar as telas da videochamada para tablet. Todas as funcionalidades da videochamada foram mantidas.

![](./media/54.png)


**Agendamento entre profissionais**

Esta nova funcionalidade permite o agendamento entre profissionais, inclusive por videochamada.

![](./media/agendamentoprofissionais.png)

Ao entrar em agenda, selecionar o profissional e o horário desejado, poderá escolher entre consulta, reserva ou agendamento entre profissionais. 

Ao selecionar agendamento entre profissionais, deverá incluir o nome do profissional convidado, em seguida o nome do cidadão que será atendido e salvar.

![](./media/agendamentoentreprofissionais5.png)

Na agenda do profissional, ficará registrado o nome do cidadão agendado e o profissional convidado, conforme imagem:

![](./media/agendamentoentreprofissionais6.png)


**Inclusão do nome social do profissional**

Agora, o PEC e-SUS APS amplia o uso do nome social não apenas para os cidadãos, mas também para os profissionais de saúde.  

Conforme o Decreto nº8.727, de 28/04/2016, nome social se refere à designação pela qual a pessoa travesti ou transexual se identifica e é socialmente reconhecida. 

![](media/nome_social_profissional.png)

Essa implementação garante que o nome social do profissional seja exibido em todos os campos do sistema, incluindo impressões e prescrições eletrônicas. 

Receita realizada com nome social
![](media/receituarionomesocial.png)

**Acesso rápido na agenda**

Novo campo de pesquisa que possibilita acesso rápido na agenda profissional, como também fixação na lista em todos os campos do PEC e-SUS APS que se relacionam com a agenda. 

Ao entrar no módulo "Agenda" será possível fixar um profissional para consulta rápida conforme imagem.

![](media/agendafixar.png)

Nas próximas consultas, a agenda abrirá automaticamente no profissional fixado.

**Doses fracionadas na prescrição de medicamento**

Novo campo na prescrição de medicamentos que possibilita tipo de dose fracionada por turno. 
O passo a passo está no capítulo PEC - Atendimento - Prescrição. 

![](media/56.png)

**Atestado Digital**

Implementado campo para o envio do atestado digital para o cidadão. 

Ao selecionar "Gerar e enviar atestado digital", o profissional deverá incluir o e mail para envio do documento.

![](media/atestadodigital1.png)

Em seguida, abrirá uma tela de aviso para conferência dos dados do atestado.

![](media/atestadodigital2.png)

Na sequência, abrirá a tela de assinatura, sendo necessário que o profissional tenha assinatura cadastrada em um provedor.

![](media/atestadodigital3.png)

O registro do atestado digital ficará disponível no prontuário do cidadão.

![](media/atestadodigital4.png)

**Garantia do Acesso no Cuidado Compartilhado**

**Participação do cidadão e atendimento compartilhado**


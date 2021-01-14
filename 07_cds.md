---
layout: default
title: Coleta de Dados Simplificada (CDS)
nav_order: 9
has_children: false
has_toc: false
---



CAPÍTULO 7 - Coleta de Dados Simplificada (CDS)
===============================================

A Coleta de Dados Simplificada (CDS) é um dos componentes da Estratégia e-SUS APS, sendo utilizada principalmente nos serviços de saúde que não dispõem de sistema informatizado para utilização rotineira no trabalho. Este capítulo apresenta informações para a utilização do Módulo CDS, agregado ao Sistema com PEC, considerando o processo de digitação das fichas previamente preenchidas. Todas as orientações que constam neste manual se aplicam ao Sistema com CDS (*standalone*). Para mais informações sobre o Sistema com CDS, em especial sobre a forma de preenchimento das fichas, consulte o Manual do Sistema com Coleta de Dados Simplificada, disponível por meio do endereço eletrônico [http://dab.saude.gov.br/portaldab/esus.php](http://dab.saude.gov.br/portaldab/esus.php).

> ![](media/image58.png) **NOTA**: Para conhecer os conceitos e orientações de preenchimento das fichas, consulte o Manual do Sistema com Coleta de Dados Simplificada (CDS).

# 7.1 Visão Geral do Sistema/Módulo CDS


O Sistema com CDS ou o Módulo CDS (do Sistema com PEC) é um **sistema de apoio à digitação** das fichas que compõem esse sistema. A Figura 7.1 apresenta a tela principal do CDS, na qual também são visualizadas as doze fichas para o registro de informações, que compõem o sistema e-SUS AB. São elas:

- Cadastro individual;
- Cadastro domiciliar e territorial;
- Ficha de atendimento individual;
- Ficha de atendimento odontológico;
- Ficha de atividade coletiva;
- Ficha de procedimentos;
- Ficha de visita domiciliar e territorial;
- Marcadores de consumo alimentar;
- Ficha de avaliação de elegibilidade;
- Ficha de atendimento domiciliar;
- Ficha complementar - Síndrome neurológica por Zika/Microcefalia;
- Ficha de Vacinação.

Figura 7.1 - Tela do menu do CDS
![](media/image623.png)
Fonte: SAS/MS.

## 7.1.1 Orientações Gerais sobre o Processo de Digitação das Fichas

O processo de digitação deve ser definido no âmbito da gestão municipal, considerando os aspectos logísticos e os recursos humanos disponíveis para esse fim. Em especial, considerando os diferentes cenários de implantação, como visto no Manual de Implantação da Estratégia e-SUS APS, o fluxo deve estar adequado a cada realidade.

Veja a Nota Técnica: [**Alimentação dos sistemas de informação pelos profissionais das equipes de Atenção Básica**](http://189.28.128.100/dab/docs/portaldab/documentos/NT_ACS.pdf) ([[http:// 189.28.128.100/dab/docs/portaldab/documentos/ NT_ACS.pdf]](http://189.28.128.100/dab/docs/portaldab/documentos/NT_ACS.pdf)). De modo a facilitar o processo de digitação, foi elaborado modelo padrão de cabeçalho para todas as fichas usadas no Sistema com CDS, como ilustrado na Figura 7.2. Estes campos não são registrados no sistema, tampouco existe relatório desse processo, e são de uso exclusivo dos responsáveis pela digitação para **controle interno da digitação**.

Figura 7.2 - Cabeçalho- padrão das fichas CDS
![](media/image624.png)
Fonte: SAS/MS.

Cada campo é definido da seguinte maneira:

- **DIGITADO POR:** nome do profissional que digitou a ficha;

- **DATA:** dia em que a digitação foi realizada;

- **CONFERIDO POR:** nome do profissional que fez a supervisão do processo de digitação da ficha;

- **FOLHA Nº:** este campo pode ser utilizado na organização do processo de trabalho do profissional que preencher as informações da ficha em determinado contexto, identificando, quando for o caso, o número da folha usada para esse fim.

## 7.1.2 Orientações Gerais sobre Digitação das Fichas no Sistema

Conforme vimos na Figura 7.1, o Sistema com CDS organiza as ferramentas para digitação por fichas. De modo geral, quando acessamos alguma das fichas é possível observar a lista com os registros que já foram digitados no sistema (estará vazia quando não houver nenhuma ficha digitada, ou se já tiverem sido enviadas), como podemos ver na Figura 7.3, para o caso das Fichas de Atendimento Individual.

Figura 7.3 - Ficha de Atendimento Individual - listagem
![](media/image625.png)
Fonte: SAS/MS.

Portanto, para digitar uma ficha, selecione a ferramenta correspondente, na tela principal, conforme a ficha que deseja digitar. Após abrir a tela de listagem da ficha correspondente, clique no botão ![](media/image626.png). Logo depois, já é possível iniciar a digitação da ficha. Nas seções a seguir, cada ficha será abordada com mais detalhes.

Neste momento, vale destacar ainda o novo componente de filtro ![](media/image627.png), disponível na listagem das fichas, conforme podemos ver na Figura 7.4. Ele permite a realização de pesquisa utilizando algumas informações dos cabeçalhos das fichas, como o CNS do profissional, data de nascimento, CBO, CNES da unidade onde a ficha foi preenchida, INE, entre outras. Os campos de pesquisa variam de acordo com cada ficha.

Figura 7.4 - Componente de filtro da listagem das fichas
![](media/image628.png)
Fonte: SAS/MS.

Para filtrar a lista, digite a informação desejada no campo correspondente e clique no botão Pesquisar ![](media/image629.png). Para retirar o filtro, deixe todos os campos vazios e clique novamente em Pesquisar.

Outra funcionalidade importante na listagem de fichas é o controle de envio das fichas. As fichas não enviadas recebem uma marcação especial, como podemos ver na Figura 7.5. Quando uma ficha é enviada a marcação some, indicando que a ficha já foi enviada/transmitida para o SISAB.

Figura 7.5 - Fichas não enviadas
![](media/image630.png)
Fonte: SAS/MS.

Na listagem das fichas, ainda existem várias ações possíveis para cada registro e, por padrão, as seguintes opções estão disponíveis:

- ![](media/image631.png) **Visualizar:** permite visualizar as informações de uma ficha digitada;

- ![](media/image632.png) **Editar:** permite fazer alterações em uma ficha digitada. Disponível apenas para fichas não enviadas.

- ![](media/image632.png) **Excluir:** permite excluir uma ficha digitada. Disponível apenas para fichas não enviadas.

> ![](media/image59.png) **ATENÇÃO**: caso a ficha digitada já tenha sido transmitida para o SISAB, não será possível editá- la ou excluí- la (botão esmaecido), apenas será possível visualizar a ficha ![](media/image633.png).

## 7.1.3 Inconsistência ao Finalizar a Digitação

Ao finalizar a digitação de uma ficha, clique no botão ![](media/image634.png). Caso o sistema não detecte alguma inconsistência, o sistema salvará os dados e voltará para a tela com a lista de registros/colunas da ficha.

Caso haja alguma inconsistência, o sistema mostrará mensagem na tela indicando os campos que deverão ser corrigidos, como ilustrado na Figura 7.6.

Figura 7.6 - Verificação de inconsistência ao finalizar a digitação
![](media/image635.png)
Fonte: SAS/MS.

Verifique as mensagens, corrigindo a informação conforme estiver preenchido na ficha. Caso ela esteja preenchida de forma **inconsistente**, em relação à validação do sistema, **cancele a digitação** da ficha e informe o supervisor, a equipe de saúde ou o profissional responsável pelo preenchimento dela.

> ![](media/image59.png) **ATENÇÃO**: caso alguma **inconsistência** seja **detectada** pela validação do sistema, o supervisor ou o próprio profissional deve ser avisado para que esta ficha possa ser **verificada na origem da informação**.

# 7.2 Cadastro da Atenção Básica

O Cadastro da Atenção Básica (AB) é uma extensão do CadSUS no que se refere aos dados que apoiam as equipes de AB a mapear as características sociais, econômicas e de saúde da população adscrita ao território sob sua responsabilidade. Esse cadastro está organizado em duas dimensões: a) Cadastro individual e b) Cadastro domiciliar e territorial.

## 7.2.1 Cadastro Individual

![](media/image636.png)

Na tela principal, clique no ícone "Cadastro individual". A janela com a lista de fichas digitadas de cadastro individual será mostrada, conforme a Figura 7.7. É possível visualizar esta lista e as opções relacionadas a cada registro, além das opções de filtro da lista.

Figura 7.7 - Tela principal do cadastro individual
![](media/image637.png)
Fonte:SAS/MS.

### 7.2.1.1 Adicionar Cadastro Individual

Após clicar no botão \"Adicionar\", o sistema mostrará a tela de preenchimento da ficha de cadastro, conforme as Figuras 7.8, 7.9 (continuação) e 7.10 (continuação).

Figura 7.8 - Adicionar cadastro individual
![](media/image638.png)
Fonte:SAS/MS.

Figura 7.9 - Adicionar cadastro individual - continuação
![](media/image639.png)
Fonte:SAS/MS.

Figura 7.10 - Adicionar cadastro individual - continuação
![](media/image640.png)
Fonte:SAS/MS.

Para digitar a ficha de cadastro, atente para o que se segue:

#### 7.2.1.1.1 Informações de cabeçalho

1.Preencha os campos do cabeçalho, digitando os dados que constam na ficha de cadastro;

![](media/image641.png)

a.Ao incluir o número do Cartão SUS do profissional, o sistema mostrará opções para o CNES e o INE que vêm da base de dados do CNES importado na instalação da aplicação;

b.Caso o profissional tenha apenas um vínculo no município, os dados serão preenchidos automaticamente;

c.Caso o trabalhador tenha mais de um vínculo, o sistema mostrará as opções e o digitador indicará o que está registrado na ficha. Também são apresentados para o preenchimento, dependendo da ficha que irá digitar, os campos "microárea" e a data em que o cadastro foi realizado;

#### 7.2.1.1.2 Dados de identificação

2.Preencha os "Dados de identificação" do cidadão de acordo com a ficha CDS. Se a resposta da questão "Cidadão é o responsável familiar?" for "Não", o campo "CNS ou CPF do responsável familiar" deve ser preenchido obrigatoriamente;

![](media/image642.png)

#### 7.2.1.1.3 Informações sociodemográficas

3.Preencha as "Informações sociodemográficas" de acordo com as informações da ficha. Se a resposta de uma questão for "Sim", verifique as opções adicionais de preenchimento (ex.: Tem alguma deficiência? "Sim". Então, responda também "Se sim, quais?" outro exemplo; É membro de povo ou comunidade tradicional? Se sim, qual?). No momento da digitação, deve- se escolher uma das opções disponíveis no software, conforme seu preenchimento na ficha.

![](media/image643.png)

#### 7.2.1.1.4 Questionário autorreferido de condições/situações de saúde

4.Preencha as informações de "Condições/situações de saúde gerais" do cidadão de acordo com os dados da ficha. Observe que algumas perguntas devem ser especificadas caso a resposta seja "Sim";

![](media/image644.png)

#### 7.2.1.1.5 Cidadão em situação de rua

5.Preencha as informações de "Em situação de rua" de acordo com as informações registradas na ficha. Observe que a pergunta "Está em situação de rua" é obrigatória;

![](media/image645.png)

6.Após a digitação dos dados, clique no botão ![](media/image646.png) e, caso haja alguma inconsistência, o sistema mostrará mensagem na tela indicando os campos que deverão ser corrigidos. Se não houver inconsistência, o sistema salvará os dados e voltará para a tela anterior.

### 7.2.1.2 Adicionar Cadastro Individual com Termo de Recusa

Para fazer cadastro individual com termo de recusa, siga os passos:

- Passo 1. Preencha os dados de cabeçalho e de identificação do cidadão;

- Passo 2. Marque o campo "Termo de recusa do cadastro individual da Atenção Básica" quando o cidadão não desejar ser cadastrado pela equipe de saúde, seja Saúde da Família ou Unidade de Saúde Tradicional;

![](media/image647.png)

> ![](media/image59.png) **ATENÇÃO**: caso o campo "Termo de recusa" seja marcado, os campos ficam desabilitados para preenchimento, exceto os campos de identificação do cidadão.

## 7.2.2 Cadastro domiciliar e territorial

![](media/image648.png)

Na tela principal do CDS, clique no ícone "Cadastro domiciliar e territorial". A janela da "Lista de cadastro domiciliar" será mostrada, conforme a Figura 7.11. É possível visualizar a lista de cadastros realizados, o componente de filtro e as opções relacionadas a cada registro.

Figura 7.11 - Tela principal do cadastro domiciliar
![](media/image649.png)
Fonte: SAS/MS.

Como vimos nas orientações gerais de digitação das fichas, várias ações podem ser realizadas para cada registro. E, em especial para as fichas de Cadastro Domiciliar, ainda podem ser destacadas duas opções:

- ![](media/image631.png) **Cadastros individuais:** permite visualizar dados das famílias vinculadas àquele domicílio;

- ![](media/image650.png) **Atualizar**: permite atualizar os dados cadastrais do domicílio.

Por fim, o botão ![](media/image651.png) é utilizado para incluir novos cadastros domiciliares. Vamos observar como é realizado este cadastro.

### 7.2.2.1 Adicionar Cadastro Domiciliar

Após clicar no botão \"Adicionar\", o sistema mostrará a tela de preenchimento da ficha de cadastro, conforme a Figura 7.12.

Figura 7.12 - Adicionar cadastro domiciliar
![](media/image652.png)
Fonte: SAS/MS.

Para digitar a ficha de cadastro, observe os seguintes itens:

#### 7.2.2.1.1 Informações de cabeçalho

1.Preencha os campos do cabeçalho, digitando os dados que constam na ficha de cadastro;

![](media/image653.png)

a.Ao incluir o número do Cartão SUS do profissional, o sistema mostrará opções para o CNES e o INE que vêm da base de dados do CNES importado na instalação da aplicação;

b.Caso o profissional tenha apenas um vínculo no município, os dados serão preenchidos automaticamente.

c.Caso tenha mais de um, o sistema mostrará as opções e o digitador indicará o que está registrado na ficha. Também será apresentado para preenchimento, de acordo com a ficha, o campo "Data" em que o cadastro foi realizado;

#### 7.2.2.1.2 Informações de identificação e contato do domicílio

2.Preencha as informações do "Endereço/Local de permanência" do domicílio.

a.Após preenchimento do CEP, os campos "Município", "UF", "Bairro"  e "Tipo de logradouro" e "Nome de logradouro" são completados  automaticamente, conforme imagem a seguir:

![](media/image654.png)

b.Também é possível incluir, nesse cadastro, as informações sobre o "Tipo de imóvel" e "Telefones para contato". Atenção para o telefone, que deve estar acompanhado pelo número de DDD do município;

c.Para o "Tipo de imóvel", selecione uma das opções:

- 01 - Domicílio

- 02 - comércio

- 03 - terreno baldio

- 04 - Ponto Estratégico (PE: cemitério, borracharia, ferro- velho,  depósito de sucata ou materiais de construção, garagem de ônibus  ou veículo de grande porte)

- 05 - Escola

- 06 - Creche

- 07 - Abrigo

- 08 - Instituição de longa permanência para idosos

- 09 - Unidade prisional

- 10 - Unidade de medida sócio educativa

- 11 - Delegacia

- 12 - Estabelecimento religioso

- 99 - Outros


| **Atenção para as regras do sistema a partir do Tipo de Imóvel!**|
|- |
| **Domicílio:** |
|- Ao selecionar a opção \"01 - ­Domicílio\" para Tipo de Imóvel, serão desabilitados os campos \"Nome da instituição de permanência\" e \"Existem outros profissionais de saúde vinculados à instituição (não inclui profissionais da rede pública de saúde)?\", além do grupo \"Identificação do responsável técnico da instituição de permanência\". Será alterado o nome do grupo \"Termo de recusa\" para \"Termo de recusa do cadastro domiciliar e territorial da Atenção Básica\". |

| **Imóveis sem finalidade de moradia/longa permanência:**|
|- |
| - No caso da seleção das opções \"02 - ­ Comércio\", \"03 - ­ Terreno baldio\", \"04 - ­ Ponto estratégico\", \"05 - ­ Escola\", \"06 - ­ Creche\", \"12 - ­ Estabelecimento religioso\" ou \"99 - ­ \Outros\", serão desabilitados os grupos \"Condições de moradia\", \"Animais no domicílio?\", \"Famílias\", \"Identificação do responsável técnico da instituição de permanência\" e \"Termo de recusa\". Também serão desabilitados os campos \"Nome da instituição de permanência\" e \"Existem outros profissionais de saúde vinculados à instituição (não inclui profissionais da rede pública de saúde)?\".|

| **Instituição de longa permanência:**|
|- |
| - E se forem selecionadas as opções \"07 - ­ Abrigo\", \"08 - ­ Instituição de longa permanência para idosos\", \"09 - ­ Unidade prisional\", \"10 - ­ Unidade de medida sócio educativa\" ou \"11 - ­ Delegacia\", os campos \"Situação de moradia/Posse de terra\", \"Tipo de domicílio\", \"Nº de cômodos\", \"Em caso de área de produção rural: condição de posse e uso da terra\", \"Material predominante na construção das paredes externas de seu domicílio\" e \"Tipo de acesso ao domicílio\", os grupos \"Animais no domicílio\" e \"Famílias\" serão desabilitados. Nesta ocasião, será alterado o nome do termo de recusa para \"Termo de recusa do cadastro da instituição de permanência\".|

#### 7.2.2.1.3 Condições de moradia

3.Preencha as informações de "Condições de moradia" de acordo com o registrado na ficha. Caso o campo "Animais no domicílio" estiver marcado com a resposta "Sim", informe "Qual(is)" e "Quantos", como mostra a imagem abaixo:

![](media/image655.png)

#### 7.2.2.1.4 Adicionar núcleo familiar

4.Preencha as informações do bloco "Famílias" (núcleos familiares) que vivem no domicílio. Cada uma é representada pelo número do CNS ou CPF do Responsável Familiar de cada núcleo familiar. Para adicionar uma família, basta preencher os campos no início do bloco e clicar no botão "Confirmar"![](media/image656.png);

![](media/image657.png)

a.Caso existam **mais famílias** informadas na ficha, **repita o processo conforme item anterior** para todas as linhas que identificam núcleos familiares daquele domicílio;

b.Ao digitar as informações, após confirmada a inclusão, caso alguma tenha sido registrada de forma incorreta, é possível alterá- la de um registro já incluído, clicando na opção ![](media/image658.png) "Editar". O registro será habilitado para edição nos campos de entrada de dados principal. Para salvar, clique novamente no botão "Confirmar";

c.Durante a atualização deste registro, ver mais na Seção 7.1.3, é possível indicar se a família "mudou- se" clicando na caixa correspondente. Esta opção está desabilitada ao adicionar nova família;

d.Caso o registro tenha sido inserido de forma incorreta, também é possível excluir a família. Para excluir o registro, clique na opção ![](media/image150.png) "Excluir" e este será removido;

5.Após a digitação dos dados, clique no botão ![](media/image646.png) e, caso haja alguma inconsistência, o sistema mostrará mensagem na tela indicando os campos que deverão ser corrigidos. Se não houver inconsistência, o sistema salvará os dados e voltará para a tela anterior.

### 7.2.2.2 Adicionar Cadastro Domiciliar com Termo de Recusa

O campo ao final da ficha/tela do termo de recusa tem um processo de cadastro diferenciado. Ao ter um cadastro domiciliar com termo de recusa preenchido, basta adicionar os dados de identificação do domicílio e marcar a opção \"Termo de recusa do cadastro domiciliar da Atenção Básica\", conforme a Figura 7.13.

Figura 7.13 - Termo de recusa do cadastro domiciliar
![](media/image659.png)
Fonte: SAS/MS.

> ![](media/image59.png) **ATENÇÃO**: caso o campo de termo de recusa seja marcado, os campos ficam desabilitados para preenchimento, exceto os campos de identificação do imóvel.

## 7.2.3 Atualizar Cadastro da Atenção Básica

A ferramenta de "Atualizar" é parte importante do processo de trabalho das equipes para manter as informações do território atualizadas.

Ao clicar no botão "Atualizar" ![](media/image660.png) é iniciado o procedimento de atualização das fichas. Serão apresentadas todas as informações do último registro salvo, com a exceção dos Campos do cabeçalho (CNS do profissional, CNES, INE, Microárea e Data) e do Campo \"Saída do cidadão do cadastro\". Será permitida a alteração dos dados, exceto do campo \"CNS do cidadão\" quando estiver preenchido. Ao informar o CNS ou CPF do cidadão, o sistema deverá verificar se o mesmo existe na base de dados e apresentará a mensagem \"CNS já cadastrado no sistema.\" com opção \"OK\" e não permitirá salvar o registro até que esta ação seja resolvida. Caso contrário, as alterações serão salvas normalmente.

# 7.3 Fichas de Atendimento

As fichas de atendimento são utilizadas para registro dos profissionais de nível superior. Elas não objetivam esgotar todo o processo de atendimento de um indivíduo e também não substituem o registro clínico feito no prontuário em papel. As informações nelas contidas foram selecionadas segundo a sua relevância no cuidado ao cidadão e por comporem indicadores de monitoramento e avaliação para a AB e para as Redes de Atenção à Saúde como um todo.

## 7.3.1 Ficha de Atendimento Individual

![](media/image661.png)

Na tela principal do Módulo do CDS, clique no ícone "Ficha de Atendimento Individual". Será apresentada a lista das "Fichas de Atendimento Individual" digitadas, em que constará a Data do atendimento, CNS do profissional responsável pelo atendimento, CBO do profissional, CNES da UBS, e o INE da equipe, conforme a Figura 7.14.

Figura 7.14 - Lista de Fichas de Atendimento Individual
![](media/image662.png)
Fonte: SAS/MS.

### 7.3.1.1 Adicionar Ficha de Atendimento Individual

Para informar nova Ficha de Atendimento Individual, clique no botão ![](media/image663.png). O sistema exibirá uma tela , conforme a Figura 7.15.

Figura 7.15 - Adicionar Ficha de Atendimento Individual
![](media/image664.png)
Fonte: SAS/MS.

Para preencher os dados da Ficha de Atendimento Individual, atente para os itens a seguir:

#### 7.3.1.1.1 Informações de cabeçalho

1.Preencha o cabeçalho da ficha (Figura 7.15), ao incluir o número do CNS do profissional, o sistema mostrará opções para o CBO, CNES e INE que vêm da base de dados do CNES importado na instalação da aplicação;

![](media/image665.png)

a.caso o profissional tenha apenas um vínculo no município, os dados serão preenchidos automaticamente;

b.caso o profissional tenha mais de um vínculo, o sistema mostrará as opções e o digitador indicará o que está registrado na ficha. Também são apresentados para preenchimento os campos para inclusão de outros profissionais da equipe para os casos em que houver a realização de consulta compartilhada;

2.para informar novo registro de atendimento, clique no botão ![](media/image666.png). O sistema exibirá uma tela com cabeçalho preenchido (somente leitura) e os dados a serem completados para cada atendimento;

a.deve- se obedecer o conteúdo da ficha, portanto, poderão ser  registrados até 13 atendimentos para usuários diferentes e  realizados pelo mesmo profissional;

3.quando for realizado um atendimento compartilhado é necessário incluir os dados do outro profissional que participou.

#### 7.3.1.1.2 Dados de identificação do cidadão

4.digite os dados conforme preenchido na ficha, iniciando- se pelos dados de identificação do cidadão e de alguns dados sobre o atendimento;

![](media/image667.png)

5.na sequência, digite o tipo de atendimento e alguns dados de saúde, conforme preenchido na ficha;

![](media/image668.png)

6.após, digite as informações correspondentes ao bloco "Problema/Condição Avaliada". Atenção aos campos CIAP2 e CID10, que são informados usando códigos correspondentes das classificações e estão no verso da ficha, acompanhados de outras opções;

![](media/image669.png)

7.na sequência, marque os exames solicitados e avaliados. Cada *checkbox* corresponde a um item marcado na ficha pelo profissional. Atenção aos itens "Outros exames", que são informados pelo código do SIGTAP e acompanhados de uma marcação se foi solicitado (S) e/ou avaliado (A);

![](media/image670.png)

8.por último, informe se ficou em observação. Caso se trate de **profissional do NASF** ou Polo, marque as opções correspondentes. Assinale, também, as opções de conduta/desfecho e/ou encaminhamento, caso tenha sido assinalado na ficha;

![](media/image671.png)

9.após a digitação dos dados, clique no botão ![](media/image672.png) e, caso haja alguma inconsistência, o sistema mostrará mensagem na tela indicando os campos que deverão ser corrigidos. Se não houver inconsistência, o sistema salvará os dados e voltará para a tela anterior.

#### 7.3.1.1.3 Lista de registro dos atendimentos individuais

O sistema traz, para cada ficha, a lista dos atendimentos individuais. Ao clicar em visualizar ou editar é possível acessar o conteúdo do atendimento, facilitando a busca do registro pelo usuário do sistema, como podemos ver na Figura 7.16.

Figura 7.16 - Lista de registros de atendimento na Ficha de Atendimento Individual
![](media/image673.png)
Fonte: SAS/MS.

Ao finalizar a digitação da Ficha de Atendimento Individual, clique no botão ![](media/image634.png)

## 7.3.2 Ficha de Atendimento Odontológico Individual

![](media/image674.png)

Na tela principal, clique no ícone "Ficha de Atendimento Odontológico". Será apresentada a lista das "Fichas de Atendimento Odontológico" digitadas, conforme a Figura 7.17, em que constará a data do atendimento, o número do CNS do profissional que preencheu a ficha, o CBO do profissional, o código CNES da UBS e o código INE da equipe.

Figura 7.17 - Lista de Fichas de Atendimento Odontológico
![](media/image675.png)
Fonte: SAS/MS.

### 7.3.2.1 Adicionar Ficha de Atendimento Odontológico

Para informar nova Ficha de Atendimento Odontológico, clique no botão ![](media/image666.png) e atente para os itens a seguir:

1.após clicar no botão \"Adicionar\", o sistema mostrará a tela de preenchimento da ficha de cadastro;

#### 7.3.2.1.1 Informações de cabeçalho

2.digite os dados do cabeçalho conforme preenchido na ficha, ao incluir o CNS do profissional, o sistema mostrará opções para o CBO, CNES e INE que vêm da base de dados do CNES importado na instalação da aplicação;

![](media/image665.png)

a.caso o profissional tenha apenas um vínculo no município, os dados serão preenchidos automaticamente;

b.caso o profissional tenha mais de um vínculo, o sistema mostrará as opções e o digitador indicará o que está registrado na ficha;

c.também são apresentados para preenchimento os campos para inclusão de outros profissionais da equipe para os casos em que houver a realização de atendimento compartilhado;

3.para informar novo registro de atendimento, clique no botão ![](media/image666.png). O sistema exibirá uma tela com cabeçalho preenchido (somente leitura) e os dados a serem completados para cada atendimento;

a.deve- se obedecer ao conteúdo da ficha, portanto poderão ser registrados até 13 atendimentos para usuários diferentes e realizados pelo mesmo profissional;

#### 7.3.2.1.2 Dados de identificação do cidadão e do serviço de saúde

4.digite os dados no sistema conforme preenchido na ficha, iniciando pelos dados de identificação do cidadão e alguns dados sobre o atendimento;

![](media/image676.png)

5.digite os dados "Tipo de atendimento", "Tipo de consulta" e "Vigilância em saúde bucal", que são obrigatórios;

![](media/image677.png)

6.digite os dados de procedimentos realizados no sistema, conforme preenchido na ficha. Perceba que, diferentemente da Ficha de Atendimento Individual, os procedimentos de odontologia são preenchidos com a quantidade;

7.no campo "Outros procedimentos", digite os procedimentos preenchidos com a quantidade informada na coluna da ficha e o código do SIGTAP informado na linha da ficha, nos respectivos campos "Quantidade" e "Procedimento", e clique em "Confirmar". Faça isso para todos os procedimentos preenchidos na coluna correspondente ao registro de atendimento do cidadão;

![](media/image678.png)

8.por fim, digite os itens de fornecimento, caso estes tenham sido preenchidos na ficha, e a conduta/desfecho e/ou encaminhamento, caso tenha sido realizado no atendimento;

![](media/image679.png)

9.após a digitação dos dados, clique no botão ![](media/image672.png) e, caso haja alguma inconsistência, o sistema mostrará mensagem na tela indicando os campos que deverão ser corrigidos. Se não houver inconsistência, o sistema salvará os dados e voltará para a tela anterior.

#### 7.3.2.1.3 Lista de registro dos atendimentos individuais

Diferentemente das versões anteriores do CDS, em que cada registro de atendimento era mostrado em abas, desde a versão 1.3, o sistema traz a lista de atendimentos, representada em forma de colunas na Ficha de Atendimento Odontológico, facilitando a busca do registro pelo usuário do sistema, como podemos ver na Figura 7.18.

Figura 7.18 - Lista de registros de atendimento na Ficha de Atendimento Odontológico
![](media/image680.png)
Fonte: SAS/MS.

Ao finalizar a digitação da Ficha de Atendimento Odontológico, clique no botão ![](media/image634.png).

# 7.4 Ficha de Atividade Coletiva

![](media/image681.png)

A Ficha de Atividade Coletiva visa ao registro das atividades realizadas pelas equipes conforme as necessidades do território e capacidade da equipe de estruturar as ações. Nela, pode ser registrada ações estruturantes para a organização do processo de trabalho, como reuniões da própria equipe de saúde, reuniões com outras equipes de saúde, ou reuniões com outros órgãos, além das atividades de saúde voltadas para a população, como: educação em saúde, atendimentos, avaliações em grupo e mobilizações sociais, conforme podemos ver na Figura 7.19.

Figura 7.19 - Tipo de atividade da Ficha de Atividade Coletiva
![](media/image682.png)
Fonte: SAS/MS.

## 7.4.1 Adicionar Ficha de Atividade Coletiva

Na tela principal, clique no ícone "Ficha de Atividade Coletiva". Será apresentada a lista das "Fichas de Atividade Coletiva" digitadas, em que constará a data da atividade, o tipo de atividade realizada, o número do Cartão SUS do profissional responsável pela atividade, o CBO do profissional, o código CNES da UBS e o código INE da equipe, conforme a Figura 7.20.

Figura 7.20 - Lista de atividade coletiva
![](media/image683.png)
Fonte: SAS/MS.

Para informar Ficha de Atividade Coletiva, clique no botão ![](media/image626.png) e atente para os itens a seguir:

1.Digite as informações sobre a atividade coletiva realizada nos campos apresentados no início da ficha. Perceba que o cabeçalho é um pouco diferente das demais fichas, informando dados do profissional responsável por organizar e conduzir a atividade coletiva;

![](media/image684.png)

2.Digite as informações da realização da atividade, como Turno, Programa saúde na escola, Local de atividade, etc.;

a.Caso seja uma atividade do Programa Saúde na Escola, o n⁰ do INEP (Escola/Creche) deve estar preenchido no bloco "Local da  atividade", assim como, deve ser preenchida no bloco "Programa  saúde na escola", se é uma atividade realizada pela equipe de educadores da escola e/ou pela equipe de saúde;

b.Atividades realizadas em outros estabelecimentos de saúde que não o estabelecimento de origem da equipe, deverá ser preenchido o campo "CNES" no bloco Local de atividade (Exemplo: quando realiza atividade em um Polo de Academia da Saúde);

> ![](media/image74.png) **ATUALIZAÇÃO:** A partir da versão 3.1, no momento da digitação da ficha será apresentada uma lista com as Escolas do Município no campo INEP, com o isso deve- se escolher uma das escolas listadas para informar onde a Atividade Coletiva foi realizada.

3.No bloco "Profissionais participantes", preencha o n⁰ do CNS e o CBO de cada profissional que participou da atividade e clique em ![](media image685.png), inserindo- os na lista, um a um;

a.Caso necessário, para excluir um profissional da lista, clique  na opção ![](media/image686.png) "Excluir";

4.Preencha o "Nº de participantes" e o campo "Nº de avaliações alteradas", o qual traz o resultado da contagem de participantes da atividade coletiva que tiveram a marcação de "Avaliação alterada" na lista de participantes;

### 7.4.1.1 Atividades de planejamento da equipe e temas para reunião

5.As atividades 01, 02 e 03 estão relacionadas com quaisquer dos assunto do bloco "Temas para reunião", conforme imagem abaixo;

![](media/image687.png)

a.Quando a atividade não for destinada a atender aos 03 (três) itens acima descritos, o sistema desabilita o bloco "Temas para reunião";

### 7.4.1.2 Atividades de saúde

6.As atividades relacionadas a ações de saúde com os usuários (itens 04, 05, 06 e 07) fazem relação com os blocos "Público- alvo", "Temas para saúde" e "Práticas em saúde";

a.O bloco "Público alvo" é de múltipla opção, sendo de preenchimento obrigatório para as atividades 4, 5, 6 e 7;

b.O bloco "Temas para saúde" também é de múltipla opção, sendo de preenchimento obrigatório para as atividades 4, 5 e 7;

c.O bloco "Práticas em saúde" é de opção única e de preenchimento obrigatório para a atividade 6, e de múltipla opção para atividades 5.

![](media/image688.png)

### 7.4.1.3 Adicionar participantes

7.Para adicionar os participantes da atividade coletiva, é necessário incluir os dados do CNS do cidadão, data de nascimento e sexo;

![](media/image689.png)

8.Caso a opção "Prática em saúde" seja marcada como \"Antropometria\", os campos "Peso" e "Altura" da lista de participantes se tornam obrigatórios;

9.Para atividades de "avaliação/procedimento coletivo", é possível indicar se foi identificada alguma alteração durante a avaliação realizada ao cidadão usando a opção "Avaliação alterada".

10.É possível registrar no bloco "Práticas em saúde" qual sessão do Programa Nacional de Controle do Tabagismo (PNCT) os cidadãos participaram. Ao clicar em uma das sessões do PNCT habilita- se o campo "Programa Nacional de Controle do Tabagismo", onde poderá informar, caso necessário, se o cidadão cessou o hábito de fumar e/ou abandonou o grupo;

11. Clique no botão ![](media/image685.png) e o sistema incluirá o cidadão na lista e mostrará uma linha com campos em branco para o próximo preenchimento. Repita esses passos para informar todos os participantes da atividade coletiva;

12. Caso seja necessário alterar as informações de algum participante, clique no ícone ![](media/image658.png) "Editar" e as informações serão carregadas nos campos abertos. Para salvar, clique no ícone ![](media/image685.png). Há possibilidade de edição das fichas até o momento do seu envio;

13. Caso seja necessário excluir um participante, clique no ícone ![](media/image150.png) "Excluir". O registro será removido;

14. Ao finalizar a digitação da ficha, clique no botão ![](media/image646.png).

## 7.4.2 Copiar Ficha de Atividade Coletiva

Além das opções- padrão da listagem da Ficha de Atividade Coletiva, ainda tem a opção ![](media/image690.png) "**Copiar**", que estará disponível apenas para o caso de uma atividade coletiva do tipo **"Avaliação/Procedimento Coletivo"**. Para outros tipos de atividades, esta opção não estará disponível, como podemos visualizar na Figura 7.21.

Essa opção auxilia, portanto, nas atividades de avaliação/procedimento coletivo feitas com o mesmo grupo de indivíduos, por exemplo, as atividades do Programa Saúde na Escola.

Figura 7.21 - Tipo de atividade em que a função "Copiar" está disponível (somente para a avaliação/procedimento coletivo)
![](media/image691.png)
Fonte: SAS/MS.

# 7.5 Ficha de Procedimentos

![](media/image692.png)

A Ficha de Procedimentos é utilizada para a coleta de dados sobre a realização de procedimentos ambulatoriais. Ela capta os procedimentos que foram realizados por determinado profissional, diferentemente da Ficha de Atendimento Individual, em que são registradas a solicitação e a avaliação de exames.

## 7.5.1 Como registrar as informações de uma Ficha de Procedimentos

Na tela principal, clique no ícone "Ficha de Procedimentos". Será apresentada a lista das "Fichas de Procedimento" digitadas, em que constará a data do atendimento, o CNS do profissional responsável pela ficha, o CBO do profissional, o código CNES da UBS e o código INE da equipe, conforme abaixo:

Figura 7.22 - Tela principal com a lista de Fichas de Procedimentos
![](media/image693.png)
Fonte: SAS/MS.

### 7.5.1.1 Adicionar Ficha de Procedimentos

Figura 7.23 - Adicionar Ficha de Procedimentos
![](media/image694.png)
Fonte: SAS/MS.

1.Após clicar no botão "Adicionar", o sistema mostrará a tela de preenchimento da Ficha de Procedimentos para ser preenchida;

#### 7.5.1.1.1 Informações de cabeçalho

2.Digite o cabeçalho conforme preenchido na ficha;

![](media/image695.png)

3.Ao incluir o número do CNS do profissional, o sistema mostrará opções para o CNES e INE que vêm da base de dados do CNES importado na instalação da aplicação;

4.Caso o profissional tenha apenas um vínculo no município, os dados serão preenchidos automaticamente;

5.Caso o profissional tenha mais de um vínculo, o sistema mostrará as opções e o digitador indicará o que está registrado na ficha. Diferentemente da Ficha de Atendimento Individual, a Ficha de Procedimentos é por profissional e não permite o registro de ações compartilhadas;

6.Para informar novo registro de procedimentos de um atendimento, clique no botão ![](media/image666.png);

#### 7.5.1.1.2 Registro de procedimentos individualizados

7.O primeiro bloco de informações são relacionados aos dados do cidadão atendido, local de atendimento e se houve escuta inicial/orientação;

![](media/image696.png)

8.Os campos marcados com um asterisco (\*) na cor azul, são de preenchimento obrigatório. O campo "Nº do prontuário" deve ser numérico. O campo "CNS do cidadão" será validado por meio de algoritmo e deverá possuir, no mínimo, 15 caracteres;

#### 7.5.1.1.3 Detalhamento dos procedimentos individualizados realizados

9.Preencha os dados solicitados referentes ao atendimento do cidadão, marcando os procedimentos conforme preenchido na ficha;

![](media/image697.png)

10. Para os campos de \"Outros Procedimentos\", preencha o campo \"Código do SIGTAP\" conforme informado na ficha, e aperte a tecla \"Enter\" ou clique no procedimento. Todos os procedimentos informados por código do SIGTAP serão incluídos na Lista de Procedimentos;

11. Ao finalizar o preenchimento, clique no botão ![](media/image672.png). Caso haja alguma inconsistência, o sistema mostrará mensagem na tela indicando os campos que deverão ser corrigidos. Do contrário, o sistema salvará os dados e voltará para a tela com a lista de registros da ficha.

#### 7.5.1.1.3 Lista de registro dos procedimentos individualizados

O sistema traz, para cada ficha, uma lista dos registros dos procedimentos individualizados por cidadão. Ao clicar em visualizar ou editar é possível acessar o conteúdo do registro, facilitando a busca do registro pelo usuário do sistema, como podemos ver na Figura 7.24.

Figura 7.24 - Lista de registros de atendimento na Ficha de Procedimentos
![](media/image698.png)
Fonte: SAS/MS.

O número de registros deve obedecer ao conteúdo da ficha, portanto poderão ser registrados no máximo 14 registros para cada cidadão e realizados pelo mesmo profissional.

#### 7.5.1.1.4 Registro dos procedimentos consolidados

Com intuito de dar mais destaque e facilitar o preenchimento e uso do bloco para registro dos procedimentos consolidados, este se apresenta abaixo da lista de procedimentos individualizados, como podemos visualizar na Figura 7.25.

Figura 7.25 - Registro de procedimentos consolidados
![](media/image694.png)
Fonte: SAS/MS.

Como podemos visualizar, os procedimentos individualizados permanecem em telas separadas para facilitar o registro dos procedimentos consolidados. Caso não haja nenhum procedimento individualizado, basta preencher os itens consolidados e clicar no botão ![](media/image634.png) para que o sistema guarde o registro da ficha.

# 7.6 Ficha de Visita Domiciliar e Territorial

![](media/image699.png)

A Ficha de Visita Domiciliar e Territorial tem como objetivo principal registrar as atividades de visitas domiciliares do Agente Comunitário de Saúde (ACS) ou do Agente de Combate a Endemias (ACE), realizadas no território adstrito à equipe da UBS.

## 7.6.1 Como registrar as informações de uma Ficha de Visita Domiciliar e Territorial

Na tela principal, clique no ícone "Ficha de Visita Domiciliar e Territorial". A janela da lista de "Visita domiciliar" será mostrada, conforme a Figura 7.26.

Figura 7.26 - Listagem da Ficha de Visita Domiciliar
![](media/image700.png)
Fonte: SAS/MS.

## 7.6.2 Adicionar Ficha de Visita Domiciliar

Após clicar no botão ![](media/image701.png), siga os passos:

- Passo 1. Preencha os campos do cabeçalho com o CNS do profissional e a data. O sistema automaticamente preencherá os campos CBO e CNES;

![](media/image702.png)

- Passo 2. após preencher os dados do cabeçalho, clique no botão ![](media/image626.png) para incluir uma visita domiciliar e territorial individualmente;

### 7.6.2.1 Identificação do usuário e do serviço de saúde

- Passo 3. Na sequência, digite as informações de identificação do usuário e alguns detalhes sobre o serviço de saúde;

![](media/image703.png)

### 7.6.2.2 Detalhamento da visita domiciliar

- Passo 4. Marque, conforme preenchido na ficha, o motivo da visita. Perceba que é possível escolher múltiplas opções;

![](media/image704.png)

- Passo 5. Caso haja necessidade de acompanhamento do peso e altura dos indivíduos visitados, preencha os campos "Peso (kg)" e "Altura (cm)" do bloco "Antropometria".

![](media/image705.png)

- Passo 6. Na sequência, marque a opção de desfecho da visita;

![](media/image706.png)

- Passo 7. Para finalizar , clique no botão ![](media/image707.png);

- Caso haja alguma inconsistência ou ausência de preenchimento de campos obrigatórios, o sistema mostrará mensagem na tela indicando os que deverão ser corrigidos ou preenchidos. Caso contrário, os dados serão salvos e o sistema retornará à lista das fichas de visitas;

- Para cada visita, adicione novo registro, conforme orientado nos passos acima;

- Como na ficha de papel, nesta tela, poderão ser registradas **até 23 visitas domiciliares e territoriais** para cidadãos diferentes e realizados pelo mesmo profissional, na mesma data e turno. Para visualizar todos os registros, use a barra de rolagem (detalhe indicado pela seta vermelha);

![](media/image708.png)

- Passo 8. Ao digitar todas as visitas, clique no botão ![](media/image707.png) para concluir a digitação da ficha.

# 7.7 Marcadores de Consumo Alimentar

![](media/image709.png)

Esse instrumento permite a identificação de marcadores positivos ou negativos da alimentação e, de maneira mais dinâmica, a composição de indicadores.

> ![](media/image84.png) **DICA**: para auxiliar a utilização da ficha, que pode **ser feita por qualquer profissional da Atençãoásica**, e a orientação sobre práticas alimentares saudáveis, recomenda- se o uso do documento "Orientações para Avaliação de Marcadores de Consumo Alimentar na Atenção Básica", disponível em [[http://dab.saude.gov.br/portaldab/biblioteca.php?conteudo=publicacoes/marcadores_consumo_alimentar_atencao_basica]](http://dab.saude.gov.br/portaldab/biblioteca.php?conteudo=publicacoes/marcadores_consumo_alimentar_atencao_basica).

Após clicar no botão ![](media/image701.png), siga os passos:

- Passo 1. Preencha os campos do cabeçalho com o número do CNS do profissional e a data da avaliação. O sistema automaticamente preencherá os campos CBO e CNES;

- Passo 2. Identifique o cidadão atendido. Os campos "Nome do cidadão", "Data de nascimento", "Sexo" e "Local de atendimento" são de preenchimento obrigatório registre também o CNS ou CPF do cidadão.

![](media/image710.png)

- Passo 3. Preencha os campos do bloco referente às questões específicas organizadas segundo o grupo etário habilitado pelo sistema, de acordo com a data de nascimento do cidadão.

- Todas as questões do bloco são de preenchimento obrigatório, respeitando- se os casos de opção de múltipla escolha.

**Crianças menores de seis meses:**

![](media/image711.png)

**Crianças de 6 a 23 meses:**

![](media/image712.png)

**Crianças com dois anos ou mais, adolescentes, adultos, gestantes e idosos:**

![](media/image713.png)

- Passo 4. Ao finalizar a digitação da ficha, clique no botão ![](media/image646.png).

# 7.8 Ficha de Avaliação de Elegibilidade e Admissão

![](media/image714.png)

**Exclusiva para uso em Serviço de Atenção Domiciliar (SAD)**, pode ser utilizada pelos profissionais das equipes de Atenção Domiciliar (AD), cadastrados no CNES, por meio dos tipos: i) Equipe Multiprofissional de Atenção Domiciliar (EMAD); e ii) Equipe Multiprofissional de Apoio (EMAP). Esse instrumento permite identificar os cidadãos elegíveis para acompanhamento pelas equipes de AD.

## 7.8.1 Como registrar as informações de uma Ficha de Avaliação de Elegibilidade

Na tela principal, clique no ícone "Ficha de Avaliação de Elegibilidade". A janela da lista de fichas digitadas de avaliações de elegibilidade e admissão será mostrada, conforme a Figura 7.27.  

Figura 7.27 - Listagem da Fichas de Avaliação de Elegibilidade
![](media/image715.png)
Fonte: SAS/MS.

## 7.8.2 Adicionar Ficha de Avaliação de Elegibilidade e Admissão

Após clicar no botão "Adicionar", siga os passos:

- Passo 1. Preencha os dados de identificação do profissional que realizou a avaliação e alguns detalhes sobre o serviço de saúde;

- Passo 2. Clique no Turno em que foi realizado a avaliação e que está indicado na ficha;

- Passo 3. Preencha os dados de identificação do cidadão e a procedência;

![](media/image716.png)

- Passo 4. Na sequência, preencha os dados da avaliação;

![](media/image717.png)

- Passo 5. Informar os dados da conclusão, atenção aos campos de preenchimento obrigatórios condicionados à conclusão:

a.inelegível;

![](media/image718.png)

b.elegível, com admissão na equipe;

![](media/image719.png)

c.No caso de elegível, mas sem admissão na equipe, marcar o tipo de encaminhamento;

![](media/image720.png)

Passo 5. Conclua o preenchimento, respeitando minimamente os campos obrigatórios, e clique em "Salvar" para concluir.

![](media/image721.png)

7.9 Ficha de Atendimento Domiciliar

![](media/image722.png)

Esta ficha é de uso **exclusivo do Serviço de Atenção Domiciliar (SAD)**, os profissionais de nível superior da equipe de AB deverão informar o atendimento domiciliar na ficha de atendimento individual no campo "Local de Atendimento" conforme descrito no capítulo 7.1.3. Por tanto, a Ficha de atendimento domiciliar pode ser utilizada pelos **profissionais das equipes de Atenção Domiciliar**, cadastrados no CNES, por meio dos tipos: i) Equipe Multiprofissional de Atenção Domiciliar (EMAD); e ii) Equipe Multiprofissional de Apoio (EMAP). Esse instrumento permite registrar os atendimentos realizados pelas equipes de AD.

Na tela principal do Módulo do CDS, clique no ícone "Ficha de Atendimento Domiciliar". Será apresentada a lista das Fichas de Atendimento Domiciliar digitadas, conforme a Figura 7.28.

Figura 7.28 - Lista de Fichas de Atendimento Domiciliar
![](media/image723.png)
Fonte: SAS/MS.

## 7.9.1 Adicionar Ficha de Atendimento Domiciliar

Para informar nova Ficha de Atendimento Domiciliar, clique no botão![](media/image666.png){width="0.9945745844269467in" height="0.2572178477690289in"}. O sistema exibirá uma tela, conforme Figura 7.29.

Figura 7.29 - Adicionar Ficha de Atendimento Domiciliar
![](media/image724.png)
Fonte: SAS/MS.

Para preencher os dados da Ficha de Atendimento Domiciliar, siga os passos:

- Passo 1. Após clicar no botão \"Adicionar\", o sistema mostrará a tela de preenchimento da ficha;

### 7.9.1.1 Informações de cabeçalho

- Passo 2. Preencha o cabeçalho da ficha;

- Ao incluir CNS do profissional, o sistema mostrará opções para o CNES e INE que vêm da base de dados do CNES importado na instalação da aplicação;

- Caso o profissional tenha apenas um vínculo no município, os dados serão preenchidos automaticamente;

- Caso o profissional tenha mais de um vínculo, o sistema mostrará as opções e o digitador indicará o que está registrado na ficha;

- Passo 3. Para informar novo registro de atendimento (registro em **colunas** da ficha), clique no botão ![](media/image626.png). O sistema exibirá uma tela com cabeçalho preenchido (somente leitura) e os dados a serem completados para cada atendimento;

### 7.9.1.2 Dados de identificação do cidadão

- Passo 4. Digite os dados conforme preenchido na ficha, iniciando pelo Turno do atendimento domiciliar, os dados de identificação do cidadão, local de atendimento e a Modalidade AD.

![](media/image725.png)

- Passo 5. Na sequência, clique no tipo de atendimento, conforme preenchido na ficha;

- Passo 6. Clique na Condição(ões) avaliada(s);

![](media/image726.png)

- Passo 7. Na sequência, clique nos procedimentos realizados no atendimento domiciliar;

![](media/image727.png)

- Passo 8. Na sequência, insira a "conduta/desfecho" e/ou o encaminhamento, caso tenha sido informado na ficha do atendimento domiciliar;

![](media/image728.png)

- Passo 9. Após a digitação dos dados, clique no botão ![](media/image672.png) e, caso haja alguma inconsistência, o sistema mostrará mensagem na tela indicando os campos que deverão ser corrigidos. Se não houver inconsistência, o sistema salvará os dados e voltará para a tela anterior.

### 7.9.1.3 Lista de registro dos atendimentos individuais

- Passo 10. Ao finalizar a digitação dos registros de atendimento da Ficha de Atendimento Domiciliar, clique no botão![](media image634.png) para concluir a digitação da ficha.

# 7.10 Ficha Complementar - Registro de Emergência em Saúde Pública Síndrome Neurológica por Zika/Microcefalia

![](media/image729.png)

Na tela principal do Módulo do CDS, clique no ícone "Síndrome neurológica por Zika/Microcefalia". Será apresentada a lista das fichas digitadas, em que constará a data do atendimento, o número do Cartão SUS do cidadão, o número do cartão do SUS do responsável familiar e o turno do atendimento., conforme a Figura 7.30.

Figura 7.30 - Lista de Fichas complementares
![](media/image730.png)
Fonte: SAS/MS.

## 7.10.1 Adicionar Ficha complementar

Para informar nova Ficha complementar, clique no botão ![](media/image626.png). O sistema exibirá os dados da ficha.

### 7.10.1.1 Informações de cabeçalho

1.Preencha o cabeçalho da ficha;

![](media/image731.png)

2.Ao incluir o número do CNS do profissional, o sistema mostrará opções para o CBO, CNES e INE que vêm da base de dados do CNES importado na instalação da aplicação;

a.Caso o profissional tenha apenas um vínculo no município, os dados serão preenchidos automaticamente;

b.Caso o profissional tenha mais de um vínculo, o sistema mostrará as opções e o digitador indicará o que está registrado na ficha. Também são apresentados para preenchimento os campos para inclusão de outros profissionais da equipe para os casos em que houver a realização de consulta compartilhada;

3.Para informar novo registro de atendimento, após finalizado e salvado o preenchimento da ficha anterior, ao retornar para a tela apresentada pela Figura 7.30, clique no botão ![](media/image666.png). O sistema exibirá uma tela com cabeçalho preenchido (somente leitura) e os dados a serem completados para cada atendimento;

4.Deve- se obedecer ao conteúdo da ficha, portanto poderão ser registrados até 13 atendimentos para usuários diferentes e realizados pelo mesmo profissional;

### 7.10.1.2 Dados de identificação do cidadão

7.Digite os dados de identificação do cidadão, conforme preenchido na ficha;

![](media/image732.png)

8.Na sequência, digite a data e o resultados dos exames correspondentes;

![](media/image733.png)

9.Após a digitação dos dados, clique no botão ![](media/image634.png) e, caso haja alguma inconsistência, o sistema mostrará mensagem na tela indicando os campos que deverão ser corrigidos. Se não houver inconsistência, o sistema salvará os dados e voltará para a tela anterior.

# 7.11 Ficha de vacinação

![](media/image734.png)

Esta ficha é para o registro dos imunobiológicos, soros e imunoglobulinas administradas no âmbito da Atenção Básica e o seu registro é fundamental para a continuidade do cuidado e acompanhamento da imunização do cidadão conforme preconizado pelo Programa Nacional de Imunização do Ministério da Saúde.

Na tela principal do Módulo do CDS, clique no ícone "Ficha de vacina". Será apresentada a lista das fichas de vacinação digitadas com as informações CNS do cidadão, Data de nascimento, sexo e turno.

Figura 7.31 - Adicionar Vacinação Individualizada
![](media/image735.png)
Fonte: SAS/MS.

## 7.11.1 Adicionar Ficha de vacinação

Observando a Figura 7.31, para adicionar uma nova ficha de vacinação basta clicar no botão ![](media/image736.png){width="1.1666666666666667in" height="0.28125in"} e aparecerá a seguinte tela:

Figura 7.31 - Adicionar Vacinação Individualizada
![](media/image737.png)
Fonte: SAS/MS.

Em seguida preencha o cabeçalho da Ficha de vacina no sistema.

### 7.11.1.1 Informações de cabeçalho

1.Informe o CNS do profissional e automaticamente o sistema apresentará opções para o CBO, CNES e INE oriundas da base de dados do CNES e que foram importado na instalação da aplicação. Lembre também de informar a data em que foi(ram) administrado(s) o(s) imunobiológico(s) no cidadão.

![](media/image738.png)

a.Caso o profissional tenha apenas um vínculo no município, os dados do cabeçalho serão preenchidos automaticamente, com exceção da data;

b.Caso o profissional tenha mais de um vínculo, o sistema mostrará as opções e o digitador escolherá o que está registrado na ficha de vacina.

c.Caso queira informar novo registro de vacinação realizado no mesmo dia e para o mesmo profissional, clique no botão ![](media image666.png){width="0.8576388888888888in" height="0.2218033683289589in"}. O sistema exibirá uma tela com cabeçalho preenchido (somente leitura) e os dados a serem completados para se efetivar o registro de vacinação.

### 7.11.1.2 Vacinações individualizadas

2.Após clicar no botão ![](media/image666.png) digite os dados conforme preenchido na ficha, iniciando pelo Turno da administração do imunobiológico, os dados de identificação do cidadão, o local de atendimento e o grupo, se for o caso:

a.Se o cidadão está na situação de "viajante"

b.A Situação de "Gestante" e "Puérpera" somente estará habilitado  quando for selecionado o sexo "Feminino".

c.O campo "Comunicante de hanseníase" somente estará habilitado  após a confirmação do registro da BCG.

![](media/image739.png)

> ![](media/image59.png) **ATENÇÃO:** Para habilitar o campo e registrar um comunicante de hanseníase, o digitador terá que preencher, no bloco "Vacinação", o campo imunobiológico com a vacina **BCG** e os demais campos obrigatórios. Em seguida deverá clicar no botão "confirmar".

### 7.11.1.3 Vacinação

No bloco "Vacinação" digite o Imunobiológico, a Estratégia, a Dose, o Lote e o Fabricante, conforme preenchido na ficha de vacinação. Em seguida clique no botão ![](media image740.png) para adicionar o registro do imunobiológico. Para cada imunobiológico repita essa mesma operação.

Figura 7.32 - Adicionar Vacinação
![](media/image741.png)
Fonte: SAS/MS.

Ao terminar de registrar todos imunobiológicos preenchidos na ficha de vacinação clique no botão ![](media/image672.png) e caso haja alguma inconsistência, o sistema mostrará mensagem na tela indicando os campos que deverão ser corrigidos. Por outro lado, caso não haja nenhuma inconsistência, o sistema salvará os dados, voltará para a tela de adicionar os registros de vacinação e apresentará a mensagem "registro confirmado com sucesso".

Figura 7.33 - Registro de Vacinação
![](media/image742.png)
Fonte: SAS/MS.

### 7.11.1.4. Lista de registro das vacinações individualizadas

O sistema traz, para cada ficha, a lista das vacinações individualizadas. Nesta Lista é possível visualizar ![](media/image743.png), editar ![](media/image744.png) ou excluir ![](media/image745.png) o registro dos imunobiológicos. A funcionalidade editar e excluir somente estarão disponíveis enquanto a lista não for salva.

Figura 7.34 - Adicionar Registro Individualizada
![](media/image746.png)
Fonte: SAS/MS.

Ao finalizar todo o processo de digitação das Fichas de vacina, clique no botão ![](media/image634.png).


CAPÍTULO 8 - Relatórios
=======================

![](media/image747.png)

O acompanhamento das ações de saúde que são realizadas no território é uma tarefa extremamente importante do cotidiano das equipes de Atenção Primária à Saúde. Esta atividade, além de auxiliar os trabalhadores a enxergar seu território, exprime o resultado do seu esforço, podendo ser potente ferramenta de reflexão e transformação do seu processo de trabalho.

O módulo "Relatórios" permite que trabalhadores e gestores possam visualizar, de forma sintetizada e sistematizada, as ações de saúde realizadas no território. São vários tipos de relatórios, divididos em consolidados, produção e operacionais, e são utilizados por diferentes tipos de atores.

Nesta versão os relatórios são exibidos na barra lateral de navegação, oferecendo um caminho mais simples e rápido para cada relatório (Figura 8.1). Clicando na opção "Relatórios" o sistema apresenta a lista com todos os disponíveis, dependendo do tipo de acesso que o profissional ou gestor tenha. Caso haja dúvida em relação ao relatório, é possível acionar um balão de ajuda representado pelo símbolo ![](media/image748.png) no canto superior direito de cada tela dos relatórios.

Figura 8.1 - Tela do Relatórios exibida com o perfil de profissional da equipe de AB
![](media/image749.png)
Fonte: SAPS/MS.

# 8.1 Administração dos relatórios

![](media/image750.png)

As opções de administração e configuração estão disponíveis APENAS para os perfis de administração da instalação. Para evitar o processamento desnecessário dos relatórios apenas o administrador da instalação, devidamente instruído, poderá utilizá- la.

## 8.1.1 Processamento

![](media/image751.png)

O processamento dos relatórios é um processo diário e incremental iniciado a meia- noite (0h) do próximo dia, a partir dos itens registrados ou enviados por meio do sistema. Este processo é ativado sempre que o usuário clica em Gerar/Transmitir os dados para envio ao SISAB, ver Seção 3.6.3.2.

Nesta funcionalidade, conforme podemos ver na Figura 8.2, é possível Marcar para reprocessamento ![](media/image752.png) ou forçar o processamento ![](media/image753.png) dos dados dos relatórios do sistema. A primeira funcionalidade permite que os dados dos relatórios, mesmo os dados que já foram processados, sejam reprocessados junto ao fluxo automático do sistema. A segunda funcionalidade força o processamento a ser executado de imediato.

> ![](media/image59.png) **ATENÇÃO**: a funcionalidade de "Forçar o processamento" pode ser um tanto dispendioso para a performance do PEC, a depender do tamanho da base de dados, podendo gerar lentidão para os outros usuários. Portanto, sempre que possível utilize a opção "Marcar para reprocessamento".

Figura 8.2 - Tela Processamento de Relatórios exibida somente com o perfil de administrador
![](media/image754.png)
Fonte: SAPS/MS.

## 8.1.2 Configuração da Impressão

![](media/image755.png)

Para evitar que consultas muito grandes criem uma carga exagerada no servidor da aplicação, por meio desta funcionalidade é possível configurar o fator que determinará quantos grupos de informações podem ser selecionados ao mesmo tempo, e ainda o período máximo, em meses, que poderá ser definido como intervalo para filtrar em cada relatório.  

Figura 8.3 - Tela de Configuração de Impressão exibida somente com o perfil de administrador
![](media/image756.png)
Fonte: SAPS/MS.

> ![](media/image84.png) **DICA**: o fator de carga no sistema, em relação à geração de um relatório, está relacionado com a capacidade de processamento do computador que está sendo utilizado, bem como com a quantidade de registros dentro do sistema/instalação. Caso a geração de relatórios prejudique o desempenho do sistema, opte por uma configuração com fatores menores.

Após finalizar a configuração clique em Salvar ![](media/image757.png) para ativar a nova configuração.

# 8.2 Nível de Agregação das Informações


O Sistema e-SUS APS, como sistema de gerenciamento de dados e informações da Atenção Básica, traz grande avanço no que diz respeito à segurança, sigilo e confidencialidade dos dados de saúde dos cidadãos. Isso quer dizer que apenas os profissionais que participam do atendimento ao cidadão têm acesso aos seus dados de saúde.

Atualmente, os relatórios do e-SUS APS disponibilizam informações agregadas, por meio dos relatórios consolidados e de produção, além dos relatórios operacionais, com informações individualizadas (Figura 8.1). A seguir uma breve explicação sobre os agrupamentos dos relatórios no sistema:

- **Relatórios consolidados**: são os relatórios que permitem uma visualização da situação cadastral consolidada, de acordo com a data selecionada, permitindo ao usuário ver a informação mais atual até aquele momento. Ver seção 8.3 para mais detalhes sobre os relatórios.

- **Relatórios de produção**: são os relatórios que permitem uma visualização agregada das informações, tais como: o atendimento individual, odontológico, domiciliar (SAD), atividade coletiva, procedimentos, entre outros, bem como relatórios de resumo de produção. Ver seção 8.4 para mais detalhes sobre os relatórios.

- **Relatórios operacionais:** são os relatórios que apresentam as informações individualizadas e identificadas da situação de saúde dos cidadãos do território. Estes relatórios são acessados apenas pelos trabalhadores das Unidades Básicas de Saúde, pois trazem dados relacionados ao cuidado individual do cidadão. Esta medida serve para proteger a individualidade e o direito à privacidade dos usuários do SUS, da mesma forma que é preservado o sigilo durante a relação trabalhador da saúde e usuário do serviço. Ver seção 8.5 para mais informações os relatórios disponíveis.

## 8.2.1 Perfis de acesso e Filtros disponíveis

Para a geração dos relatórios estão disponíveis diversos tipos de filtros de acordo com o tipo de perfil utilizado pelo usuário, obedecendo o seu papel na estrutura da saúde no município. Os relatórios consolidados e de produção possuem estrutura de filtros iguais como descrito a seguir.

O gestor municipal, seja ele o próprio secretário, coordenador da Atenção Básica ou outros profissionais que fazem parte da equipe de gestão, terá opções de visualização no âmbito de todo o município. Desta forma, é possível utilizar filtros para a totalização dos dados nos relatórios em relação ao "Período", "Unidade saúde", "Equipe", "Profissional" e "Categoria Profissional", como mostra a Figura 8.4.

Figura 8.4 - Tipos de filtro de gestor municipal
![](media/image758.png)
Fonte: SAPS/MS.

> ![](media/image58.png) **NOTA**: as opções "Profissional" e "Categoria profissional" [não podem] ser utilizadas em conjunto. É possível filtrar as informações do relatório por profissional **[ou]** por uma categoria profissional.

O perfil de coordenador da UBS terá acesso apenas a dados do serviço de saúde sob sua gestão. É possível utilizar filtros para a totalização dos dados nos relatórios de acordo com as vinculações de unidade de saúde e equipe de saúde registradas no CNES. Estão disponíveis os filtros "Período", "Equipe", "Profissional" e "Categoria Profissional", como mostra a Figura 8.5.

Figura 8.5 - Tipos de filtro de coordenador de UBS
![](media/image759.png)
Fonte: SAPS/MS.

Já os trabalhadores de saúde têm acesso aos relatórios, porém apenas aos dados produzidos por sua equipe. É possível utilizar, para a totalização dos dados nos relatórios, os filtros "Período", "Minha equipe" ou apenas "Minhas produções", como mostra a Figura 8.6.

Figura 8.6 - Tipos de filtro de trabalhador de saúde
![](media/image760.png)
Fonte: SAPS/MS.

Outra novidade para os filtros disponíveis é possibilidade de extrair relatórios analíticos ![](media/image761.png) e da série histórica ![](media image762.png) nos relatórios de produção. Já nos relatórios consolidados, além da série histórica é possível extrair o mensal ![](media image763.png) no relatório de situação do território, que será abordado mais adiante. A estrutura dos filtros segue o mesmo padrão dos descritos anteriormente, com a diferença que nos relatórios da série histórica, o período pode ser escolhido entre os últimos 3 meses, últimos 6 meses, últimos 12 meses ou simplesmente selecionar o período que deseja extrair os relatórios.

![](media/image764.png)

## 8.2.2 Grupo de Informações Disponíveis para Impressão

Os relatórios consolidados e de produção, tem um modelo padronizado para ativar ou desativar os grupos de informações a serem disponibilizados no impresso do relatório. Conforme vemos na Figura 8.7, usando como exemplo o relatório de Atividades Coletivas, podemos fazê- lo por meio da seleção do checkbox correspondente ao grupo de informações do relatório.

Figura 8.7 - Tipo de seleção dos grupos de informação
![](media/image765.png)
Fonte: SAPS/MS.

Para configurar o impresso do relatório realize os passos a seguir:

1.Abra a opção de seleção dos grupos de informação clicando no botão de dropdown ![](media/image766.png).

![](media/image767.png)

2.Marque ou desmarque o checkbox, conforme a necessidade. Caso o checkbox esteja marcado ![](media/image768.png), o grupo será mostrado no impresso, caso contrário ![](media/image769.png), o grupo não será mostrado.

Todos os grupos de informações vem ativados por padrão nos relatórios. Utilize as opções Selecionar Todos ![](media/image770.png) e Limpar ![](media image771.png), para marcar todos os grupos de informação ou desmarcar todos os grupos, respectivamente.

## 8.2.3 Filtros personalizados

As opções de filtros personalizados possibilitam ao usuário filtrar as informações do relatório. Para usar filtros personalizados realize os passos a seguir:

![](media/image772.png)

Passo 1. Em "Filtros personalizados" selecione na opção "Campo filtro" a informação que deseja obter e clique em adicionar ![](media/image773.png).

![](media/image774.png)

Passo 2. Ao selecionar um dos itens do "Campo filtro", serão apresentadas outras opções de filtro.

![](media/image775.png)

Passo 3. Selecione o(s) iten(s) desejado(s), clicando marcando cada checkbox do item que irá filtrar o relatório. No caso em destaque, selecione para "Destino do lixo" o item "Céu aberto" ![](media/image776.png), por exemplo, para filtrar os cadastros onde os domicílios tem lixo a céu aberto.

Passo 4. Para filtrar outros itens para compor um mesmo relatório, basta seguir os passos anteriores.

- Caso queira remover um filtro, basta excluir o item do campo "filtro personalizado", usando o botão "Excluir" ![](media/image777.png).

# 8.3 Relatórios Consolidados

Figura 8.8 - Tela do Relatórios consolidados exibida com o perfil de profissional da equipe de AB
![](media/image778.png)
Fonte: SAPS/MS.

Os relatórios consolidados trazem o estado atual do registro para um determinado conjunto de informações. Estes seguem o modelo padrão de estruturação dos relatórios, porém o usuário ao invés de selecionar um período, selecionará a data limite para consolidação dos dados.

Figura 8.9 - Tela do Relatório Consolidado de Cadastro Individual
![](media/image779.png)
Fonte: SAPS/MS.

## 8.3.1 Relatório consolidado de Cadastro domiciliar e territorial

Este relatório reflete o consolidado do estado atual do cadastro domiciliar e territorial, contém as informações registradas por meio das fichas de Cadastro domiciliar e territorial, bem como do Aplicativo do e-SUS APS Território, quando este estiver sendo utilizado.

Figura 8.10 - Tela do Relatório de cadastro domiciliar e territorial exibida com o perfil de profissional de saúde
![](media/image780.png)
Fonte: SAPS/MS.

Para gerar o relatório de cadastro domiciliar e territorial primeiro o usuário do sistema deve escolher a data limite para a consolidação dos dados no campo "Data" ![](media/image781.png).

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". as variáveis do grupo de informação são:

- Tipo de imóvel

- Condições de moradia

- Situação de moradia / Posse da terra

- Localização

- Tipo de domicílio

- Condição de posse e uso da terra

- Tipo de acesso ao domicílio

- Material predominante na construção das paredes externas

- Disponibilidade de energia elétrica

- Abastecimento de água

- Água para consumo no domicílio

- Forma de escoamento do banheiro ou sanitário

- Destino do lixo

- Animais no domicílio

- Famílias - Renda familiar

![](media/image782.png)

No filtro personalizado são apresentados as variáveis consolidadas que informam os dados sobre o abastecimento de água, água para consumo no domicílio, animais no domicílio, condição de posse e uso da terra, destino do lixo, disponibilidade de energia elétrica, forma de escoamento do banheiro ou sanitário, localização, material predominante na construção das paredes externas, microárea, qual animal no domicílio, recusa de cadastro, renda familiar (salário mínimo), situação de moradia, tipo de acesso ao domicílio, tipo de domicílio e tipo de imóvel.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

As variáveis apresentadas possibilitam a realização de uma análise inicial da situação de saúde do território de atuação das equipes de Atenção Básica, com a finalidade de construção de estratégia de enfrentamento das condicionalidades e dos determinantes sociais que afetam a qualidade da saúde da população assistida.

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do CDS sobre a Ficha de Cadastro Domiciliar e Territorial.

## 8.3.2 Relatório consolidado de Cadastro Individual

Este relatório reflete o consolidado do estado atual do cadastro individual, contém as informações registradas por meio da ficha de Cadastro Individual, bem como do Aplicativo do e-SUS APS Território, quando este estiver sendo utilizado.

Figura 8.11 - Tela do Relatório de cadastro individual exibida com o perfil de profissional da equipe de AB
![](media/image783.png)
Fonte: SAPS/MS.

Para gerar o relatório de cadastro individual primeiro o usuário do sistema deve escolher a data limite para a consolidação dos dados no campo "Data" ![](media image781.png).

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são :

- Dados gerais

- Identificação do usuário / cidadão

- Faixa etária

- Sexo

- Raça / Cor

- Etnia

- Nacionalidade

- Informações sociodemográficas

- Relação de parentesco com o responsável familiar

- Ocupação

- Qual é o curso mais elevado que frequenta ou frequentou

- Situação no mercado de trabalho

- Crianças de 0 a 9 anos, com quem fica

- Orientação sexual

- Identidade de gênero

- Deficiência

- Outras informações sociodemográficas

- Tipo de saída do cidadão do cadastro

- Condições / Situações de saúde gerais

- Sobre seu peso, você se considera

- Doença respiratória

- Doença cardíaca

- Problemas nos rins

- Cidadão em situação de rua

- Tempo em situação de rua

- Quantas vezes se alimenta ao dia

- Qual a origem da alimentação

- Tem acesso à higiene pessoal

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre o cidadão que estão presentes na ficha de cadastro individual.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

As variáveis apresentadas podem complementar a análise da situação de saúde do território de atuação das equipes de Atenção Básica, com a finalidade de construção de estratégia de enfrentamento das condicionalidades e dos determinantes de saúde que afetam a qualidade de vida da população assistida. A variável "Dados Gerais" apresentará a quantidade de "cidadãos ativos" e "saída de cidadão do cadastro". O primeiro refere- se ao cidadãos que permanecem vinculados ao território e o segundo aos cidadãos que foram cadastrados, mas que não estão mais vinculados ao território.

![](media/image784.png)

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do CDS sobre a Ficha de Cadastro Individual.

## 8.3.3 Relatório da Situação do Território

O relatório consolidado da situação do território apresenta informações gerais sobre a área de atuação das equipes de saúde, reunindo dados sobre o cadastro do cidadão, condições gerais do domicílio, situação sociodemográfica e pessoas em situação de rua, sendo um conjunto de informação necessária para o planejamento das ações de saúde do território.

Neste relatório é possível avaliar a situação do território para uma competência específica ou avaliar a evolução dos dados do território para um período escolhido. Para isso, escolha entre os tipos de relatório ![](media/image785.png) ou de ![](media/image786.png), conforme as figuras a seguir, respectivamente:

![](media/image787.png)

![](media/image788.png)

# 8.4 Relatórios de Produção

Os relatórios de produção trazem os dados (eventos) agregados em um determinado período, orientados pelo bloco de informação dentro do sistema. Os blocos de informações são organizados de forma similar ao formato de envio dos registros ao SISAB. Atualmente os blocos disponíveis são:

- Atendimento domiciliar

- Atendimento individual

- Atendimento odontológico individual

- Atividade coletiva

- Avaliação de elegibilidade e admissão

- Marcadores de consumo alimentar

- Procedimentos

- Procedimentos consolidados

- Resumo de produção

- Síndrome neurológica por Zika / Microcefalia

- Visita domiciliar e territorial

- Vacinação

Figura 8.12 - Tela de Relatório de produção exibida com o perfil de profissional da equipe de AB
![](media/image789.png)
Fonte: SAPS/MS.

Os relatórios de produção apresentam novidades para os filtros disponíveis, sendo possível extrair relatórios analíticos ![](media/image761.png) e da série histórica ![](media/image762.png).

Nas seções seguintes são detalhados cada bloco de informação.

## 8.4.1 Atendimento domiciliar

Este relatório contabiliza os dados referentes aos atendimentos domiciliares dentro do período determinado, tendo como fonte de informação as Fichas de Atendimento Domiciliar ou do Aplicativo e-SUS AD, que são de uso exclusivo do Serviço de Atenção Domiciliar (SAD).

Figura 8.13 - Tela do Relatório de atendimento domiciliar exibida com o perfil de profissional da equipe de AB
![](media/image790.png)
Fonte: SAPS/MS.

Para gerar o relatório de atendimento domiciliar primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são :

- Resumo de produção

- Turno

- Sexo

- Faixa etária

- Local de atendimento

- Modalidade AD

- Tipo de atendimento

- Condições avaliadas

- Condições avaliadas (CID10)

- Condições avaliadas (CIAP2)

- Conduta / Desfecho

- Procedimentos

- Outros procedimentos (SIGTAP)

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre o atendimento domiciliar e que estão presentes na ficha de atendimento domiciliar.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png){width="0.3906255468066492in" height="0.33203083989501314in"} NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Atendimento Domiciliar**.

## 8.4.2 Atendimento individual

Este relatório contabiliza os dados referentes aos atendimentos individuais dentro do período determinado, tendo como fonte de informação às Ficha de atendimento individual e os Atendimentos realizados no PEC.

Figura 8.14 - Tela do Relatório de cadastro individual exibida com o perfil de profissional da equipe de AB
![](media/image792.png)
Fonte: SAPS/MS.

Para gerar o relatório de atendimento individual primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são:

- Resumo de produção

- Dados gerais

- Turno

- Sexo

- Faixa etária

- Local de atendimento

- Tipo de atendimento

- Atenção domiciliar

- Racionalidade em saúde

- Criança - Aleitamento materno

- NASF / Polo

- Conduta / Desfecho

- Encaminhamento

- Problemas / Condições avaliadas

- Problemas / Condições avaliadas - Doenças transmissíveis

- Problemas / Condições avaliadas - Rastreamento

- Problemas / Condições avaliadas - Outros CIAP2

- Problemas / Condições avaliadas - Outros CID10

- Exames solicitados e avaliados

- Exames - Triagem neonatal

- Outros exames solicitados e avaliados (código do SIGTAP)

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre o atendimento e que estão presentes na ficha de atendimento individual.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Atendimento Individual**.

## 8.4.3 Atendimento odontológico individual

Este relatório contabiliza os dados referentes aos atendimentos odontológicos individuais dentro do período determinado, tendo como fonte de informação as Fichas de atendimento odontológico individual e os Atendimentos odontológicos realizados no PEC.

Figura 8.15 - Tela do Relatório de cadastro individual exibida com o perfil de profissional da equipe de AB
![](media/image793.png)
Fonte: SAPS/MS.

Para gerar o relatório de atendimento odontológico primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são:

- Resumo de produção

- Dados gerais

- Turno

- Sexo

- Faixa etária

- Local de atendimento

- Tipo de atendimento

- Tipo de consulta

- Vigilância em saúde bucal

- Procedimentos

- Outros procedimentos (SIGTAP)

- Fornecimento

- Conduta / Desfecho

- Encaminhamento

- Problema/ Condições avaliadas

- Condições avaliadas (CID10)

- Condições avaliadas (CIAP2)

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre o atendimento e que estão presentes na ficha de atendimento odontológico.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Atendimento Individual Odontológico**.

## 8.4.4 Atividade coletiva

Este relatório contabiliza os dados referentes às atividades coletivas dentro do período determinado, tendo como fonte de informação os registros das Fichas de atividade coletiva.

Figura 8.16 - Tela do Relatório de atividade coletiva exibida com o perfil de profissional da equipe de AB
![](media/image794.png)
Fonte: SAPS/MS.

Para gerar o relatório de atividades coletivas primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são:

- Resumo de produção

- Número de participantes

- Turno

- Programa Saúde na Escola

- Atividade

- Público alvo

- Temas para saúde

- Práticas em saúde

- Outros procedimentos coletivos

- Temas para reunião

O número de participantes nas atividades coletivas está disponível neste relatório. Os Participantes identificados, correspondem aos participantes que tiveram seu número de CNS registrado, já o Total de participantes corresponde ao número de participante informados. Ainda é possível utilizar os filtros personalizados para refinar o relatório.

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre a atividade e que estão presentes na ficha de atividade coletiva.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Atividade Coletiva**.

## 8.4.5 Avaliação de elegibilidade e admissão

Este relatório contabiliza os dados referentes às avaliações de elegibilidade e admissão dentro do período determinado, tendo como fonte de informação as Fichas de avaliação de elegibilidade e admissão, bem como os registros de avaliação de elegibilidade do Aplicativo e-SUS AD. Estes instrumentos são de uso exclusivo do SAD.

Figura 8.17 - Tela do Relatório de atividade coletiva exibida com o perfil de profissional da equipe de AB
![](media/image795.png)
Fonte: SAPS/MS.

Para gerar o relatório de avaliação de elegibilidade e admissão primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são:

- Resumo de produção

- Turno

- Dados gerais

- Etnia

- Sexo

- Raça / Cor

- Nacionalidade

- Faixa etária

- Procedência

- Condições avaliadas

- CID- 10

- Conclusão / Destino

- Destino elegibilidade

- Motivo inelegibilidade

- Cuidador

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre esta avaliação e que estão contidas na ficha de avaliação de exigibilidade e admissão.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Avaliação de Elegibilidade e Admissão** do SAD.

## 8.4.6 Marcadores de consumo alimentar

Este relatório contabiliza os dados referentes aos marcadores de consumo alimentar dentro do período determinado, tendo como fonte as fichas de Marcadores de consumo alimentar.

Figura 8.18 - Tela do Relatório de marcadores de consumo alimentar exibida com o perfil de profissional da equipe de AB
![](media/image796.png)
Fonte: SAPS/MS.

Para gerar o relatório de marcadores de consumo alimentar primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são:

- Resumo de produção

- Faixa etária

- Sexo

- Local de atendimento

- Crianças menores de 6 meses

- Crianças de 6 a 23 meses

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre estes marcadores e que estão contidas na ficha de marcadores de consumo alimentar.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a ficha **Marcadores de Consumo Alimentar**.

## 8.4.7 Procedimentos

Este relatório contabiliza os dados referentes aos procedimentos dentro do período determinado, tendo como fonte as Fichas de procedimentos ou os registros de procedimentos no PEC.

Figura 8.19 - Tela de Relatório de procedimentos exibida com o perfil de profissional da equipe de AB
![](media/image797.png)
Fonte: SAPS/MS.

Para gerar o relatório procedimentos primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são:

Os grupos de informações disponíveis para impressão e as opções de campos para filtros personalizados são:

- Resumo de produção

- Turno

- Faixa etária

- Sexo

- Local de atendimento

- Dados gerais

- Procedimentos / Pequenas cirurgias

- Teste rápido

- Administração de medicamentos

- Outros procedimentos (SIGTAP)

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre os procedimentos e que estão contidas na ficha de procedimentos.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Procedimentos**.

## 8.4.8 Procedimentos consolidados

Este relatório contabiliza os dados referentes aos procedimentos consolidados dentro do período determinado, tendo como fonte as Fichas de procedimentos e os registros de procedimentos no PEC.

Figura 8.20 - Tela de Relatório de procedimentos consolidados exibida com o perfil de profissional da equipe de AB
![](media/image798.png)
Fonte: SAPS/MS.

Para gerar o relatório procedimentos consolidados primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados".

O filtro personalizado apresenta todas as variáveis que aparecem no relatório de procedimentos consolidados e que podem ser gerados de forma isoladas, tais como os totais de aferição de PA, temperatura, coleta de material para exame laboratorial, curativo simples, glicemia capilar, medição de altura e medição de peso.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Procedimento**, especialmente sobre o bloco de procedimentos consolidados.

## 8.4.9 Resumo de produção

Este relatório contabiliza a produção de todos os registros realizados por tipo de ficha.

Figura 8.21 - Tela de Resumo de produção exibida com perfil de profissional da equipe de AB
![](media/image799.png)
Fonte: SAPS/MS.

Para gerar o relatório de resumo de produção primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Após a escolha do período basta clicar em "Exportar CSV" ou "Imprimir" para gerar o relatório de resumo de produção.

Figura 8.22 - Exemplo do Relatório de Resumo de Produção
![](media/image800.png)
Fonte: SAPS/MS.

Os registros nas fichas onde é informado o CNS do cidadão são apresentados como \"Identificados\", já os registros sem CNS são os \"Não identificados\". Ou seja, por meio desse relatório pode- se monitorar o percentual de ações que ficam vinculadas ao prontuário do cidadão e aquelas que terão apenas finalidade estatística. Idealmente se espera que o máximo de registro sejam identificados.

Ainda é possível identificar a quantidade de novos cadastros, atualização dos cadastrados e recusa de cadastro.

## 8.4.10 Síndrome neurológica por Zika / Microcefalia

Este relatório contabiliza os dados referentes aos atendimentos de síndrome neurológica por Zika / Microcefalia dentro de um período determinado , tendo como fonte de informação os registros da Ficha complementar de Síndrome neurológica por Zika / Microcefalia, bem como os atendimentos no PEC.

Figura 8.23 - Tela do Relatório da ficha complementar - Síndrome neurológica por Zika/Microcefalia exibida com perfil de profissional da equipe de AB.
![](media/image801.png)
Fonte: SAPS/MS.

Para gerar o relatório da ficha complementar primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são:

- Resumo de produção

- Turno

- Resultado de Teste do olhinho (Reflexo vermelho)

- Resultado de Exame de fundo de olho (02.11.06.010- 0 - Fundoscopia)

- Resultado de Teste da orelhinha - PEATE (02.11.07.027- 0 - Potencial evocado auditivo para a triagem auditiva)

- Resultado de US transfontanela (02.05.02.017- 8 - Ultrassonografia transfontanela)

- Resultado de Tomografia computadorizada (02.06.01.007- 9 - Tomografia computadorizada do crânio)

- Resultado de Ressonância magnética (02.07.01.006- 4 - Ressonância magnética de crânio)

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha complementar** de Síndrome neurológica por Zika / Microcefalia.

## 8.4.11 Visita domiciliar e territorial

Este relatório contabiliza os dados referentes às visitas domiciliares dentro do período determinado, tendo como fonte de informação as Fichas de visita domiciliar e territorial ou o Aplicativo e-SUS APS Território.

Figura 8.24 - Tela do Relatório de visita domiciliar e territorial exibida com perfil de profissional da equipe de AB
![](media/image802.png)
Fonte: SAPS/MS.

Para gerar o relatório de visita domiciliar e territorial primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são:

- Resumo de produção

- Turno

- Tipo de imóvel

- Faixa etária

- Sexo

- Visitas compartilhadas

- Motivo de visita

- Geral

- Busca ativa

- Acompanhamento

- Controle ambiental / vetorial

- Desfecho

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre a visita dos agentes aos cidadãos do território de abrangência da equipe de AB e que estão contidas na ficha de visita domiciliar e territorial.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Visita Domiciliar e Territorial**.

## 8.4.12 Vacinação

Este relatório contabiliza os dados referentes a administração dos imunobiológicos dentro de um período determinado, tendo como fonte de informação as Fichas de vacinação ou por meio do registro no PEC.

Figura 8.25 - Tela do Relatório de vacinação exibida com perfil de profissional da equipe de AB
![](media/image803.png)
Fonte: SAPS/MS.

Para gerar o relatório de vacinação primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são:

- Resumo de produção

- Turno

- Sexo

- Faixa etária

- Local de Atendimento

- Dados gerais

- Imunobiológico

- Estratégia

- Dose

- Lote

- Fabricante

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre o registro de vacinação e que estão contidas na ficha de vacinação.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

> ![](media/image58.png) NOTA: Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Vacinação**.

### 8.4.12.1 Orientação para extração de relatórios de doses aplicadas para auxílio no cálculo de cobertura vacinal.

O relatório de vacinação apresenta informações agregadas dos registros de doses aplicadas por imunobiológicos.

Para a geração dos relatórios estão disponíveis diversos tipos de filtros de acordo com o tipo de perfil utilizado pelo usuário do sistema e-SUS APS.

Para a impressão com o perfil de gestor municipal (secretário de saúde, coordenador da Atenção Básica ou outros profissionais que fazem parte da equipe de gestão) existe a opção de visualização dos dados em todo o município. Desta forma, é possível utilizar filtros para a totalização dos dados nos relatórios em relação ao "Período", "Unidade saúde", "Equipe", "Profissional" e "Categoria Profissional", como mostra a Figura 1.

Figura 1 - Tipos de filtro de gestor municipal
![](media/image758.png)

> ![](media/image58.png) **NOTA**: as opções "Profissional" e "Categoria profissional" [não podem] ser utilizadas em conjunto. É possível filtrar as informações do relatório por profissional **[ou]** por uma categoria profissional.

Para visualizar os dados referentes ao quantitativo de dose aplicadas referentes a um imunobiológico em um determinado período e local, siga os passos a seguir:

1.Escolha o "Período" e a "Unidade de saúde";

2.Utilize o campo "Filtros personalizados";

3.No "Campo filtro" selecione as variáveis que pretende usar para compor o relatório.

![](media/image804.png)

**Por exemplo:** Quantas doses de BCG foram aplicadas em crianças menores de 01 ano. Para isso basta selecionar as variáveis "imunobiológico", "Dose" e "Faixa etária" e incluir "BCG", "Dose" + "Revacinação" e "menos de 01 ano", respectivamente.

Figura 5. Filtros personalizados
![](media/image805.png)

4\. Se quiser extrair o relatório somente com as informações escolhidas nas variáveis, selecione as mesmas, no campo "Grupos de informações disponíveis para a impressão" (Figura 6).

Figura 6. Grupo de informação disponíveis para impressão
![](media/image806.png)

5\. Após a seleção das variáveis é possível extrair o relatório no formato .CSV ou simplesmente imprimi- lo.

6\. Pronto o relatório é apresentado conforme a figura abaixo.

![](media/image807.png)

# 8.5 Relatórios Operacionais

Os relatórios operacionais foram criados para auxiliar os trabalhadores das equipes de Atenção Básica no acompanhamento da situação de saúde dos usuários adscritos no território[^3]. Estes relatórios são acessados apenas pelos perfis de trabalhadores de saúde das equipes e coordenadores de UBS, tendo em vista as questões de segurança, privacidade e sigilo já tratadas no início deste capítulo.

Os quatro relatórios operacionais auxiliam a equipe a monitorar e acompanhar a situação de saúde dos cidadãos. Neste momento, cada um traz informações detalhadas dos indivíduos de acordo com a condição apresentada nos registros de saúde do e-SUS APS, seja por meio da Coleta de Dados Simplificada, seja por meio do Prontuário Eletrônico do Cidadão.

Nesta versão, estão disponíveis quatro tipos de relatórios operacionais, como mostra a Figura 8.26, abaixo:

Figura 8.26 - Tipos de relatório operacional
![](media/image808.png)
Fonte: SAPS/MS.

Cada relatório trata de linhas de cuidados diferentes, além do relatório de cadastro territorial. Falaremos sobre cada um com mais profundidade mais adiante.

Para a geração dos relatórios, os profissionais podem utilizar alguns filtros que ajudam a organizar a forma como as informações serão mostradas. Da mesma forma que os relatórios consolidados, os relatórios operacionais possuem filtros que dependem do tipo de perfil utilizado.

Há uma diferença entre os filtros utilizados no relatório de cadastro e nos relatórios por linha de cuidado. Por padrão, os Coordenadores de UBS tem acesso a estes relatórios por equipe caso haja mais de uma equipe vinculada à UBS. Os profissionais acessam apenas os dados em relatório operacional apenas daqueles cidadãos adscritos a sua equipe.

## 8.5.1 Relatório operacional de cadastro territorial

O Relatório Operacional de Cadastro Territorial traz informações essenciais sobre os cidadãos cadastrados no território por meio das fichas de Cadastro Individual e Cadastro Domiciliar da Coleta de Dados Simplificada (CDS). Nele, é possível visualizar os agrupamentos de indivíduos que compõem uma família, com seu responsável em destaque, os agrupamentos das famílias nos domicílios e os domicílios, de acordo com a microárea a que pertencem.

Para estes relatórios, é possível optar tanto pelo relatório "Cadastro territorial" ![](media/image809.png), onde são apresentados a composição dos núcleos familiares organizados por microárea e logradouro (Figura 8.27), quanto pelo relatório "Inconsistências" ![](media/image810.png) do cadastro territorial (Figura 8.29).

Para listar apenas o cadastro é necessário selecionar um INE (caso seja um Coordenador de UBS) e uma microárea[^4]. Caso estes campos fiquem em branco, será gerado um relatório com todos os cadastros relacionados a esta UBS. Caso seja selecionada a opção de inconsistências, serão habilitadas as situações de inconsistência, sendo obrigatória a seleção de pelo menos um item.

Figura 8.27 - Filtro do relatório operacional de cadastro
![](media/image811.png)
Fonte: SAPS/MS.

Ao selecionar o relatório de Cadastro Territorial, uma lista com informações sobre o território como microárea, endereço, dados de identificação e contato dos cidadãos serão exibidos, como mostra o exemplo da Figura 8.28.

Figura 8.28 - Exemplo de Relatório de Cadastro - Cadastro Territorial
![](media/image812.png)
Fonte: SAPS/MS.

O relatório de inconsistências permite a visualização do tipo de incoerência em relação ao cidadão, seu núcleo familiar, vínculo com responsável familiar e domicílio. Com estas informações, é possível realizar as adequações para manter a consistência do cadastro do território, permitindo maior fidedignidade nas informações em relação aos indivíduos, assim como, as famílias adscritas no território da equipe.

Ao selecionar a opção "inconsistências do cadastro territorial", oito inconsistências possíveis ficarão disponíveis, conforme é possível visualizar na figura 8.29, sendo relacionadas ao domicílio, a família e aos cidadãos individualmente.

Figura 8.29 - Tela do Relatório de Cadastro - Inconsistências
![](media/image813.png)
Fonte: SAPS/MS.

A impressão deste relatório apresentará dois blocos distintos por INE e microárea: cidadãos com dados inconsistentes e domicílios com dados inconsistentes. Cada bloco apresenta os dados de identificação do cidadão ou do domicílio inconsistente, acrescido da identificação do tipo de inconsistência, como mostra o exemplo na Figura 8.30.

Figura 8.30 - Exemplo de Relatório de Inconsistência do Cadastro Territorial
![](media/image814.png)
Fonte: SAPS/MS.

### 8.5.1.1 Critérios de Inclusão e Exclusão do relatório de Cadastro Territorial

Ao observar o relatório de Cadastro Territorial deve- se estar atento aos critérios de inclusão e exclusão dos registros exibidos no relatório, tal como segue:

- Inclusão:

- As fichas de cadastro domiciliar e cadastro individual devem pertencer ao mesmo CNES da lotação do profissional;

- As famílias devem estar cadastradas de acordo com as regras de composição do núcleo familiar, identificadas a partir do CNS do Responsável Familiar.

- As informações das fichas de cadastro com a data mais atual são exibidas da seguinte forma:

 - Caso sejam ​dados gerais​, considerar a informação mais atual, independente da equipe que a registrou;

 - Caso sejam dados não globais​, considerar a informação mais atual, da equipe que a registrou.

- Considerar somente as fichas de cadastro domiciliar que possuem \"Tipo de imóvel\" igual a \"01 - Domicílio\";

- Exclusão:

- Não deve ter sido informado na ficha de cadastro individual os campos \"mudança de território\" ou \"óbito\";

- Famílias não devem estar cadastradas de acordo com Regras de inativação do núcleo familiar;

- Cidadãos não devem estar cadastrados com inconsistências

### 8.5.1.2 Critérios de Inclusão do relatório de Inconsistência

Ao observar o relatório de Inconsistências deve- se estar atento aos critérios de inclusão no relatório, tanto em relação ao cadastro individual do cidadão, quanto para o núcleo familiar ao qual ele
pertence, tal como segue:

- **Relacionado ao Núcleo Familiar:**

**Inconsistência identificada: Família excluída durante a  atualização do cadastro (1)**. Esta inconsistência é observada  quando a atualização do cadastro domiciliar não possuir mais o  registro da família cadastrada na última visita.

*Como resolver?* Para remover a inconsistência deve- se registrar o CNS do Responsável Familiar em um Cadastro Domiciliar, vinculando a família a um domicílio.

**Inconsistência identificada: Responsável sem cadastro individual (2)**. Esta inconsistência é observada quando não existe uma ficha de cadastro individual para o responsável familiar, com CNS, indicado na ficha de cadastro domiciliar.

*Como resolver?* Para remover a inconsistência deve- se cadastrar o Responsável Familiar informando o CNS na ficha de cadastro individual.

**Inconsistência identificada: Responsável não declarado no cadastro individual (3)**. Esta inconsistência é identificada quando no cadastro individual do responsável familiar, o campo \"Responsável familiar\" é marcado como \"Não\" ou está em branco.

 *Como resolver?* Para remover a inconsistência, a ficha de cadastro individual do responsável deve ser atualizada, registrando \"Sim\" no campo de \"Responsável familiar\".

**Inconsistência identificada: Responsável em outro domicílio mais atual (4)**. Esta inconsistência é observada quando o responsável familiar está sendo cadastrado em outro domicílio.

*Como resolver?* Para remover a inconsistência será necessário atualizar o domicílio anterior, marcando a opção \"Mudou- se\" no grupo \"Famílias\", onde o CNS do Responsável Familiar está referido.

- **Relacionado ao Cidadão:**

**Inconsistência identificada: Responsável com mudança de território (5).** Esta inconsistência é observada quando o cadastro individual do cidadão possui o campo \"CNS do responsável familiar\" com CNS de um responsável com mudança de território.

*Como resolver?* Para que a inconsistência não ocorra, é necessário informar o \"CNS do responsável familiar\" cujo cadastro individual não possua a informação da mudança de território.

**Inconsistência identificada: Responsável com óbito no cadastro individual (6).** Esta inconsistência é observada quando o cadastro individual do cidadão possui o campo \"CNS do responsável familiar\" com CNS de um responsável com óbito.

*Como resolver?* Para que a inconsistência não ocorra, é necessário informar o \"CNS do responsável familiar\" cujo cadastro individual não possua a informação do óbito.

**Inconsistência identificada: Responsável não informado (7).** Esta inconsistência é identificada quando o cadastro individual do cidadão não possui seu responsável familiar informado, ou seja, o campo \"CNS do responsável familiar\" está vazio e o campo \"Cidadão é o responsável familiar?\" foi respondido como \"Não\" ou encontra- se em branco.

 *Como resolver?* Para que a inconsistência não ocorra, é necessário manter o campo \"Cidadão é o responsável familiar?\" como \"Não\" e informar um CNS do responsável familiar que possua cadastro individual no mesmo território.

**Inconsistência identificada: Sem vínculo com domicílio (8):** Esta inconsistência é observada quando o cidadão não está vinculado a um domicílio cadastrado. Nesse caso existem as seguintes inconsistências adicionais.

**Cidadão com responsável sem cadastro individual:** O cadastro do cidadão está com o campo \"Cidadão é o responsável familiar?\" marcado como \"Não\" e o CNS indicado no campo \"CNS do responsável familiar\" não possui cadastro individual.

*Como resolver?* Para que a inconsistência não ocorra, é necessário manter o campo \"Cidadão é o responsável familiar?\" como \"Não\" e informar um CNS do responsável familiar que possua cadastro individual no mesmo território.

**Responsável sem domicílio:** O cadastro do cidadão está com o campo \"Cidadão é o responsável familiar?\" marcado como \"Sim\", declarando- o como responsável. Porém, não há domicílio cadastrado com seu respectivo CNS.

*Como resolver?* Para que a inconsistência não ocorra, é necessário cadastrar um domicílio informando o mesmo CNS do cidadão (campo \"CNS do cidadão\" no cadastro individual) no grupo \"Famílias\" do respectivo domicílio.

**Cadastro individual com responsável declarado sem domicílio:** O cadastro do cidadão está com o campo \"Cidadão é o responsável familiar?\" marcado como \"Não\" e não há domicílio cadastrado com o CNS do responsável familiar.

*Como resolver?* Para que a inconsistência não ocorra, é necessário cadastrar um domicílio informando o mesmo CNS do responsável (campo \"CNS do responsável familiar\" no cadastro individual) no grupo \"Famílias\" do respectivo domicílio.

**Cadastro individual sem CNS e declarado como responsável:** O cadastro do cidadão está com o campo \"Cidadão é o responsável familiar?\" marcado como \"Sim\", declarando- o como responsável. Porém, o campo \"CNS do cidadão\" está vazio.

*Como resolver?* Para que a inconsistência não ocorra, é necessário informar um CNS válido no campo \"CNS do cidadão\".

## 8.5.2 Relatório operacional de gestantes e puérperas

O Relatório Operacional de Gestantes/Puérperas permite o acompanhamento das mulheres que estão nesta condição. Comporão esta lista, aquelas que tiveram algum registro de condição de saúde relacionado à gestação nos instrumentos de captação de dados clínicos (PEC ou CDS), de acordo com a quantidade e qualidade do preenchimento destes instrumentos.

Para o relatório de gestantes/puérperas, são utilizados filtros diferentes do relatório de cadastro. Para o coordenador da UBS, serão disponibilizadas as opções de filtragem por "INE/Equipe" e "Microárea". Caso deseje listar todas as microáreas do seu território basta deixar este campo em branco (Figura 8.31).

Figura 8.31 - Filtro do relatório operacional de gestantes/puérperas - coordenador da UBS
![](media/image815.png)
Fonte: SAPS/MS.

> ![](media/image58.png) NOTA: os profissionais de saúde, sem perfil de coordenação, irão observar que o filtro INE estará desabilitado, mas poderão utilizar o filtro "Microárea" para selecionar uma microárea específica.

Prioritariamente, as **gestantes cadastradas** no território da equipe comporão este relatório, devendo estar **vinculadas a um responsável familiar**, *e este*, **vinculado a um domicílio do território**. Contudo, é possível verificar se há alguma gestante sendo acompanhada, mas que está fora da área de cobertura da equipe. O relatório oferece à equipe dados relacionados à DUM, DPP, IG, informações relacionadas à última consulta pré- natal (data da última consulta e situação vacinal), status do VDRL, além da data de outras consultas e visita domiciliar realizada pelo ACS, como observado na imagem a seguir.

Figura 8.32 - Exemplo de Relatório Operacional de Gestante/Puérpera
![](media/image816.png)
Fonte: SAPS/MS.

## 8.5.3 Relatório operacional de crianças menores de 5 anos

O Relatório Operacional de Crianças Menores de 5 Anos oferta aos profissionais de saúde informações importantes para o acompanhamento das crianças residentes no território de abrangência da UBS. Tais informações são coletadas por meio do registro de ações de saúde, tanto do Prontuário Eletrônico do Cidadão quanto da Coleta de Dados Simplificada.

Para o relatório de crianças menores de 5 anos são utilizados filtros diferentes dos outros relatórios. Para o coordenador da UBS, serão disponibilizadas as opções de filtragem por "INE", "Microárea" e por CID10. Para selecionar todas as microáreas este campo deve ficar em branco. O filtro baseado no CID10 pode auxiliar o acompanhamento de crianças em situações específicas, como as identificadas com a Síndrome Neurológica por Zika/Microcefalia, ou outras situações que podem ser identificadas por meio da CID10 (Figura 8.33).

Figura 8.33 - Tela do Relatório de crianças menores de 5 anos - perfil de coordenador da UBS
![](media/image817.png)
Fonte: SAPS/MS.

> ![](media/image58.png) NOTA: os profissionais de saúde, sem perfil de coordenação, irão observar que o filtro INE estará desabilitado, mas poderão utilizar o filtro "Microárea" para selecionar uma microárea específica, bem como um CID10.

Prioritariamente, as **crianças menores de 5 anos cadastradas no território** da equipe comporão este relatório, devendo estar **vinculadas a um responsável familiar**, *e este*, **vinculado a um domicílio no território**. Entretanto, é possível verificar se há alguma criança sendo acompanhada, mas que está fora da área de cobertura da equipe. O relatório oferece à equipe dados relacionados a realização da consulta na primeira semana de vida, se foram avaliados os testes da triagem neonatal (pezinho, orelhinha e olhinho), última consulta odontológica, última visita do ACS e os registros da última consulta de puericultura (tipo de aleitamento, status de imunização, últimas medições de perímetro cefálico, peso, altura e estado nutricional), como mostra a imagem a seguir.

Figura 8.34 - Exemplo de Relatório Operacional de Crianças menores que 5 anos
![](media/image818.png)
Fonte: SAPS/MS.

## 8.5.4 Relatório operacional de risco cardiovascular

O Relatório Operacional de Risco Cardiovascular mostra à equipe informações sobre a situação de saúde dos usuários que, de alguma forma, se enquadram num estado que apresente risco ao desenvolvimento de doenças cardiovasculares. A presença de usuários neste relatório, depende de alguns fatores de risco coletados nos instrumentos de registro do e-SUS APS, seja no Prontuário Eletrônico do Cidadão, seja na Coleta de Dados Simplificada.

Neste relatório são utilizados os seguintes filtros: o coordenador da UBS terá a sua disposição as opções de filtragem por "INE/Equipe" e "Microárea" . Caso deseje listar todas as microáreas do seu território basta deixar este campo em branco (Figura 8.35).

Figura 8.35 - Tela do Relatório de Risco Cardiovascular - perfil de coordenador da UBS
![](media/image819.png)
Fonte: SAPS/MS.

> ![](media/image58.png) NOTA: os profissionais de saúde, sem perfil de coordenação, irão observar que o filtro INE estará desabilitado, mas poderão utilizar o filtro "Microárea" para selecionar uma microárea específica.

Os **cidadãos em risco cardiovascular**, **cadastrados no território** da equipe, comporão este relatório devendo estar **vinculados a um responsável familiar**, *e este*, **vinculado a um domicílio no território**. Todavia, é possível verificar se há algum cidadão sendo acompanhado, mas que está fora da área de cobertura da equipe. O relatório oferece à equipe, dados relacionados a presença de diagnóstico ou informação auto referida de hipertensão arterial sistêmica, diabetes, tabagismo, último IMC, data do atendimento em que foi realizada a consulta para rastreamento de risco cardiovascular e a data da última consulta para condições que ampliam o risco cardiovascular, além da consulta odontológica e da última visita domiciliar realizada pelo ACS.
Os critérios de inclusão do cidadão neste relatório são:

- Resposta afirmativa no questionário autorreferido de condições da Ficha de Cadastro Individual para os itens \"Tem hipertensão arterial?\"; \"Tem diabetes?\"; \"Teve AVC/derrame?\"; \"Teve infarto?\"; \"Tem doença cardíaca/do coração?\"; \"Tem ou teve problemas nos rins?\"; \"Está fumante?\".

- CID e/ou CIAP informado(s) no atendimento PEC ou na Ficha de Atendimento Individual de acordo com o Quadro 8.1 abaixo;

- Opções \"Hipertensão arterial\"; \"Diabetes\"; \"Obesidade\"; \"Tabagismo\" marcada na Ficha de Atendimento Individual;

Figura 8.36 - Exemplo de Relatório Operacional de risco cardiovascular
![](media/image820.png)
Fonte: SAPS/MS.

Quadro 8.1 - Códigos CIAP2 e CID10 para o Relatório de Risco Cardiovascular

|Condição|CIAP2|CID10|
|- |- |- |
|Hipertensão Arterial (HAS)|K86, K87|I10, P292, K766, I270, I272, que contenha o código I13, que contenha o código I15|
|Diabetes (DIA)|T90, T89|que contenha o código E10, que contenha o código E11, que contenha o código E12, que contenha o código E13, que contenha o código E14, que contenha o código O24, E232, N083, N251, P700, P702|
|Tabagismo|P17|Z720
|Obesidade|T82|que contenha o código E66|
|AVC|K89, K90, K91|G45, G46, I60, que contenha o código I61, I62, que contenha o código I63, I64, I65, I66, que contenha o código I67 (exceto I674), I68, I69|
|Infarto|K75, K78|que contenha o código I21, que contenha o código I22, que contenha o código I23, I241, I48|
|Doença Cardíaca|K74, K76, K77, K79, K80, K82, K83, K84, K99|I20, I240, I249, I25, I50, I47, I49, I27, I28, I34, I35, I36, I37, I31, que contenha o código I42 (exceto I424), I43, I44, I45, I46, I51, I52, O903, I71, I72, I77, I780, I788, I789, I79, I85, I86, I871, I879, I890, I98, I99, M30, M31, R57, T063|
|Doenças Renais|U70, U71, U72, U75, U76, U77, U78, U79, U80, U85, U88, U90, U95, U98, U99|N10, N11, N12, N151, N159, N30, N390, A560, A562, A590, B374, N34, C64, C65, C67, C66, C68, D30, D099, D091, D41, S370, S371, S372, S373, T190, T191, T283, Q60, Q61, Q62, Q63, Q64, N00, N01, N03, N04, N05, N07, N08, N14, N150, N158, N16, N392, 20, N21, N22, N391, R80, R81, R82, N06, N13, N17, N18, N19, N25, N26, N27, N28, N29, N31, N32, N33, N35, N36, N37, N398, R392, T198, T199, Z905, Z906|
|Rastreamento Risco Cardiovascular|K22|Z136, Z824|

Fonte: SAPS/MS.

CAPÍTULO 9 - Gestão de Cadastros
================================

![](media/image821.png)

Neste capítulo abordaremos as questões relacionadas ao gerenciamento do cadastro do cidadão, principalmente no que tange a situações de multiplicidade de cadastro. A presença de situações deste tipo podem ter ocorrido por diversos motivos, como falta de conectividade para recuperação do CNS através do módulo cidadão, falta da informação do número do CNS no momento do cadastro individual do CDS, dentre outros. Pensando em solucionar esta situação apresentamos a funcionalidade da **Unificação de Cadastros** que tem por objetivo unificar os cadastros dos cidadãos, com ou sem CNS, que pertencem a uma única pessoa. Esse processo unirá de forma automática todos os registros de cadastro e atendimento, seja no PEC, seja no CDS, em um único prontuário.  Esse processo de unificação pode ser executado em algumas etapas pelo **gerente de serviços de saúde** ao clicar na opção "Unificação de Cadastros" (Figura 9.1) localizada na barra de navegação lateral.

Figura 9.1. Módulo de Gestão de Cadastros
![](media/image822.png)
Fonte: SAPS/MS.

> ![](media/image58.png) **NOTA**: Por se tratar de uma ação de alta sensibilidade e de muita responsabilidade apenas profissionais com perfil de "Gerente de UBS" poderão ter acesso a esta funcionalidade.

# 9.1 Busca pelo cidadão

A primeira etapa da unificação de cadastro consiste em realizar a pesquisa dos cadastros que serão unificados. Após clicar em "Unificação de cadastros" (Figura 9.1) a busca pelo cidadão se dá nos mesmos moldes do módulo Cidadão, permitindo que se realize a busca utilizando dados demográficos ou número de alguns documentos válidos:

- Nome do cidadão;

- número do CNS do cidadão;

- número do CPF;

- Data de nascimento;

- Nome da mãe;

Município de nascimento, como mostra a imagem abaixo:

Figura 9.3 - Busca Unificação de Cadastros
![](media/image823.png)
Fonte: SAPS/MS.

Para realizar esse tipo de consulta o profissional precisa preencher no mínimo o nome completo do cidadão, porém quanto mais informações forem preenchidas, maior será a acurácia do sistema na lista de resultados.

Após a inserção de pelo menos o nome do cidadão na busca é possível realizar a consulta clicando no botão "Buscar cidadão". Em seguida é apresentada uma lista conforme a figura 9.5.

Figura 9.5 - Resultado da Busca Cidadão
![](media/image824.png)
Fonte: SAPS/MS.

As buscas são realizadas apenas na base de dados local da instalação do PEC observando cadastros realizados tanto no módulo Cidadão quanto na Ficha Cadastro Individual do CDS. É importante sinalizar que nesta busca os cadastros "inativos", originados de versões anteriores do PEC, também estarão disponíveis para unificação, facilitando a agregação de informações clínicas anteriores que possam ter ficado vinculadas aos cadastros inativados. Caso a busca apresente algum cadastro inativo o sistema mostrará este cadastro com a marcação ![](media/image236.png). Apesar disto ele estará disponível para unificação como mostra a Figura 9.6.

Figura 9.6 - Marcação de cadastro inativo.
![](media/image237.png)
Fonte: SAPS/MS.

Caso a primeira consulta não apresente as opções de cadastros a serem unificados é possível realizar novas buscas sem perder os resultados das buscas já realizadas como indica a Figura 9.7.

Figura 9.7 - Ampliação dos resultados de busca
![](media/image825.png)
Fonte: SAPS/MS.

Caso o profissional deseje visualizar mais informações relacionadas ao cadastro apresentado na busca, basta clicar no ícone ![](media/image826.png) e o sistema apresentará dados relevantes do cidadão. Estes dados poderão auxiliar o profissional a ter certeza de que se trata de cadastros do mesmo cidadão, como mostra a Figura 9.9.

Figura 9.9 - Tela com informações de identificação do cadastro do cidadão
![](media/image827.png)
Fonte: SAPS/MS.

# 9.2 Processo de seleção de cadastros a serem unificados

Após a etapa de busca, é necessário selecionar os cadastros a serem unificados através do checkbox localizado ao lado esquerdo de cada item da lista (Figura 9.10).

Figura 9.10 - Tela de Unificar Cadastro
![](media/image828.png)
Fonte: SAPS/MS.

Após selecionados os cadastros, o usuário do sistema deverá selecionar o cadastro que ele deseja utilizar como o principal (Figura 9.11). O cadastro principal definirá os dados cadastrais, como por exemplo nome, data de nascimento e nome da mãe. A escolha do CNS é feita de forma automática e prioriza o CNS definitivo.

Figura 9.11 - Tela de Unificação do Cidadão
![](media/image829.png)
Fonte: SAPS/MS.

Ao clicar no botão "Unificar cadastros" o sistema apresentará a forma como o cadastro ficará após a unificação. Caso esteja de acordo com o desejado, é necessário clicar no botão "**Confirmar unificação**". Caso haja alguma incongruência é possível cancelar a ação, como mostra a imagem 9.12.

Figura 9.12 - Confirmação do processo de unificação de cadastros
![](media/image830.png)
Fonte: SAPS/MS.

A escolha do cadastro como principal interfere apenas nos dados demográficos, como por exemplo, nome, data de nascimento, nome da mãe. Cada cadastro unificado nesse processo pode possuir um prontuário diferente, com registros clínicos diversos, entretanto, todos esses registros serão unificados em apenas um prontuário.

Nas próximas buscas os cadastros unificados sempre serão identificados com uma marcação, como mostra a imagem a seguir:

![](media/image831.png)

CAPÍTULO 10 - Acompanhamento de condições de saúde
==================================================

![](media/image832.png)

Uma das atividades da Atenção Primária à Saúde é realizar o acompanhamento das condições de saúde dos cidadãos vinculados às Equipes da APS. Esta ação é importante e demanda muita organização por parte da equipe. Uma forma facilitada de realizar o acompanhamento das situações de saúde é por meio de relatórios ou listas de cidadãos que possuem determinada condição de saúde, extraídos a partir do sistema de informação utilizado pela equipe. Este módulo visa proporcionar aos profissionais de saúde um formato mais simples e otimizado de visualizar estas informações.

Figura 10.1 - Tela do Relatórios exibida com o perfil de profissional da equipe de AB
![](media/image833.png)
Fonte: SAPS/MS.

O painel de Acompanhamento de condições de saúde busca apresentar de forma clara a lista de cidadão vinculados à equipe de APS que possuem determinada situação de saúde.

> ![](media/image58.png) **NOTA**: Somente são apresentados neste painel cidadãos que estão vinculados à equipe de APS. A busca retorna apenas cidadãos que possuem todas as condições selecionadas e ativas na lista de problemas ou avaliadas no SOAP e na ficha de atendimento individual.

# 10.1 Filtros

Nesta funcionalidade são apresentados diversos filtros, para facilitar a busca de cidadãos por determinadas situações de saúde. Como ocorre nos relatórios do sistema, neste módulo também existe hierarquia de acesso, o gerente da unidade pode escolher a UBS ou a equipe que deseja visualizar o painel, já os profissionais das equipes, conseguem visualizar os cidadãos apenas de sua própria equipe.

## 10.1.1 Filtro de problemas e condições pré estruturado

O primeiro bloco apresenta situações muito comuns na APS, e que devem ser acompanhadas pelas equipes, conforme imagem. Lembre- se que essa forma de extração visa facilitar a busca, porém, as possibilidade de busca não se limitam a esse bloco.

![](media/image834.png)

Estes itens contemplam os seguintes CID10 e CIAP 2:

|Grupo|CIAP2|CID10|
|- |- |- |
|Diabetes|T89, T90, W85|E10, E100, E101, E102, E103, E104, E105, E106, E107, E108, E109, E11, E110, E111, E112, E113, E114, E115, E116, E117, E118, E119, E12, E120, E121, E122, E123, E124, E125, E126, E127, E128, E129, E13, E130, E131, E132, E133, E134, E135, E136, E137, E138, E139, E14, E140, E141, E142, E143, E144, E145, E146, E147, E148, E149, O24, O240, O241, O242, O243, O244, O249, P702, E232, N083, N251, P700|
|Hipertensão arterial|K86, K87, W81|I10, I11, I110, I119, I12, I120, I129, I13, I130, I131, I132, I139, I15, I150, I151, I152, I158, I159, I270, I272, O10, O100, O101, O102, O103, O104, O109, O11, O13, O14, O140, O141, O149, O15, O150, O151, O152, O159, O16, P292, K766|
|Obesidade|T82|E66, E660, E661, E662, E668, E669|
|Gravidez|W03, W05, W29, W71, W72, W73, W76, W78, W79, W80, W81, W84, W85, W75|O000, O001, O002, O008, O009, O11, O12, O120, O121, O122, O13, O14 , O140, O141, O149, O15, O150, O151, O159, O16, O20, O200, O208, O209, O21, O210, O211, O212, O218, O219, O22, O220, O221, O222, O223, O224, O225, O228, O229, O23, O230, O231, O232, O233, O234, O235, O239, O24, O240, O241, O242, O243, O244, O249, O25, O26, O260, O261, O263, O264, O265, O268, O269, O28, O280, O281, O282, O283, O284, O285, O288, O289, O29, O290, O291, O292, O293, O294, O295, O296, O298, O299, O30, O300, O301, O302, O308, O309, O31, O311, O312, O318, O32, O320, O321, O322, O323, O324, O325, O326, O328, O329, O33, O330, O331, O332, O333, O334, O335, O336, O337, O338, O339, O34, O340, O341, O342, O343, O344, O345, O346, O347, O348, O349, O35, O350, O351, O352, O353, O354, O355, O356, O357, O358, O359, O36, O360, O361, O362, O363, O365, O366, O367, O368, O369, O40, O41, O410, O411, O418, O419, O43, O430, O431, O438, O439, O44, O440, O441, O46, O460, O468, O469, O47, O470, O471, O479, O48, Z321, Z33, Z34, Z340, Z348, Z349, Z35, Z350, Z351, Z352, Z353, Z354, Z357, Z358, Z359, Z640, O00, O990, O991, O992, O993, O994, O995, O996, O997, z355, z356, W03, W05, W29, W71, W72, W73, W76, W78, W79, W80, W81, W84, W85, W75|

## 10.1.2 Filtro de problemas e condições pré estruturado ou busca por CIAP2 e CID10

É possível ainda realizar a busca por outras condições de saúde que contemplam um grupo de CIAP2 e CID10 relacionados, ou ainda, selecionando os códigos CIAP2 e CID10.

![](media/image835.png)

Para realizar a busca pelo "Grupos de condições prioritárias", selecione um ou mais problemas, conforme imagem abaixo:

![](media/image836.png)

Os problemas ou condições deste bloco representam um conjunto de CIAP2 e CID10, conforme quadro abaixo:

|Grupo|CIAP2|CID10|
|-|-|-|
|Asma|R96|J45, J450, J451, J458, J459, J46|
|AVC|K89, K90, K91|G45, G46, I60, I61, I610, I611, I612, I613, I614, I615, I616, I618, I619, I62, I63, I630, I631, I632, I633, I634, I635, I636, I638, I639, I64, I65, I66, I67, I670, I671, I672, I673, I675, I676, I677, I678, I679, I68, I69|
|Dengue|A77|A90, A91|
|Desnutrição|B80, B81, B82, T91|D46, D460, D461, D462, D463, D464, D50, D500, D508, D509, D51, D510, D511, D512, D513, D518, D519, D52, D520, D521, D528, D529, D53, D530, D531, D532, D538, D539, E40, E41, E42, E43, E44, E440, E441, E45, E46, E50, E500, E501, E502, E503, E504, E505, E506, E507, E508, E509, E51, E511, E512, E518, E519, E52, E53, E530, E531, E538, E539, E54, E55, E550, E559, E56, E560, E561, E568, E569, E58, E58, E59, E60, E60, E61, E610, E611, E612, E613, E614, E615, E616, E617, E618, E619, E63, E630, E631, E638, E639, O25, O990, P050, P052|
|Diabetes|T89, T90, W85|E10, E100, E101, E102, E103, E104, E105, E106, E107, E108, E109, E11, E110, E111, E112, E113, E114, E115, E116, E117, E118, E119, E12, E120, E121, E122, E123, E124, E125, E126, E127, E128, E129, E13, E130, E131, E132, E133, E134, E135, E136, E137, E138, E139, E14, E140, E141, E142, E143, E144, E145, E146, E147, E148, E149, O24, O240, O241, O242, O243, O244, O249, P702, E232, N083, N251, P700|
|Doença cardíaca|K74, K76, K77, K79, K80, K82, K83, K84, K99|I20, I240, I249, I25, I50, I47, I49, I27, I28, I34, I35, I36, I37, I31, I43, I44, I45, I46, I51, I52, O903, I71, I72, I77, I780, I788, I789, I79, I85, I86, I871, I879, I890, I98, I99, M30, M31, R57, T063, I420, I421, I422, I423, I425, I426, I427, I428, I429|
|DPOC|R95|J43, J430, J431, J432, J438, J439, J44, J440, J441, J448, J449|
|DST|X70, X71, X73, X90, X91, X92, Y70, Y71, Y72, Y76|A50, A500, A501, A502, A503, A504, A505, A506, A507, A509, A51, A510, A511, A512, A513, A514, A515, A519, A52, A520, A521, A522, A523, A527, A528, A529, A53, A530 , A539, A54, A540, A541, A542, A543, A544, A545, A546, A548, A549, A55, A56, A560, A561, A562, A563, A564, A568, A57, A58, A59, A590, A598, A599, A60, A600, A601, A609, A63, A630, A638, A64|
|Gravidez|W03, W05, W29, W71, W72, W73, W76, W78, W79, W80, W81, W84, W85, W75|O000, O001, O002, O008, O009, O11, O12, O120, O121, O122, O13, O14 , O140, O141, O149, O15, O150, O151, O159, O16, O20, O200, O208, O209, O21, O210, O211, O212, O218, O219, O22, O220, O221, O222, O223, O224, O225, O228, O229, O23, O230, O231, O232, O233, O234, O235, O239, O24, O240, O241, O242, O243, O244, O249, O25, O26, O260, O261, O263, O264, O265, O268, O269, O28, O280, O281, O282, O283, O284, O285, O288, O289, O29, O290, O291, O292, O293, O294, O295, O296, O298, O299, O30, O300, O301, O302, O308, O309, O31, O311, O312, O318, O32, O320, O321, O322, O323, O324, O325, O326, O328, O329, O33, O330, O331, O332, O333, O334, O335, O336, O337, O338, O339, O34, O340, O341, O342, O343, O344, O345, O346, O347, O348, O349, O35, O350, O351, O352, O353, O354, O355, O356, O357, O358, O359, O36, O360, O361, O362, O363, O365, O366, O367, O368, O369, O40, O41, O410, O411, O418, O419, O43, O430, O431, O438, O439, O44, O440, O441, O46, O460, O468, O469, O47, O470, O471, O479, O48, Z321, Z33, Z34, Z340, Z348, Z349, Z35, Z350, Z351, Z352, Z353, Z354, Z357, Z358, Z359, Z640, O00, O990, O991, O992, O993, O994, O995, O996, O997, z355, z356, W03, W05, W29, W71, W72, W73, W76, W78, W79, W80, W81, W84, W85, W75|
|Hanseníase|A78|A30, A300, A301, A302, A303, A304, A305, A308, A309, B92|
|Hipertensão arterial|K86, K87, W81|I10, I11, I110, I119, I12, I120, I129, I13, I130, I131, I132, I139, I15, I150, I151, I152, I158, I159, I270, I272, O10, O100, O101, O102, O103, O104, O109, O11, O13, O14, O140, O141, O149, O15, O150, O151, O152, O159, O16, P292, K766|
|Infarto|K75, K78|I21, I210, I211, I212, I213, I214, I219, I220, I221, I228, I229, I230, I231, I232, I233, I234, I235, I236, I238, I241, I48|
|Obesidade|T82|E66, E660, E661, E662, E668, E669|
|Reabilitação|A57|Z500, Z501, Z505, Z506, Z507|
|Rins|­­­­­­­­­­U70, U71, U72, U75, U76, U77, U78, U79, U80, U85, ­­­­U88, U90, U95, U98, U99|N10, N11, N12, N151, N159, N30, N390, A560, A562, A590, B374, N34,C64, C65, C67, C66, C68, D30, D099, D091, D41, S370, S371, S372, S373, T190, T191, T283, Q60, Q61, Q62, Q63, Q64, N00, N01, N03, N04, N05, N07, N08,­­­­­­­­­­­­­­­­­­­­­­­­­­­­­­­­­­N14, N150, N158, N16, N392, N20, N21, N22, N391, R80, R81, R82, N06, N13, N17, N18, N19, N25, N26, N27, N28, N29, N31, N32, N33, N35,N36, N37, N398, R392, T198, T199, Z905, Z906|
|Saúde mental|P02, P06, P10, P11, P12, P13, P22, P23, P24, P29, P73, P70, P71, P72, P73, P74, P75, P76, P78, P79, P80, P81, P85, P98, P99|F00, F000, F001, F002, F009, F01, F010, F011, F012, F013, F018, F019, F02, F020, F021, F022, F023, F024, F028, F03, F04, F05, F050, F051, F058, F059, F06, F060, F061, F062, F063, F064, F065, F066, F067, F068, F069, F07, F070, F071, F072, F078, F079, F09, F20, F200, F201, F202, F203, F204, F205, F206, F208, F209, F21, F22, F220, F228, F229, F23, F230, F231, F232, F233, F238, F239, F24, F25, F250, F251, F252, F258, F259, F28, F29, F30, F300, F301, F302, F308, F309, F31, F310, F311, F312, F313, F314, F315, F316, F317, F318, F319, F32, F320, F321, F322, F323, F328, F329, F33, F330, F331, F332, F333, F334, F338, F339, F34, F340, F341, F348, F349, F38, F380, F381, F388, F39, F40, F400, F401, F402, F408, F409, F41, F410, F411, F412, F413, F418, F419, F42, F420, F421, F422, F428, F429, F43, F430, F431, F432, F438, F439, F44, F440, F441, F442, F443, F444, F445, F446, F447, F448, F449, F45, F450, F451, F452, F453, F454, F458, F459, F48, F480, F481, F488, F489, F50, F500, F501, F502, F503, F504, F505, F508, F509, F51, F510, F511, F512, F513, F514, F515, F518, F519, F52, F520, F521, F522, F523, F524, F525, F526, F527, F528, F529, F53, F530, F531, F538, F539, F54, F55, F59, F60, F600, F601, F602, F603, F604, F605, F606, F607, F608, F609, F61, F62, F620, F621, F628, F629, F63, F630, F631, F632, F633, F638, F639, F64, F640, F641, F642, F648, F649, F65, F650, F651, F652, F653, F654, F655, F656, F658, F659, F66, F660, F661, F662, F668, F669, F68, F680, F681, F688, F69, F70, F700, F701, F708, F709, F71, F710, F711, F718, F719, F72, F720, F721, F728, F729, F73, F730, F731, F738, F739, F78, F780, F781, F788, F789, F79, F790, F791, F798, F799, F80, F800, F801, F802, F803, F808, F809, F81, F810, F811, F812, F813, F818, F819, F82, F83, F84, F840, F841, F842, F843, F844, F845, F848, F849, F88, F89, F90, F900, F901, F908, F909, F91, F910, F911, F912, F913, F918, F919, F92, F920, F928, F929, F93, F930, F931, F932, F933, F938, F939, F94, F940, F941, F942, F948, F949, F95, F950, F951, F952, F958, F959, F98, F980, F981, F982, F983, F984, F985, F986, F988, F989, F99|
|Saúde Sexual e Reprodutiva|P07, P08, P09, W10, W11, W12, W13, W14, W15, X01, X02, X03, X04, X05, X06, X07, X08, X09, X10, X11, X12, X13, X18, X20, X21, X22, X24, Y01, Y02, Y04, Y05, Y06, Y07, Y08, Y10, Y13, Y14, Y16, Y24|Z70, Z700, Z701, Z702, Z703, Z708, Z709|
|Tabagismo|P17|F17, F170, F171, F172, F173, F174, F175, F176, F177, F178, F179, Z716, Z720|
|Tuberculose|A70|A15, A150, A151, A152, A153, A154, A155, A156, A157, A158, A159, A16, A160, A161, A162, A163, A164, A165, A167, A168, A169, A17, A170, A171, A178, A179, A18, A180, A181, A182, A183, A184, A185, A186, A187, A188, A19, A190, A191, A192, A198, A199, B90, B900, B901, B902, B908, B909, J65|
|Usuário de álcool|P15, P16|F10, F100, F101, F102, F103, F104, F105, F106, F107, F108, F109, Z502, Z714, Z721|
|Usuário de outras drogas|P18, P19|F11, F110, F111, F112, F113, F114, F115, F116, F117, F118, F119, F12, F120, F121, F122, F123, F124, F125, F126, F127, F128, F129, F13, F130, F131, F132, F133, F134, F135, F136, F137, F138, F139, F14, F140, F141, F142, F143, F144, F145, F146, F147, F148, F149, F15, F150, F151, F152, F153, F154, F155, F156, F157, F158, F159, F16, F160, F161, F162, F163, F164, F165, F166, F167, F168, F169, F18, F180, F181, F182, F183, F184, F185, F186, F187, F188, F189, F19, F190, F191, F192, F193, F194, F195, F196, F197, F198, F199, R781, R782, R783, R784, R785, Z503, Z715, Z722|


> ![](media/image58.png){width="0.3906255468066492in" height="0.33203083989501314in"} **NOTA**: Atente para a opção de buscar apenas problemas/condições ativas na lista de problemas e condições do PEC. Essa função permite que os profissionais possam visualizar apenas a lista de cidadão com problemas ativos na lista de problemas e condições, e desconsiderar os problemas latentes ou resolvidos.

## 10.1.3 Filtro sexo ou identidade de gênero

Neste bloco é possível selecionar o sexo (feminino ou masculino, ou ambos) ou ainda selecionar a identidade de gênero (mulher transsexual, homem transsexual, travesti e outros).

![](media/image837.png)

![](media/image838.png)

## 10.1.4 Filtro de período

Neste bloco é possível selecionar o período em que deseja obter as informações. Informe o dia/mês/ano de início e o dia/mês/ano de fim, conforme figura abaixo. Caso a data de início não esteja preenchida, o sistema considera todos os atendimentos realizados até a data de fim. Caso contrário, se a data de fim não estiver preenchida, o sistema irá considerar o intervalo da data de início até a data do dia atual.

![](media/image839.png)

## 10.1.5 Filtro de faixa etária

Neste bloco é possível definir a faixa etária desejada para consulta. É possível buscar "Todas as faixas", "Criança (0 a 10 anos)", "Adolescente (11 a 19 anos), "Adulto (20 a 59 anos)", "Idoso (60 anos ou mais)" ou ainda, clique em "Outra" e insira a faixa etária desejada, conforme figura abaixo:

![](media/image840.png)

Após selecionar todos os filtros desejados, clique no botão ![](media/image841.png), e serão listados os cidadão vinculados à equipe, conforme imagem abaixo:

![](media/image842.png)

Ainda, será apresentado o botão ![](media/image843.png) para gerar os relatórios operacionais já existentes no sistema, a saber: "Relatório operacional de Crianças menores de 5 anos", "Relatório operacional de Gestante/Puérpera" e "Relatório operacional de Risco cardiovascular\'\'. Estes serão gerados utilizando as regras já existentes, como núcleo familiar consistido, dentre outros. Veja a imagem abaixo:

![](media/image844.png)

[^1]: O Catálogo de Materiais (CATMAT) do Sistema Integrado de Administração de Serviços Gerais (SIASG) do Ministério do Planejamento, Orçamento e Gestão (MPOG) é um sistema informatizado que permite a catalogação dos materiais destinados às atividades fins e meios da Administração Pública. O principal objetivo do CATMAT é estabelecer e manter uma linguagem única e padronizada para identificação, codificação e descrição de materiais a serem adquiridos pelo Governo Federal. O Ministério da Saúde (UC/MS) é responsável pela manutenção das classes referentes a produtos de saúde e medicamentos.

[^2]: [Resolução RDC nº 134 de 13 de julho de 2001](http://e-legis.anvisa.gov.br/leisref/public/showAct.php?id=16038&word=)

[^3]: Segundo a Política Nacional de Atenção Básica (BRASIL, 2011), "adscrição de usuários" é um processo de vinculação de pessoas e/ou famílias e grupos a profissionais/equipes, com o objetivo de ser referência para o seu cuidado.

[^4]: Em caso de re- territorialização, os logradouros, domicílios ou cidadãos que fiquem fora da área de cobertura da equipe poderão ser identificados com o status "Fora de Área", sendo identificados desta forma nos relatórios e no filtro "microárea".

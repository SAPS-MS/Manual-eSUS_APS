---
layout: default
title: Relatórios
parent: Prontuário Eletrônico do Cidadão v5.2
nav_order: 10
has_children: false
has_toc: true
last_modified_date: "25/09/2023"
---

<head>
    <style>
        p{text-align:justify};
    </style>
</head>

# CAPÍTULO 8 - Relatórios
{: .no_toc }

O módulo "Relatórios" permite que trabalhadores e gestores possam visualizar, de forma sintetizada e sistematizada, as ações de saúde realizadas no território. São vários tipos de relatórios divididos em gerenciais, consolidados e produção, e são utilizados por diferentes tipos de atores.

## Sumário
{: .no_toc .text-delta }

- TOC
{:toc}

![](media/pec_image747.png)

O acompanhamento das ações de saúde que são realizadas no território é uma tarefa extremamente importante no cotidiano das equipes de Atenção Primária à Saúde. Esta atividade, além de auxiliar os trabalhadores a enxergar seu território, exprime o resultado do seu esforço, podendo ser potente ferramenta de reflexão e transformação do seu processo de trabalho.

Nesta versão os relatórios são exibidos na barra lateral de navegação, oferecendo um caminho mais simples e rápido para cada relatório (Figura 8.1). Clicando na opção "Relatórios" o sistema apresenta a lista com todos os disponíveis, dependendo do tipo de acesso que o profissional ou gestor possui. Caso haja dúvida em relação ao relatório, é possível acionar um balão de ajuda representado pelo símbolo ![](media/pec_image748.png) no canto superior direito de cada tela dos relatórios.

Figura 8.1 - Tela do Relatórios exibida com o perfil de profissional da equipe de AB
![](media/pec_imagem749.png)
Fonte: SAPS/MS.

# 8.1 Administração dos relatórios

![](media/pec_image750.png)

As opções de administração e configuração estão disponíveis APENAS para os perfis de administrador da instalação. Para evitar o processamento desnecessário dos relatórios apenas o administrador da instalação, devidamente instruído, poderá utilizá-la.

## 8.1.1 Processamento

![](media/pec_image751.png)

O processamento dos relatórios é um processo diário e incremental automático iniciado a meia-noite (0h), a partir dos itens registrados ou enviados por meio do sistema. Este processo é pode ser ativado manualmente sempre que o usuário clica em Gerar/Transmitir os dados para envio ao SISAB, ver Seção 3.6.3.2.

Nesta funcionalidade, conforme podemos ver na Figura 8.2, é possível Marcar para reprocessamento ![](media/pec_image752.png) ou forçar o processamento ![](media/pec_image753.png) dos dados dos relatórios do sistema. A primeira funcionalidade permite que os dados dos relatórios, mesmo os dados que já foram processados, sejam reprocessados junto ao fluxo automático do sistema. A segunda funcionalidade força o processamento a ser executado de imediato.

{: .atencao }
a funcionalidade de "Forçar o processamento" pode ser um tanto dispendioso para a performance do PEC, a depender do tamanho da base de dados, podendo gerar lentidão para os outros usuários. Portanto, sempre que possível utilize a opção "Marcar para reprocessamento".

Figura 8.2 - Tela Processamento de Relatórios exibida somente com o perfil de administrador
![](media/pec_image754.png)
Fonte: SAPS/MS.

## 8.1.2 Configuração da Impressão

![](media/pec_image755.png)

Para evitar que consultas muito grandes criem uma carga exagerada no servidor da aplicação, por meio desta funcionalidade é possível configurar o fator que determinará quantos grupos de informações podem ser selecionados ao mesmo tempo, e ainda o período máximo, em meses, que poderá ser definido como intervalo para filtrar em cada relatório.  

Figura 8.3 - Tela de Configuração de Impressão exibida somente com o perfil de administrador
![](media/pec_image756.png)
Fonte: SAPS/MS.

{: .dica }
o fator de carga no sistema, em relação à geração de um relatório, está relacionado com a capacidade de processamento do computador que está sendo utilizado, bem como com a quantidade de registros dentro do sistema/instalação. Caso a geração de relatórios prejudique o desempenho do sistema, opte por uma configuração com fatores menores.

Após finalizar a configuração clique em Salvar ![](media/pec_image757.png) para ativar a nova configuração.

# 8.2 Nível de Agregação das Informações


O Sistema e-SUS APS, como sistema de gerenciamento de dados e informações da Atenção Primária, traz grande avanço no que diz respeito à segurança, sigilo e confidencialidade dos dados de saúde dos cidadãos. Isso quer dizer que apenas os profissionais que participam do atendimento ao cidadão têm acesso aos seus dados clínicos de saúde.

Atualmente, os relatórios do e-SUS APS disponibilizam informações agregadas, por meio dos relatórios gerenciais, consolidados e de produção. A seguir uma breve explicação sobre os agrupamentos dos relatórios no sistema:

- **Relatórios gerenciais**: a partir da versão 4.2 do sistema, está disponível um novo grupo de relatórios, Neste grupo, os dados são apresentados em uma tabela dinâmica construída pelo usuário. O usuário pode definir a tabela arrastando os campos disponíveis para linhas e colunas. Também é permitida a exportação destes relatórios para um arquivo no formado .csv.

- **Relatórios consolidados**: são os relatórios que permitem uma visualização da situação cadastral consolidada, de acordo com a data selecionada, permitindo ao usuário ver a informação mais atual até aquele momento. Ver seção 8.3 para mais detalhes sobre os relatórios.

- **Relatórios de produção**: são os relatórios que permitem uma visualização agregada das informações, tais como: o atendimento individual, odontológico, domiciliar (SAD), atividade coletiva, procedimentos, entre outros, bem como relatórios de resumo de produção. Ver seção 8.4 para mais detalhes sobre os relatórios.

## 8.2.1 Perfis de acesso e Filtros disponíveis

Para a geração dos relatórios estão disponíveis diversos tipos de filtros de acordo com o tipo de perfil utilizado pelo usuário, obedecendo o seu papel na estrutura da saúde no município. Os relatórios consolidados e de produção possuem estrutura de filtros iguais como descrito a seguir.

O gestor municipal, seja ele o próprio secretário, coordenador da Atenção Básica ou outros profissionais que fazem parte da equipe de gestão, terá opções de visualização no âmbito de todo o município. Desta forma, é possível utilizar filtros para a totalização dos dados nos relatórios em relação ao "Período", "Unidade saúde", "Equipe", "Profissional" e "Categoria Profissional", como mostra a Figura 8.4.

Figura 8.4 - Tipos de filtro de gestor municipal
![](media/pec_image758.png)
Fonte: SAPS/MS.

{: .nota }
as opções "Profissional" e "Categoria profissional" [não podem] ser utilizadas em conjunto. É possível filtrar as informações do relatório por profissional **[ou]** por uma categoria profissional.

O perfil de coordenador da UBS terá acesso apenas a dados do serviço de saúde sob sua gestão. É possível utilizar filtros para a totalização dos dados nos relatórios de acordo com as vinculações de unidade de saúde e equipe de saúde registradas no CNES. Estão disponíveis os filtros "Período", "Equipe", "Profissional" e "Categoria Profissional", como mostra a Figura 8.5.

Figura 8.5 - Tipos de filtro de coordenador de UBS
![](media/pec_image759.png)
Fonte: SAPS/MS.

Já os trabalhadores de saúde têm acesso aos relatórios, porém apenas aos dados produzidos por sua equipe. É possível utilizar, para a totalização dos dados nos relatórios, os filtros "Período", "Minha equipe" ou apenas "Minhas produções", como mostra a Figura 8.6.

Figura 8.6 - Tipos de filtro de trabalhador de saúde
![](media/pec_image760.png)
Fonte: SAPS/MS.

Outra novidade para os filtros disponíveis é possibilidade de extrair relatórios analíticos ![](media/pec_image761.png) e da série histórica ![](media pec_image762.png) nos relatórios de produção. Já nos relatórios consolidados, além da série histórica é possível extrair o mensal ![](media pec_image763.png) no relatório de situação do território, que será abordado mais adiante. A estrutura dos filtros segue o mesmo padrão dos descritos anteriormente, com a diferença que nos relatórios da série histórica, o período pode ser escolhido entre os últimos 3 meses, últimos 6 meses, últimos 12 meses ou simplesmente selecionar o período que deseja extrair os relatórios.

![](media/pec_image764.png)

## 8.2.2 Grupo de Informações Disponíveis para Impressão

Os relatórios consolidados e de produção, tem um modelo padronizado para ativar ou desativar os grupos de informações a serem disponibilizados no impresso do relatório. Conforme vemos na Figura 8.7, usando como exemplo o relatório de Atividades Coletivas, podemos fazê- lo por meio da seleção do checkbox correspondente ao grupo de informações do relatório.

Figura 8.7 - Tipo de seleção dos grupos de informação
![](media/pec_image765.png)
Fonte: SAPS/MS.

Para configurar o impresso do relatório realize os passos a seguir:

1.Abra a opção de seleção dos grupos de informação clicando no botão de dropdown ![](media/pec_image766.png).

![](media/pec_image767.png)

2.Marque ou desmarque o checkbox, conforme a necessidade. Caso o checkbox esteja marcado ![](media/pec_image768.png), o grupo será mostrado no impresso, caso contrário ![](media/pec_image769.png), o grupo não será mostrado.

Todos os grupos de informações vem ativados por padrão nos relatórios. Utilize as opções Selecionar Todos ![](media/pec_image770.png) e Limpar ![](media pec_image771.png), para marcar todos os grupos de informação ou desmarcar todos os grupos, respectivamente.

## 8.2.3 Filtros personalizados

As opções de filtros personalizados possibilitam ao usuário filtrar as informações do relatório. Para usar filtros personalizados realize os passos a seguir:

![](media/pec_image772.png)

Passo 1. Em "Filtros personalizados" selecione na opção "Campo filtro" a informação que deseja obter e clique em adicionar ![](media/pec_image773.png).

![](media/pec_image774.png)

Passo 2. Ao selecionar um dos itens do "Campo filtro", serão apresentadas outras opções de filtro.

![](media/pec_image775.png)

Passo 3. Selecione o(s) iten(s) desejado(s), clicando marcando cada checkbox do item que irá filtrar o relatório. No caso em destaque, selecione para "Destino do lixo" o item "Céu aberto" ![](media/pec_image776.png), por exemplo, para filtrar os cadastros onde os domicílios tem lixo a céu aberto.

Passo 4. Para filtrar outros itens para compor um mesmo relatório, basta seguir os passos anteriores.

- Caso queira remover um filtro, basta excluir o item do campo "filtro personalizado", usando o botão "Excluir" ![](media/pec_image777.png).

# 8.3 Relatórios Consolidados

Figura 8.8 - Tela do Relatórios consolidados exibida com o perfil de profissional da equipe de AB

![](media/pec_image778.png)

Fonte: SAPS/MS.

Os relatórios consolidados trazem o estado atual do registro para um determinado conjunto de informações. Estes seguem o modelo padrão de estruturação dos relatórios, porém o usuário ao invés de selecionar um período, selecionará a data limite para consolidação dos dados.

Figura 8.9 - Tela do Relatório Consolidado de Cadastro Individual
![](media/pec_image779.png)
Fonte: SAPS/MS.

## 8.3.1 Relatório consolidado de Cadastro domiciliar e territorial

Este relatório reflete o consolidado do estado atual do cadastro domiciliar e territorial, contém as informações registradas por meio das fichas de Cadastro domiciliar e territorial, bem como do Aplicativo do e-SUS APS Território, quando este estiver sendo utilizado.

Figura 8.10 - Tela do Relatório de cadastro domiciliar e territorial exibida com o perfil de profissional de saúde
![](media/pec_image780.png)
Fonte: SAPS/MS.

Para gerar o relatório de cadastro domiciliar e territorial primeiro o usuário do sistema deve escolher a data limite para a consolidação dos dados no campo "Data" ![](media/pec_image781.png).

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

![](media/pec_image782.png)

No filtro personalizado são apresentados as variáveis consolidadas que informam os dados sobre o abastecimento de água, água para consumo no domicílio, animais no domicílio, condição de posse e uso da terra, destino do lixo, disponibilidade de energia elétrica, forma de escoamento do banheiro ou sanitário, localização, material predominante na construção das paredes externas, microárea, qual animal no domicílio, recusa de cadastro, renda familiar (salário mínimo), situação de moradia, tipo de acesso ao domicílio, tipo de domicílio e tipo de imóvel.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

As variáveis apresentadas possibilitam a realização de uma análise inicial da situação de saúde do território de atuação das equipes de Atenção Básica, com a finalidade de construção de estratégia de enfrentamento das condicionalidades e dos determinantes sociais que afetam a qualidade da saúde da população assistida.

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do CDS sobre a Ficha de Cadastro Domiciliar e Territorial.

## 8.3.2 Relatório Consolidado de Cadastro Individual

Este relatório reflete o consolidado do estado atual do cadastro individual, contém as informações registradas por meio da ficha de Cadastro Individual, bem como do Aplicativo do e-SUS APS Território, quando este estiver sendo utilizado.

Figura 8.11 - Tela do Relatório de cadastro individual exibida com o perfil de profissional da equipe de AB
![](media/pec_image783.png)
Fonte: SAPS/MS.

Para gerar o relatório de cadastro individual primeiro o usuário do sistema deve escolher a data limite para a consolidação dos dados no campo "Data" ![](media pec_image781.png).

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

![](media/pec_image784.png)

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do CDS sobre a Ficha de Cadastro Individual.

## 8.3.3 Relatório da Situação do Território

O relatório consolidado da situação do território apresenta informações gerais sobre a área de atuação das equipes de saúde, reunindo dados sobre o cadastro do cidadão, condições gerais do domicílio, situação sociodemográfica e pessoas em situação de rua, sendo um conjunto de informação necessária para o planejamento das ações de saúde do território.

Neste relatório é possível avaliar a situação do território para uma competência específica ou avaliar a evolução dos dados do território para um período escolhido. Para isso, escolha entre os tipos de relatório ![](media/pec_image785.png) ou de ![](media/pec_image786.png), conforme as figuras a seguir, respectivamente:

![](media/pec_image787.png)

![](media/pec_image788.png)

# 8.4 Relatórios de Produção

Os relatórios de produção trazem os dados (eventos) agregados em um determinado período, orientados pelo bloco de informação dentro do sistema. Os blocos de informações são organizados de forma similar ao formato de envio dos registros ao SISAB. Atualmente os blocos disponíveis são:

- Atendimento domiciliar

- Atendimento individual

- Atendimento odontológico individual

- Atividade coletiva

- Avaliação de elegibilidade e admissão

- Marcadores de consumo alimentar

- Procedimentos consolidados

- Procedimentos individualizados

- Resumo de produção

- Síndrome neurológica por Zika / Microcefalia

- Vacinação

- Visita domiciliar e territorial


Figura 8.12 - Tela de Relatório de produção exibida com o perfil de profissional da equipe de AB

![](media/pec_image789.png)

Fonte: SAPS/MS.

Os relatórios de produção apresentam novidades para os filtros disponíveis, sendo possível extrair relatórios analíticos ![](media/pec_image761.png) e da série histórica ![](media/pec_image762.png).

Nas seções seguintes são detalhados cada bloco de informação.

## 8.4.1 Atendimento domiciliar

Este relatório contabiliza os dados referentes aos atendimentos domiciliares dentro do período determinado, tendo como fonte de informação as Fichas de Atendimento Domiciliar ou do Aplicativo e-SUS AD, que são de uso exclusivo do Serviço de Atenção Domiciliar (SAD).

Figura 8.13 - Tela do Relatório de atendimento domiciliar exibida com o perfil de profissional da equipe de AB
![](media/pec_image790.png)
Fonte: SAPS/MS.

Para gerar o relatório de atendimento domiciliar primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

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

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Atendimento Domiciliar**.

## 8.4.2 Atendimento individual

Este relatório contabiliza os dados referentes aos atendimentos individuais dentro do período determinado, tendo como fonte de informação às Ficha de atendimento individual e os Atendimentos realizados no PEC.

Figura 8.14 - Tela do Relatório de cadastro individual exibida com o perfil de profissional da equipe de AB
![](media/pec_image792.png)
Fonte: SAPS/MS.

Para gerar o relatório de atendimento individual primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

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

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Atendimento Individual**.

## 8.4.3 Atendimento odontológico individual

Este relatório contabiliza os dados referentes aos atendimentos odontológicos individuais dentro do período determinado, tendo como fonte de informação as Fichas de atendimento odontológico individual e os Atendimentos odontológicos realizados no PEC.

Figura 8.15 - Tela do Relatório de cadastro individual exibida com o perfil de profissional da equipe de AB
![](media/pec_image793.png)
Fonte: SAPS/MS.

Para gerar o relatório de atendimento odontológico primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

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

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Atendimento Individual Odontológico**.

## 8.4.4 Atividade coletiva

Este relatório contabiliza os dados referentes às atividades coletivas dentro do período determinado, tendo como fonte de informação os registros das Fichas de atividade coletiva.

Figura 8.16 - Tela do Relatório de atividade coletiva exibida com o perfil de profissional da equipe de AB
![](media/pec_image794.png)
Fonte: SAPS/MS.

Para gerar o relatório de atividades coletivas primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

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

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Atividade Coletiva**.

## 8.4.5 Avaliação de elegibilidade e admissão

Este relatório contabiliza os dados referentes às avaliações de elegibilidade e admissão dentro do período determinado, tendo como fonte de informação as Fichas de avaliação de elegibilidade e admissão, bem como os registros de avaliação de elegibilidade do Aplicativo e-SUS AD. Estes instrumentos são de uso exclusivo do SAD.

Figura 8.17 - Tela do Relatório de atividade coletiva exibida com o perfil de profissional da equipe de AB
![](media/pec_image795.png)
Fonte: SAPS/MS.

Para gerar o relatório de avaliação de elegibilidade e admissão primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

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

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Avaliação de Elegibilidade e Admissão** do SAD.

## 8.4.6 Marcadores de consumo alimentar

Este relatório contabiliza os dados referentes aos marcadores de consumo alimentar dentro do período determinado, tendo como fonte as fichas de Marcadores de consumo alimentar.

Figura 8.18 - Tela do Relatório de marcadores de consumo alimentar exibida com o perfil de profissional da equipe de AB
![](media/pec_image796.png)
Fonte: SAPS/MS.

Para gerar o relatório de marcadores de consumo alimentar primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados". As variáveis do grupo de informação são:

- Resumo de produção

- Faixa etária

- Sexo

- Local de atendimento

- Crianças menores de 6 meses

- Crianças de 6 a 23 meses

No filtro personalizado são apresentados outras variáveis consolidadas que informam os dados sobre estes marcadores e que estão contidas na ficha de marcadores de consumo alimentar.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a ficha **Marcadores de Consumo Alimentar**.

## 8.4.7 Procedimentos

Este relatório contabiliza os dados referentes aos procedimentos dentro do período determinado, tendo como fonte as Fichas de procedimentos ou os registros de procedimentos no PEC.

Figura 8.19 - Tela de Relatório de procedimentos exibida com o perfil de profissional da equipe de AB
![](media/pec_image797.png)
Fonte: SAPS/MS.

Para gerar o relatório procedimentos primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

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

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Procedimentos**.

## 8.4.8 Procedimentos consolidados

Este relatório contabiliza os dados referentes aos procedimentos consolidados dentro do período determinado, tendo como fonte as Fichas de procedimentos e os registros de procedimentos no PEC.

Figura 8.20 - Tela de Relatório de procedimentos consolidados exibida com o perfil de profissional da equipe de AB
![](media/pec_image798.png)
Fonte: SAPS/MS.

Para gerar o relatório procedimentos consolidados primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

Os relatórios poderão ser gerados a partir dos "grupos de informações disponíveis para impressão" ou pela opção "filtros personalizados".

O filtro personalizado apresenta todas as variáveis que aparecem no relatório de procedimentos consolidados e que podem ser gerados de forma isoladas, tais como os totais de aferição de PA, temperatura, coleta de material para exame laboratorial, curativo simples, glicemia capilar, medição de altura e medição de peso.

Após selecionar as variáveis desejadas para gerar o relatório basta clicar no botão "Exportar CSV" ou "Imprimir".

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Procedimento**, especialmente sobre o bloco de procedimentos consolidados.

## 8.4.9 Resumo de produção

Este relatório contabiliza a produção de todos os registros realizados por tipo de ficha.

Figura 8.21 - Tela de Resumo de produção exibida com perfil de profissional da equipe de AB
![](media/pec_image799.png)
Fonte: SAPS/MS.

Para gerar o relatório de resumo de produção primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

Após a escolha do período basta clicar em "Exportar CSV" ou "Imprimir" para gerar o relatório de resumo de produção.

Figura 8.22 - Exemplo do Relatório de Resumo de Produção
![](media/pec_image800.png)
Fonte: SAPS/MS.

Os registros nas fichas onde é informado o CNS do cidadão são apresentados como \"Identificados\", já os registros sem CNS são os \"Não identificados\". Ou seja, por meio desse relatório pode- se monitorar o percentual de ações que ficam vinculadas ao prontuário do cidadão e aquelas que terão apenas finalidade estatística. Idealmente se espera que o máximo de registro sejam identificados.

Ainda é possível identificar a quantidade de novos cadastros, atualização dos cadastrados e recusa de cadastro.

## 8.4.10 Síndrome neurológica por Zika / Microcefalia

Este relatório contabiliza os dados referentes aos atendimentos de síndrome neurológica por Zika / Microcefalia dentro de um período determinado , tendo como fonte de informação os registros da Ficha complementar de Síndrome neurológica por Zika / Microcefalia, bem como os atendimentos no PEC.

Figura 8.23 - Tela do Relatório da ficha complementar - Síndrome neurológica por Zika/Microcefalia exibida com perfil de profissional da equipe de AB.
![](media/pec_image801.png)
Fonte: SAPS/MS.

Para gerar o relatório da ficha complementar primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

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

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha complementar** de Síndrome neurológica por Zika / Microcefalia.

## 8.4.11 Visita domiciliar e territorial

Este relatório contabiliza os dados referentes às visitas domiciliares dentro do período determinado, tendo como fonte de informação as Fichas de visita domiciliar e territorial ou o Aplicativo e-SUS APS Território.

Figura 8.24 - Tela do Relatório de visita domiciliar e territorial exibida com perfil de profissional da equipe de AB
![](media/pec_image802.png)
Fonte: SAPS/MS.

Para gerar o relatório de visita domiciliar e territorial primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

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

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Visita Domiciliar e Territorial**.

## 8.4.12 Vacinação

Este relatório contabiliza os dados referentes a administração dos imunobiológicos dentro de um período determinado, tendo como fonte de informação as Fichas de vacinação ou por meio do registro no PEC.

Figura 8.25 - Tela do Relatório de vacinação exibida com perfil de profissional da equipe de AB
![](media/pec_image803.png)
Fonte: SAPS/MS.

Para gerar o relatório de vacinação primeiro o usuário do sistema deve escolher o período que gostaria de consultar.

![](media/pec_image791.png)

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

{: .nota }
Para mais informações sobre as variáveis e as opções de filtro, consulte o Manual de Preenchimento das Fichas do **CDS** sobre a **Ficha de Vacinação**.

### 8.4.12.1 Orientação para extração de relatórios de doses aplicadas para auxílio no cálculo de cobertura vacinal.

O relatório de vacinação apresenta informações agregadas dos registros de doses aplicadas por imunobiológicos.

Para a geração dos relatórios estão disponíveis diversos tipos de filtros de acordo com o tipo de perfil utilizado pelo usuário do sistema e-SUS APS.

Para a impressão com o perfil de gestor municipal (secretário de saúde, coordenador da Atenção Básica ou outros profissionais que fazem parte da equipe de gestão) existe a opção de visualização dos dados em todo o município. Desta forma, é possível utilizar filtros para a totalização dos dados nos relatórios em relação ao "Período", "Unidade saúde", "Equipe", "Profissional" e "Categoria Profissional", como mostra a Figura 1.

Figura 1 - Tipos de filtro de gestor municipal
![](media/pec_image758.png)

{: .nota }
as opções "Profissional" e "Categoria profissional" [não podem] ser utilizadas em conjunto. É possível filtrar as informações do relatório por profissional **[ou]** por uma categoria profissional.

Para visualizar os dados referentes ao quantitativo de dose aplicadas referentes a um imunobiológico em um determinado período e local, siga os passos a seguir:

1.Escolha o "Período" e a "Unidade de saúde";

2.Utilize o campo "Filtros personalizados";

3.No "Campo filtro" selecione as variáveis que pretende usar para compor o relatório.

![](media/pec_image804.png)

**Por exemplo:** Quantas doses de BCG foram aplicadas em crianças menores de 01 ano. Para isso basta selecionar as variáveis "imunobiológico", "Dose" e "Faixa etária" e incluir "BCG", "Dose" + "Revacinação" e "menos de 01 ano", respectivamente.

Figura 5. Filtros personalizados
![](media/pec_image805.png)

4\. Se quiser extrair o relatório somente com as informações escolhidas nas variáveis, selecione as mesmas, no campo "Grupos de informações disponíveis para a impressão" (Figura 6).

Figura 6. Grupo de informação disponíveis para impressão
![](media/pec_image806.png)

5\. Após a seleção das variáveis é possível extrair o relatório no formato .CSV ou simplesmente imprimi- lo.

6\. Pronto o relatório é apresentado conforme a figura abaixo.

![](media/pec_image807.png)

# 8.5 Relatórios Gerenciais

![](media/pec_image903.png)

{: .atualizacao }
A partir da versão 4.2 estarão disponíveis relatórios gerenciais com informações sobre o funcionamento da Unidade de Saúde.

Os Relatórios Gerenciais tem como principal objetivo apresentar ao Gerente da UBS e às equipes informações específicas e essenciais sobre o funcionamento da Unidade de Saúde, observando dados gerados durante os fluxos presentes no cotidiano do serviço.

Este novo formato de relatório utiliza uma tecnologia mais sofisticada que os demais relatórios já existentes, pois oferece ao profissional uma forma mais dinâmica de trabalhar a informação.

## 8.5.1 Relatório de Absenteísmo

O Relatório de Absenteísmo apresenta de forma clara o comportamento dos usuários em relação aos agendamentos realizados previamente, as faltas dos cidadãos e outras informações relevantes. Utiliza contagem de eventos do módulo de agenda em que o cidadãos não compareceu ou não aguardou.

Figura 8.37 - Tela principal do relatório de absenteísmo

![](media/pec_image857.png)

Fonte: SAPS/MS.

A Figura 8.37 apresenta a tela principal deste relatório. Nele são apresentados blocos com as possibilidades de variáveis que podem ser utilizadas para visualizar estas informações.

O primeiro bloco (figura 8.38) apresenta o período que o profissional deseja que seja utilizado como intervalo de tempo para a análise. É possível selecionar as opções pré-definidas dos últimos 3, 6 ou 12 meses. Também é possível selecionar um intervalo de tempo customizado.

Figura 8.38 - Bloco para seleção do intervalo de tempo.

![](media/pec_image858.png)

Fonte: SAPS/MS.

A seguir (Figura 8.39) são apresentados os campos disponíveis para uso, sendo elas:
- Equipe
- Categoria profissional
- Turno
- Tipo de falta
- Profissional
- Tempo entre agendamento e consulta
- CBO
- Faixa etária

Figura 8.39 - Variáveis disponíveis.

![](media/pec_image859.png)

Fonte: SAPS/MS.

É possível filtrar as variáveis de cada campo clicando no ícone ![](media/pec_image872.png) como mostra a Figura 8.40. 

Figura 8.40 - Filtro de variáveis do campo.

![](media/pec_image873.png)

Fonte: SAPS/MS.

Estes campos podem ser distribuídas no bloco seguinte (figura 8.41) que representam as colunas e linhas da tabela que será construída. Para isto basta clicar e arrastar cada variável para uma das caixas. É possível incluir mais de um campo na linha e na coluna.

Figura 8.41 - Caixas "Colunas" e "Linhas".

![](media/pec_image868.png)

Fonte: SAPS/MS.

Feito isso, é possível escolher a forma que deve ser apresentado na tabela a ser construída. O sistema realiza as operações de contagem das variáves ou o cálculo percentual entre as variáveis, como mostra a Figura 8.42.

Figura 8.42 - Formas de cálculo dos resultados.

![](media/pec_image861.png)

Fonte: SAPS/MS.

Caso algum campo seja filtrado o sistema apresentará os filtros aplicados, indicando qual(ais) o(s) campo(s) e variável(eis) foram filtradas como mostra a Figura 8.43.

Figura 8.43 - Formas de cálculo dos resultados.

![](media/pec_image862.png)

Fonte: SAPS/MS.

Se desejar limpar as seleções, clique no botão ![](media/pec_image863.png). Para concluir o processo clique no botão ![](media/pec_image864.png).

Ao final será apresentado uma tabela com os resultados baseados nas seleções realizadas e distribuídas nos quadros **Colunas** e **Linhas**, como mostra a Figura 8.44 a seguir.

Figura 8.44 - Formas de cálculo dos resultados.

![](media/pec_image865.png)

Fonte: SAPS/MS.

Caso necessite, é possível realizar a exportação destes relatórios para um arquivo no formado .csv clicando no botão ![](media/pec_image874.png).

[^3]: Segundo a Política Nacional de Atenção Básica (BRASIL, 2011), "adscrição de usuários" é um processo de vinculação de pessoas e/ou famílias e grupos a profissionais/equipes, com o objetivo de ser referência para o seu cuidado.

[^4]: Em caso de re- territorialização, os logradouros, domicílios ou cidadãos que fiquem fora da área de cobertura da equipe poderão ser identificados com o status "Fora de Área", sendo identificados desta forma nos relatórios e no filtro "microárea".

## 8.5.2 Relatório de Atendimento

Este relatório tem por objetivo obter dados quantitativos sobre o número de atendimentos individuais e odontológicos distribuídos em um determinado período de tempo, com a finalidade de auxiliar os gestores na tomada de decisões estratégicas da unidade de saúde.

Figura 8.45 Tela principal do relatório de atendimentos

![](media/pec_image904.png)

Fonte: SAPS/MS

É possível extrair o relatório de atendimento selecionando o período mensal, semanal, do último mês, último 3 meses, último 6 meses ou ainda em um período personalizado. 

O relatório ainda pode ser extraído com a finalidade de conhecer a quantidade de atendimento a um determinado problema ou condição de saúde, para isso, basta selecionar a CIAP2, CID10 ou os grupos de condições prioritárias. 

{: .nota }
O relatório gerencial de atendimentos apresenta a contagem dos atendimentos individuais e odontológicos realizados. A origem dos atendimentos deste relatório são o CDS e o PEC. Os atendimentos do tipo "Escuta inicial / Orientação" não são apresentados.

Da mesma forma como acontece no Relatório de Absenteísmo também é possível fazer filtros no bloco "Campos Disponíveis", arrastar as variáveis para serem visualizadas em colunas ou linhas, apresentar os resultados na tabela no formato de contagem ou porcentagem e extrair esses dados em .CSV

Figura 8.46 Tela principal do relatório de atendimetno

![](media/pec_image906.png)

Fonte: SAPS/MS

## 8.5.3 Relatório de Vacinação

Este relatório tem por objetivo obter dados quantitativos sobre o número de doses de determinadas vacinas aplicadas, distribuídos em um determinado período de tempo, com a finalidade de auxiliar o gestor na tomada de decisões estratégicas da unidade de saúde.

Figura 8.46 Tela principal do relatório de vacinação

![](media/pec_image905.png)

Fonte: SAPS/MS

É possível extrair o relatório de vacinas aplicadas selecionando o período mensal, semanal, do último mês, último 3 meses, último 6 meses ou ainda em um período personalizado. 

{: .nota }
O relatório gerencial de vacinação apresenta a quantidade de doses de vacinas aplicadas nos atendimentos de vacinação provenientes tanto do CDS quanto do PEC.

Da mesma forma como acontece no Relatório de Absenteísmo também é possível fazer filtros no bloco "Campos Disponíveis", arrastar as variáveis para serem visualizadas em colunas ou linhas, apresentar os resultados na tabela no formato de contagem ou porcentagem e extrair esses dados em .CSV

Figura 8.47 Tela principal do relatório de vacinação

![](media/pec_image907.png)

Fonte: SAPS/MS
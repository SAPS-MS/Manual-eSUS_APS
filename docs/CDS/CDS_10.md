---
layout: default
title: Ficha de Vacinação
parent: Coleta de Dados Simplificada v3.2
nav_order: 11
has_children: false
has_toc: true
---

# CAPÍTULO 10 - Ficha de Vacinação
{: .no_toc }

## Sumário
{: .no_toc .text-delta }

- TOC
{:toc}

> ![](media/image53.png) **ATUALIZAÇÃO:** disponível a partir da versão 3.0.

**Objetivo da ficha:** É utilizada para registro de informações das vacinas aplicadas na rotina, campanhas ou demais estratégias realizadas na Atenção Básica. Ela identifica as vacinas que foram aplicadas no cidadão, assim como o profissional que a realizou. Esta ficha não deve ser utilizada para o registro de doses aplicadas anteriormente, mas somente para as administradas no dia.

**Profissionais que utilizam esta ficha:** É utilizada pelos profissionais que realizam aplicação de vacinas no âmbito da Atenção Básica, como enfermeiros, técnicos de enfermagem e médicos.

A seguir são apresentados os campos da Ficha de Vacinação e as orientações de como preenchê-los. Os campos assinalados com asterisco (\*) são de preenchimento obrigatório.

> ![](media/image1.png) **NOTA**: para informações sobre **Normas e Procedimento de Vacinação**, acesse o endereço eletrônico do [Manual disponibilizado pelo Programa Nacional de Imunizações](http://bvsms.saude.gov.br/bvs/publicacoes/manual_procedimentos_vacinacao.pdf)

## 10.1 Cabeçalho

O cabeçalho tem um bloco para a identificação e controle da digitação, que é importante na organização do trabalho a nível local. Este bloco é preenchido pelo digitador.

Figura 10.1 -- Cabeçalho da Ficha de Vacinas

![cabeçalho_vacina.png](media/image94.png)

*Fonte: SAS/MS.*

Quadro 10.1 -- Identificação e controle da digitação
|CAMPO|ORIENTAÇÃO DE PREENCHIMENTO|
|-|-|
|DIGITADO POR|Nome do profissional que digitou a ficha.|
|DATA|Dia/mês/ano em que a digitação foi realizada no sistema.|
|CONFERIDO POR   Nome do profissional que conferiu o correto preenchimento da ficha.|
|FOLHA Nº|Este campo pode ser utilizado na organização do processo de trabalho do profissional que realizou o procedimento, por meio da inserção de numeração das folhas.|

*Fonte: SAS/MS.*

## 10.2 Identificação do profissional e do estabelecimento de saúde

O próximo bloco é utilizado para identificação do profissional que realizou os procedimentos.

Figura 10.2 -- Identificação do profissional e lotação

![prof.png](media/image95.png)

*Fonte: SAS/MS.*

Quadro 10.2 -- Identificação do profissional e lotação

|CAMPO|ORIENTAÇÃO DE PREENCHIMENTO|
|-|-|
|  CNS do Profissional*|   Número do Cartão Nacional de Saúde (CNS) do profissional que realizou a aplicação da vacina. Cada registro de aplicação de vacina deve ser realizado e registrado por apenas UM profissional.|
|  CBO*|                   Classificação Brasileira de Ocupações (CBO) do profissional que realizou a aplicação da(s) vacina(s).|
|  CNES* |                 Código do Cadastro Nacional de Estabelecimentos de Saúde (CNES) da Unidade Básica de Saúde que oferta o serviço de vacinação onde o profissional que aplicou a(s) vacina(s) está lotado.|
|  INE* |                  Código Identificador Nacional de Equipes (INE) no Cadastro Nacional de Estabelecimentos de Saúde (CNES) do Ministério da Saúde, que identifica a equipe onde o profissional está lotado, seja equipes Saúde da Família, Nasf, CnR, etc. Este campo não é obrigatório para profissionais que não estão vinculados a equipes.|
|  DATA*  |                Dia/mês/ano em que foram realizadas as aplicações de vacina.|

*Fonte: SAS/MS.*

\* *Campo de preenchimento obrigatório.*

## 10.3 Identificação dos cidadãos e local de atendimento

Este bloco de informações permite a identificação do usuário que foi atendido por meio do CNS ou CPF, data de nascimento e sexo. Os dados informam também sobre o local do atendimento.

> ![](media/image2.png) ATENÇÃO: Para aumentar o número de registros identificados, a partir da versão 3.2.20 é possível registrar CNS ou CPF do cidadão atendido.

Figura 10.3 -- Identificação dos cidadãos e local de atendimento

![](media/image96.png)

*Fonte: SAS/MS.*

Quadro 10.3 -- Dados dos usuários e local de atendimento

|     CAMPO    |     ORIENTAÇÃO SOBRE O BLOCO/PREENCHIMENTO    |
|-|-|
|     N°    |     Cada Ficha de Vacinação permite o   registro de informações de 08 cidadãos (um   por coluna). Caso o número de vacinas no dia   exceda esse total, o profissional deverá utilizar uma nova ficha.    |
|     TURNO*    |     Turno em que foram realizadas as   vacinações, sendo: M - manhã, T - tarde    ou N - noite.    |
|     Nº PRONTUÁRIO    |     Campo destinado ao número do   prontuário da família ou do indivíduo no estabelecimento de saúde. Este campo é usado como   referência da informação do paciente na unidade, para os casos em que seja   necessário fazer verificação dos dados.    |
|     CNS ou CPF DO   CIDADÃO    |     Campo destinado ao número do Cartão Nacional de   Saúde (CNS) do cidadão que está em atendimento. Os   números devem ser inseridos no sentido   vertical. Cidadãos sem o CNS poderão e   deverão ser atendidos pela equipe.     |
|     DATA DE NASCIMENTO*    |     Informe o dia, mês e ano do   nascimento do cidadão. Variável de verificação do CNS.     |
|     SEXO*    |     Assinalar F – feminino ou M –   masculino.    |
|     LOCAL DE ATENDIMENTO*    |     Informar o número referente   ao local em que foi realizada a(s) vacinação(ões) do usuário, considerando as   seguintes opções:<br>      (01) UBS<br>      (02) Unidade Móvel<br>      (03) Rua<br>      (04) Domicílio<br>      (05) Escola/Creche<br>      (06) Outros <br>     (07) Polo (Academia da Saúde) – denomina-se polo a unidade (espaço físico)   do Programa Academia da Saúde. É considerado polo tanto a estrutura física   construída especificamente para o desenvolvimento do programa quanto o espaço   físico destinado para tal fim nas dependências de uma UBS, desde que o número   de CNES desta UBS esteja associado ao código 12 (estrutura de Academia da   Saúde).<br>      (08) Instituição/Abrigo – instituições para acolhimento destinadas a   famílias e/ou indivíduos com vínculos familiares rompidos ou fragilizados, a   fim de garantir proteção integral. <br>     (09) Unidade prisional ou   congêneres – cadeia pública, colônia   agrícola, industrial ou similar, casa do albergado, centro de observação   e  hospital de custódia e tratamento   psiquiátrico.<br>      (10) Unidade socioeducativa –   base física necessária para a   organização e o funcionamento de programa de atendimento de medidas   socioeducativas.    |

*Fonte: SAS/MS.*

\* *Campo de preenchimento obrigatório.*

## 10.4 Situação/Condição

Este grupo mostra a situação ou condição do cidadão que está recebendo a(s) vacina(s), sendo possível a indicação de gestante, puérpera (exclusivo do sexo feminino) e/ou viajante.

Figura 10.4 -- Situação / Condição no momento da vacinação

![PNI_situação.png](media/image98.png)

*Fonte: SAS/MS.*

## 10.5 Imunobiológico

Este bloco de informações é utilizado para o registro da(s) dose(s) de vacina(s) aplicada(s) nos serviços de Atenção Básica. A lista dos imunobiológicos disponíveis para registro é definida pela Coordenação Geral do Programa Nacional de Imunizações (CGPNI).

Figura 10.5 -- Imunobiológicos (frente)

![PNI_imuno_1.png](media/image99.png)

*Fonte: SAS/MS.*

Figura 10.6 - Imunobiológicos (verso)

![Captura de tela 2017-10-10 16.55.05.png](media/image100.png)
*Fonte: SAS/MS.*

Para cada vacina aplicada o profissional deverá indicar a estratégia, a dose, o lote e o fabricante do imunobiológico. A estratégia e a dose obedecerão à legenda disponível no verso da ficha.

> ![](media/image2.png) **ATENÇÃO**: **exclusivamente** para o registro de aplicação de **BCG**, caso o cidadão for **comunicante de hanseníase**, deverá marcar um "X" no campo "Comun. Hansen.".

Ainda neste bloco, o profissional pode registrar **outros imunobiológicos** não constantes na listagem (até cinco por ficha), como vacinas especiais, soros e imunoglobulinas. Esses imunobiológicos devem ser descritos a partir da sua nomenclatura oficial disponibilizada pela CGPNI, observando o preenchimento do tipo de estratégia, dose, lote e fabricante.

Figura 10.7 -- Registro de aplicação de outros imunobiológicos

![Captura de tela 2017-10-10 16.56.16.png](media/image101.png)

*Fonte: SAS/MS.*

[^1]: Como este cadastro é uma extensão do CADSUS, os dados devem    garantir consistência com o Manual de Operações do CADSUS.

[^2]: Segundo a Política Nacional de Atenção Básica (BRASIL, 2017),   "adscrição de usuários" é um processo de vinculação de pessoas e/ou   famílias e grupos a profissionais/equipes, com o objetivo de ser    referência para o seu cuidado.

[^3]: MENÉDEZ, E. Modelos, saberes e formas de atenção ao padecimento: exclusões ideológicas e articulações práticas. In: \______. Sujeitos, saberes e estruturas: uma introdução ao enfoque relacional no estudo da Saúde Coletiva. São Paulo: Hucitec, 2009. p.17-70.

[^4]: MENÉDEZ, E. Modelos, saberes e formas de atenção ao padecimento: exclusões ideológicas e articulações práticas. In: \______. Sujeitos, saberes e estruturas: uma introdução ao enfoque relacional no estudo da Saúde Coletiva. São Paulo: Hucitec, 2009. p.17-70.

[^5]: Ver na íntegra Política Nacional de Saúde da Pessoa com Deficiência (2010), disponíveis em: <http://bvsms.saude.gov.br/bvs/publicacoes/>.

[^6]: Disponível em: <https://cadastro.saude.gov.br/cadsusweb/manual.pdf/>.

[^7]: Caderno de Atenção Básica (CAB) nº 13 (BRASIL, 2013); CAB nº 29 (BRASIL, 2010).

[^8]: CAB nº 13 (BRASIL, 2013); CAB nº 29 (BRASIL, 2010).

[^9]: CAB nº 29 (BRASIL, 2010).

[^10]: Manual de Especialidades em Saúde Bucal* (BRASIL, 2008), no capítulo intitulado Estomatologia. Disponível em: <http://189.28.128.100/dab/docs/portaldab/publicacoes/manual_especialidades_bucal.pdf/>.

[^11]: Guia de Recomendações para Uso de Fluoretos no Brasil* (BRASIL, 2009). Disponível em: <http://189.28.128.100/dab/docs/portaldab/publicacoes/guia_fluoretos.pdf/>.

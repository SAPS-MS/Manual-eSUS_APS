---
layout: default
title: Gestão da Garantia do Acesso
parent: Prontuário Eletrônico do Cidadão v5.2
nav_order: 14
has_children: false
has_toc: true
last_modified_date: "02/05/2023"
---


# CAPÍTULO 12 - Gestão de Filas
{: .no_toc }

## 12.1 Garantia do Acesso

Este módulo tem como objetivo criar uma lista para a gestão da garantia do acesso dos estabelecimentos de saúde a fim de garantir o atendimento dos cidadãos que buscaram o serviço de saúde, mas não obtiveram assistência imediata. 

## Sumário
{: .no_toc .text-delta }

- TOC
{:toc}



A inserção de dados no módulo de garantia do acesso pode ser feita no momento de acolhimento, a fim de proporcionar ao cidadão em momento oportuno a garantia do acesso à consultas.

Figura 12.1 Tela módulo da garantia do acesso

![](media/garantia_de_acesso_telainicial.png)
Fonte: SAPS/MS.



{: .atencao }
O cidadão que procurar a unidade com demanda urgente não pode ter seu atendimento adiado.


A inserção dos dados de um cidadão nesta lista pode ser feita por qualquer profissional da Unidade Básica. Ela deve ser feita quando, considerando o motivo da consulta do cidadão, não for possível atender naquele momento, nem for possível o agendamento. 

As informações necessárias para incluir o cidadão nesta lista são o nome completo, CPF ou CNS do cidadão. Caso ele não seja cadastrado, deve-se fazer o cadastro simplificado ou completo. Este é um campo obrigatório.

O campo "Tipo de atendimento" apresenta três tipos de atendimento como opção, sendo eles: consulta de enfermagem, consulta médica e consulta odontológica, conforme mostra a Figura 12.2. Este campo deve ser escolhido a partir do que o cidadão foi buscar na unidade naquele momento, porém não conseguiu ter acesso. 

Figura 12.2 Tipos de atendimento buscados pelo cidadão
![](media/garantia_de_acesso_tipoconsulta.png)

Fonte: SAPS/MS.


O Campo "Motivo da consulta" também é obrigatório e é um campo aberto para inserir as informações do motivo que o cidadão buscou consulta na unidade.

![](media/garantia_de_acesso_motivo.png)


Por exemplo, uma mulher que foi buscar a realização de um exame citopatológico, mas não foi possível naquele momento, e não é possível fazer o agendamento. O registro deve ser feito no módulo como consulta de enfermagem ou médica em "Tipo de atendimento" e deve-se descrever em "Motivo da consulta" que a busca envolve a realização de coleta do exame citopatológico. 

O campo "Equipe" não é obrigatório, dessa forma pode ser selecionada a equipe que o cidadão é vinculado ou não direcionar para nenhuma equipe no momento de inserção de dados na lista. Serão mostradas as equipes vinculadas aquela UBS.

![](media/garantia_de_acesso_equipe.png)


Ao adicionar todas as informações clique em ![](media/garantiaenviar.PNG) para que o cidadão entre na lista. 

A lista é exibida com as informações: Data, Cidadão (Nome, idade, CPF/CNS), telefone, equipe e tipo de atendimento, como mostra a Figura 12.3.

Figura 12.3 Lista de cidadão inseridos no módulo Garantia do acesso

![](media/garantia_lista.png)
Fonte: SAPS/MS.


Ao inserir o cidadão na listagem do módulo da garantia do acesso é possível visualizar quantas vezes ele foi inserido na listagem e o último motivo da procura.

![](media/garantia_quantidadelista.PNG)


Para retirar o cidadão da lista deve-se clicar no ícone ![](media/garantia_removerdalista.png). A remoção do registro na lista abre as seguintes opções:

**Atendido em outro estabelecimento:** usado quando o cidadão conseguiu o atendimento que pretendia na unidade em outro serviço, seja na atenção especializada, em serviços particulares, ou até mesmo em outra unidade básica, do mesmo município ou de outro. É recomendado colocar qual o outro lugar no campo Observações para que seja possível um diagnóstico situacional no futuro.

**Atendimento agendado:** usado quando o cidadão for agendado na unidade que buscou atendimento.

**Não respondeu à tentativas de contato:** usado para indicar quantas vezes foi feito contato com o cidadão. Esta opção abre o campo obrigatório "Número de tentativas de contato" feitas com o cidadão e é possível descrever quais foram os meios de comunicação utilizados. 

**Mudou-se do território:** quando o cidadão se muda do território adstrito daquela unidade e não se tem mais contato.

**Outros**: quando o motivo para a remoção da lista não foi contemplado em nenhuma das opções anteriores. Ao selecionar esta opção o campo "Observações" torna-se obrigatório.

![](media/garantia_removerlistamotivo.png)

Fonte: SAPS/MS.

Ainda é possível fazer o agendamento do cidadão no próprio módulo de gestão da garantia do acesso no ícone ![](media/garantia_agendarconsulta.png), que abrirá a opção de agendamento de consulta para um dos profissionais de saúde, como mostra a Figura 12.5

Figura 12.5 Agendamento no módulo de gestão da garantia do acesso

![](media/garantia_agendarconsulta2.png)
Fonte: SAPS/MS.

## 12.2 Cuidados Compartilhados 

Na tela de Cuidados Compartilhados, é possível visualizar a listagem de casos solicitados pelo profissional em "Solicitados por mim" e os compartilhados com este profissional em "Compartilhados comigo".

![](media/cuidadoscompartilhados.png)

Para visualizar uma discussão de caso, selecione ![](media/cuidadoscompartilhados_visualizarcaso.png), então abrirá a tela de justificativa para visualização, que é obrigatória.

![](media/cuidadoscompartilhados_jutificativa.png)

Em seguida abrirá a tela de discussão de caso.

![](media/cuidadoscompartilhados_discussao.png)
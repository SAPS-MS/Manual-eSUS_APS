---
layout: default
title: Estabilização 5.1
parent: Últimas releases
nav_order: 3.1
has_children: false
has_toc: true
last_modified_date: "13/05/2024"
---

### Versões de estabilização 5.1

### Versão 5.1.26

* Melhorias nos processamentos das fichas de Visita domiciliar e no Histórico clínico do cidadão visando performance.

### Versão 5.1.25

* Alterações e melhorias na busca de dados do Histórico clínico do cidadão visando performance.
Correção de erro ao gerar relatórios CSV na Busca ativa de vacinação utilizando a opção de filtros avançados.

### Versão 5.1.24

* Correção de cenários onde o sistema apresentava erro caso houvesse cadastro do mesmo INE em mais de um estabelecimento.

### Versão 5.1.21

* Simplificação dos campos "Atendimento fora da UBS" e "Local de atendimento" no agendamento.
* Correção na lentidão encontrada na seleção de profissionais no módulo da Agenda.
* Destaque no calendário da Agenda para datas com horários disponíveis.
* Correção no relatório CSV ao aplicar os filtros avançados, para exibir todos os imunobiológicos daquele cidadão e não apenas os que foram selecionados.
* Correção de cenário onde a lotação de estagiário era impossibilitada de imprimir solicitações de exames.
* Correção na prescrição de medicamentos onde as comboboxes não fechavam após confirmar seleção com atalhos do teclado.
* Correção da exportação da série histórica nos relatórios CSV, para voltarem a apresentar o CNS dos profissionais.
* Correção do fluxo que solicitava múltiplas vezes a Justificativa de acesso ao prontuário para um mesmo cidadão.
* Retirada do item de checkbox em branco da lista do Tipo de atendimento do Histórico clínico do cidadão.
* Correção de cenário onde o sistema apresentava uma tela branca após o login para alguns usuários.
* Correção no módulo de Agenda para agendamentos exibirem o telefone do cidadão.
* Adicionada compatibilidade com a versão 3.1 do XML do CNES.
* Inclusão do perfil de Farmacêutico para realizar prescrição de medicamentos no Atendimento individual.

### Versão 5.1.20

* Correção de cenário onde nenhuma informação era apresentada no Relatório de inconsistências caso houvesse erro ao enviar fichas.
* Correção de erro onde uma tela branca era apresentada ao navegar no módulo de Reterritorialização.
* Correção do Relatório operacional de inconsistências do Cadastro territorial para exibição correta de famílias que foram reterritorializadas.
* Correção de erro onde atendimentos realizados no aplicativo e-SUS Atenção Domiciliar para cidadãos sem CPF e sem CNS não eram apresentados no histórico clínico.
* Correção de cenário onde a idade gestacional ecográfica era apresentada diferente entre a impressão e o card de acompanhamento.
* Ajustes para exibir a data em que o atendimento foi realizado na Declaração de comparecimento do Registro tardio.
* Alterações e melhorias na busca de dados do Acompanhamento de cidadãos vinculados visando performance.
* A mensagem informativa referente a lista de CID10 e CIAP2 que aumentam o risco da gravidez apresentará as CID10 apenas para profissionais que possam preencher essa informação.
* Correção do cenário onde a idade gestacional não era exibida no card do acompanhamento de pré-natal quando acessado através do módulo do cidadão.
* Correção do cenário onde não estava sendo possível imprimir o acompanhamento de pré-natal.
* Atualizado comportamento do botão para logar no gov.br para abrir uma pop-up no sistema e não mais redirecionar a página atual.
* Correção do cenário para que o risco da gestação seja alterado somente quando preenchido por médico ou enfermeiro.

### Versão 5.1.19

* Correção de erro na sincronização com o CADSUS e edição do cidadão que gerava carregamento infinito em algumas instalações.

### Versão 5.1.18

* Correção de cenário, onde não era possível adicionar um mesmo cidadão na lista de Atenção Domiciliar por diferentes profissionais.
* Ajustes na seleção de checkbox via atalho de teclado no Histórico clínico do cidadão.
* Correção do cálculo da IG eco para considerar a data atual, anteriormente apresentada de forma fixa a data informada no resultado da USG.
* Ajustes no processo de preparação e de envio de lotes.
* Correção de cenário onde era apresentado tela branca ao tentar finalizar um atendimento com condição W78 adicionada e, posteriormente, excluída na lista de problemas e condições.
* Adicionada funcionalidade de "Copiar atividade" para o tipo de atividade "5" na Ficha de atividade coletiva.
Correção de cenário onde não era possível evoluir uma condição adicionada através do modal da Lista de problemas e condições.
* Realizados ajustes de layout visando maior visibilidade no registro de procedimentos do odontograma, além de adicionada a possibilidade de replicar procedimentos entre os dentes.
* Correção de cenário onde o histórico de resultados de exames aparecia desabilitado mesmo havendo resultados previamente registrados.

### Versão 5.1.17

* Correção de erro onde não era possível acessar o módulo de CBO em instalações com banco de dados Oracle.
Ajuste de cenário onde, ao incluir CID 10 relacionado a puerpério, o tipo do atendimento será definido como puerpério.
* Correção de erro onde, a condição W78 adicionada automaticamente na lista de problemas e condições apresentava data de início incorreta, ao invés de mostrar a mesma data de início da condição de alto risco adicionada na avaliação.
* Correção de cenário onde, ao mudar a situação de uma condição de alto risco ou desfecho na avaliação, a data selecionada era alterada para o dia atual.
* Ajustes no Histórico clínico do cidadão para apresentar o nome do estagiário que realizou o atendimento.
* Ajuste no horário de entrada da declaração de comparecimento do cidadão para considerar toda a permanência do cidadão na unidade de saúde.
* Correção de erro onde a opção para baixar impressões não estava funcionando corretamente.
* Correção de cenário onde uma tela branca era apresentada ao tentar visualizar Atendimentos domiciliares com mais de um CIAP no histórico Clínico do cidadão.
* Ajustes no Histórico clínico do cidadão para exibir a concentração dos medicamentos prescritos ao lado do seu princípio ativo.
* Correção de erro onde o campo conduta era apresentado duas vezes no histórico de atendimentos de CEO.
* Incluído comportamento de carregamento no botão "Adicionar" da Lista de atendimentos.
* Correção no Histórico clínico do cidadão ao tentar visualizar registros de Atendimento domiciliar sem procedimento.
* Correção do cenário em que um mesmo imóvel era listado incorretamente múltiplas vezes no módulo de Reterritorialização.
* Correção de erro onde o botão de importar CNES do módulo de Unidades de saúde não estava funcionando.
* Melhoria no layout dos Exames solicitados no Histórico clínico do cidadão.
* Correção de erro onde não era possível finalizar atendimentos de pré-natal em instalações com banco de dados Oracle.
* Ajustes no processamento de dados para o acompanhamento de cidadãos vinculados ocorrer apenas no horário configurado para geração de lotes e processamento de fichas.
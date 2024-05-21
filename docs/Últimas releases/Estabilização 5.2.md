---
layout: default
title: Estabilização 5.2
parent: Últimas releases
nav_order: 2.1
has_children: false
has_toc: true
last_modified_date: "13/05/2024"
---

### Versões de estabilização 5.2

### Versão 5.2.33

* Correção de erro onde, por questões de fuso horário, os relatórios gerenciais contabilizavam atendimentos do dia 1 como do mês anterior.
Funcionalidade para impressão de comprovantes de agendamentos do cidadão.
* Correção de cenário que apresentava erro de conexão de servidor ao acessar o * Acompanhamento de Condições de Saúde.
* Criação do fluxo que envia um e-mail para o cidadão quando um agendamento for registrado.
* Correção da dose de Reforço do imunobiológico "Meningo C", que não estava sendo apresentada no Calendário Vacinal do grupo-alvo "Criança".
* Disponibilização do registro de aplicações do imunobiológico COVID-19 MODERNA - SPIKEVAX.
* Ajustes de cenário onde o Marcador de Consumo Alimentar registrado no PEC não vinculava ao atendimento em consultas de pré-natal com agendamentos.
* Atualização da tabela de procedimentos SIGTAP para a competência de 09/2023.

### Versão 5.2.32

* Correção de erro onde reservas estavam sendo salvas com o motivo "Outros" independentemente da opção selecionada.
* Atualização das regras de cadastro do cidadão no módulo de Cidadão e na Ficha de cadastro individual para os campos de Orientação Sexual e Identidade de Gênero.
* Correção de erro onde fichas de Atendimento individual ou odontológico importadas de outros sistemas não eram apresentadas no Histórico clínico do cidadão.
* Inclusão do campo de Anotações na visualização do Histórico de visita domiciliar quando a origem for aplicativo e-SUS Território.
* Correção de cenário em que o botão de Buscar cidadãos não estava funcionando no Acompanhamento de condições de saúde.
* Criação dos recursos de acesso para o módulo do Cuidado compartilhado.
* Correção de tela branca no Histórico de vacinação caso o atendimento tenha sido importado de outros sistemas.
* Correção de erro onde não estava sendo possível recadastrar o CNS de um profissional sem lotações ativas.
* Atualizações globais de regras de vacinação para compatibilidade com as políticas nacionais vigentes.
* Correção de cenário no módulo de Acompanhamento de território, onde ocorria duplicação na visualização devido a logradouros com nomes muito semelhantes.
* Correção de cenário onde um erro era mostrado no alerta ao tentar salvar um Atendimento de observação com alguma prescrição de medicamentos cadastrada.

### Versão 5.2.31

* Inclusão do imunobiológico "Influenza Trivalente" nos envios à RNDS via RIA-C.

### Versão 5.2.30

* Correção de cenário onde algumas lotações estavam sendo inativadas incorretamente ao importar o CNES.

### Versão 5.2.29

* Correção de erro onde algumas famílias apareciam duplicadas no módulo de Acompanhamento do território.
* Inclusão do modo assíncrono nos Relatórios gerenciais de atendimento, cuidado compartilhado e vacinação, para que seja possível sair da página e utilizar o sistema normalmente enquanto a busca é realizada.
* Correção de cenário em que, ao tentar finalizar um atendimento de pré-natal, era apresentado o erro de resultados não únicos.
* Melhorias no módulo de CDS na Ficha de cadastro individual visando performance.
* Correção de erro que causava lentidão e travamento no processamento e envio de dados em algumas instalações, sendo necessário reiniciá-las.
* Remoção da conduta "Agendamento para NASF" e inclusão da nova opção "Agendamento para eMulti" nos desfechos de Atendimentos individuais e odontológicos.
* Correção de cenário onde um erro era apresentado ao tentar atualizar o endereço de um cidadão estrangeiro.

### Versão 5.2.28

* Refatoração na aba de "Recebimento" do módulo de "Transmissão de dados", possibilitando a visualização da origem dos lotes recebidos e a filtragem do histórico de lotes por período e por tipo origem de recebimento.
* Adição de perguntas e respostas no topo do Termo de uso.
* Correção de cenário que fazia com que registros do Histórico clínico do cidadão ficassem indisponíveis durante o processamento de relatórios.
* Inclusão de novas doses de vacinação, grupo de atendimento, regras e imunobiológicos COVID-19 Moderna - Spikevax Bivalente e VPC15, além da inativação de imunobiológicos não mais aplicados na APS.
* Correção de cenário onde não estava sendo exibido o nome do exame da ficha de Síndrome neurológica por Zika / Microcefalia no Histórico clínico do cidadão.
* Correção de um cenário em que, mesmo após a atualização das credenciais de acesso ao serviço de documentos digitais, o PEC continuava utilizando as credenciais antigas para comunicação com este serviço.

### Versão 5.2.27

* Correção de cenário que impedia a exclusão de agendamentos no módulo de Registro Tardio.
* Adicionada restrição para que apenas estabelecimentos da atenção primária possam acessar a Busca ativa de vacinação.
* Correção de cenário que impedia a geração de Prescrição digital para cidadãos naturalizados.
* Correção de cenário que impedia a finalização do atendimento, indicando a existência de uma CIAP2 cadastrada.
* Disponibilização do imunobiológico "104 - Vacina dengue atenuada (DNG)" para registro via CDS e Atendimentos de vacinação.

### Versão 5.2.26

* Adição do campo “Produções”, que possibilita visualizar separadamente o que é produção do próprio profissional e da sua equipe, nos Relatórios gerenciais de atendimentos, vacinação e absenteísmo.
* Correção de erro onde, ao tentar iniciar uma gestação, era apresentado um erro indicando que já existia uma condição no prontuário.
* Possibilidade de profissionais que pertencem à eMulti pesquisarem, em uma única consulta, a sua produção em todos os estabelecimentos nos relatórios Gerenciais de atendimentos e absenteísmo.
* Adicionadas as possibilidades de realizar um Atendimento no registro tardio, mesmo que haja um Atendimento de vacinação ou uma Escuta inicial com data posterior a ele.
* Correção de cenário em que, ao tentar finalizar um Atendimento de pré-natal, era apresentado o erro de resultados não únicos.
* Correção de erro que causava lentidão e travamento em algumas instalações, sendo necessário reiniciá-las.
* Correção de cenário em que alguns dados de Registros tardios desapareciam da impressão do Histórico clínico do cidadão após o processamento.

### Versão 5.2.24

* Ao selecionar um imunobiológico na Busca ativa de vacinação, apenas as doses pertinentes a ele aparecerão no campo "Dose" ao lado.
* Correção de cenário em que um cidadão era cadastrado através da edição de um cidadão no Registro tardio e o cidadão editado não era atualizado automaticamente.
* Implementação de registro de auditoria para a exclusão de Atendimentos de vacinação.
* Correção de cenário em que o relatório CSV da Busca ativa de vacinação não apresentava todos os imunobiológicos dos cidadãos ao aplicar o filtro avançado "Grupo de atendimento".
* Correção de cenário em que uma pessoa grávida estava em Atendimento de pré-natal e, ao iniciar um Atendimento de observação, não era possível concluí-lo.
* Habilitados os envios de Prescrições de medicamentos e de Atestados para a RNDS.

### Versão 5.2.23

* Correção de erro que ocorria ao incluir um cidadão recém-criado na lista de registro tardio.
* Correção de cenário onde os dados do relatório CSV não correspondiam aos filtros aplicados na Busca ativa de vacinação.
* Implementação da ordenação por imunobiológico e dose no relatório CSV da Busca ativa de vacinação.
* Correção de cenários que impediam a finalização de atendimentos de pré-natal.
* Adição das opções "Aplicação", "Glóbulo" e "UI" (unidade internacional) no campo de unidade de medida da Prescrição de medicamentos.
* Correção de cenário em que uma tela branca era apresentada ao acessar um histórico de pré-natal sem CID10.
* Adição da opção "Visualizar informações do cidadão" na Lista de atendimento e na Agenda permitindo que os agentes comunitários de saúde tenham acesso a alguns dados do prontuário.
Inclusão dos registros de evoluções do Cuidado compartilhado no Histórico clínico do cidadão.

### Versão 5.2.22

* Correção de cenário onde não estava sendo possível finalizar atendimentos em algumas situações.

### Versão 5.2.21

* Correção de cenário em que os cidadãos pertencentes a equipes vinculadas não eram apresentados nos Relatórios operacionais.
* Correção da ordenação dos dados do cidadão no relatório em CSV das vacinas do calendário vacinal e de Covid-19 da Busca ativa de vacinação.
* Adicionada a funcionalidade de marcar todos os medicamentos para impressão nas Prescrições de medicamentos.
* Ajustes na ordenação da lista de medicamentos da Prescrição para apresentar os medicamentos mais recentes no topo.
* Correção de cenário onde ao atender uma cidadã com cadastro unificado que constava na lista de atendimentos não era possível iniciar uma gestação.
* Implementação de indicativo de medicamentos com termo de uso e consentimento na Prescrição de medicamentos.

### Versão 5.2.20

* Correção de erro onde não era possível visualizar imóveis do logradouro no Acompanhamento do território.
Implementação da funcionalidade que permite visualizar os registros não finalizados no Registro tardio de atendimento.
* Correção de cenário onde não era possível processar relatórios de atendimentos com evoluções registradas no Cuidado compartilhado em algumas instalações.
* Restrição adicionada no Registro tardio de atendimento para não ser possível adicionar ou editar um cidadão se este já possuir um atendimento mais recente registrado.
* Correção na ordenação da lista de cidadãos encontrados para considerar o nome social na Busca ativa de vacinação.
* Disponibilização do filtro de idade mínima de zero anos no campo da faixa etária da Busca ativa de vacinação.
* Implementação de mensagens e de marcadores para identificar atendimentos não finalizados no Registro tardio de atendimento.
* Correção de erro em que o processamento e o envio de atendimentos individuais e odontológicos contendo prescrições de medicamentos não estavam sendo realizados adequadamente.



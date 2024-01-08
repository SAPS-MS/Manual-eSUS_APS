---
layout: default
title: Certificado https - Linux
parent: Apoio a Implantação
nav_order: 2
has_children: false
has_toc: true
last_modified_date: "25/09/2023"
---

# Fluxo para solicitação de Adesão ao GOV.BR:

Caso seu município não faça parte da Rede GOV.BR ainda, o prefeito precisará realizar a adesão através da Plataforma Rede GOV.BR, seguindo os passos abaixo:

![](media/010.png)

O profissional responsável deverá preencher o formulároi de login único:

![](media/011.png)

Realizar a credencial de teste para login único:

![](media/012.png)

Após o município ser liberado pelo gov.br para utilização da funcionalidade, você precisará habilitar o botão para login na tela inicial do sistema. Você receberá um "ClientID" e um "ClientSecret", que devem ser inseridos no arquivo de configuração da instalação do PEC, chamado de "application.properties".

Diretório: e-SUS\webserver\config\

![](media/013.png)


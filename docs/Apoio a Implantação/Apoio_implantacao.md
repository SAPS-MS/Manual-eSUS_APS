---
layout: default
title: Apoio a Implantação
parent: Apoio a Implantação
nav_order: 2
has_children: false
has_toc: true
last_modified_date: "25/09/2023"
---

# Apoio a Implantação
{: .no_toc }

<style>
    p{
        text-align:justify;
        font-family:Verdana;
        font-size:12px;
    }    
</style>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

<script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.3/umd/popper.min.js" integrity="sha384-ZMP7rVo3mIykV+2+9J3UJ46jBk0WLaUAdn689aCwoqbBJiSnjAK/l8WvCWPIPm49" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/js/bootstrap.min.js" integrity="sha384-ChfqqxuZUCnJSK3+MXmPNIyE6ZbWh2IMqE241rYiqJxyMiZ6OW/JmZQ5stwEULTy" crossorigin="anonymous"></script>



<nav>
  <div class="nav nav-tabs" id="nav-tab" role="tablist">
    <a class="nav-item nav-link active" id="nav-cenario-tab" data-toggle="tab" href="#nav-cenario" role="tab" aria-controls="nav-cenario" aria-selected="true">Cenário</a>
    <a class="nav-item nav-link" id="nav-ambiente-tab" data-toggle="tab" href="#nav-ambiente" role="tab" aria-controls="nav-ambiente" aria-selected="false">Preparar Ambiente</a>
    <a class="nav-item nav-link" id="nav-download-tab" data-toggle="tab" href="#nav-download" role="tab" aria-controls="nav-download" aria-selected="false">Download</a>
    <a class="nav-item nav-link" id="nav-install-tab" data-toggle="tab" href="#nav-install" role="tab" aria-controls="nav-install" aria-selected="false">Instalar e Configurar</a>
    <a class="nav-item nav-link" id="nav-chave-tab" data-toggle="tab" href="#nav-chave" role="tab" aria-controls="nav-chave" aria-selected="false">Contra-chave</a>
    <a class="nav-item nav-link" id="nav-xml-tab" data-toggle="tab" href="#nav-xml" role="tab" aria-controls="nav-xml" aria-selected="false">XML</a>
  </div>
</nav>

<div class="tab-content" id="nav-tabContent">
  <div class="tab-pane fade show active" id="nav-cenario" role="tabpanel" aria-labelledby="nav-cenario-tab">    
  <br>
  <h4>Definição de Cenário:</h4><br>
  <p>Antes de se efetivamente realizar a implantação do Prontuário Eletrônico do Cidadão (PEC) no ambiente de produção, deve-se preliminarmente, realizar o mapeamento do ambiente, identificar necessidades e de acordo com o cenário proposto, implementar ajustes técnicos de acordo com as especificidades de cada cenário. Abaixo, segue detalhamento técnico de dois tipos principais de arquiteturas: <b>Centralizada e Descentralizada.</b></p>

  <ul>    
      <li>Arquitetura Descentralizada:</li>
      <br>
      <p>Nesta topologia, uma instalação do e-SUS APS é <b>interna e exclusiva</b> de um determinado estabelecimento de saúde (UBS). Isto significa, que temos um PEC instalado localmente neste ambiente e a partir de uma rede compartilhada, é possível que computadores internos a esta rede posssam acessar simultaneamente aquela instalação e usufruir dos recursos compartilhados daquela instalação. Abaixo, segue ilustração do cenário proposto:</p>
      <br>
      <br>

  <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="1" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>    
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-100" src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/pec_descentralizado.PNG" alt="Primeiro Slide">      
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/pec_descentralizado_02.PNG" alt="Segundo Slide">
      </div>    
  </div>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Anterior</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Próximo</span>
    </a>    
  </div>
      <br>
      <li>Arquitetura Centralizada:</li>
      <br>
      <p>Ao contrário da topologia descentralizada, na arquitetura centralizada, uma instalação do e-SUS APS é <b>externa e compartilhada</b>, podendo vários estabelecimentos de saúde (UBSs), terem acesso simultâneo e em tempo real a aplicação, para o atendimento clínico do paciente; nesta modalidade, tem-se de forma evidente, acesso ao Prontuário Único do Cidadão, no nível municipal. Abaixo, segue ilustração do cenário proposto:</p>
      <br>
      <br>
      <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/pec_centralizado.PNG">
      <br>
      <br>
      <h4>Considerações:</h4>
      <br>
      <p>A adoção de uma arquitetura ou outra, irá depender basicamente da necessidade do município. Lembrando-se que quanto mais estabelecimentos de saúde conectados a uma instalação PEC, mais robusto deverá ser o hardware que sustentará aquele ambiente, sob risco da aplicação declinar em termos de performance e apresentar lentidão na sua operacionalização.</p>
  </ul>
</div>

  <div class="tab-pane fade" id="nav-ambiente" role="tabpanel" aria-labelledby="nav-ambiente-tab">
  
  <h1>Prepação do Ambiente:</h1>
  <br>
  <p>Esta etapa diz respeito ao provimento do aparato tecnológico que sustentará o ambiente que receberá o Prontuário Eletrônico do Cidadão (PEC). Tal ambiente poderá ser sob infraestrutura própria ou utilizando soluções de computação em nuvem. Definem-se informações relevantes, como: hardware, sistema operacional, banco de dados, parametrização da JVM, etc.</p>  

  <h4>Sistema Operacional:</h4>
  <br>
  <p>O desenvolvimento do e-SUS APS é multiplataforma, ou seja, é possível ser instalado em diferentes sistemas operacionais (SO), inclusive distribuições GNU/Linux, como o Ubuntu Linux (www.ubuntu.org), que é um software livre, portanto sem custos de licença ou aquisição.</p>
  
  <table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Sistemas Operacionais Compatíveis:</th>
      <br>            
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Microsoft Windows</td>
      <td>
          Windows 7, Windows 8, Windows 10, Windows Server<br>
	    </td>      
    </tr>   
     <tr>      
      <td>GNU/LINUX</td>
      <td>
          Debian, Ubuntu, Red Hat, CentOS<br>
	    </td>      
    </tr>     
  </tbody>
</table>

  <h4>Instalação do JAVA:</h4>
  <br>
  <p>A instalação na plataforma Microsoft Windows vem com pacote Java embutido, caso seja necessária uma instalação personalizada deve ser realizada a instalação do pacote Java 7. Para plataformas Linux recomenda-se seguir as instruções do arquivo “LEIA-ME” incluso no arquivo (compactado) de instalação.</p>
  <br>
  <a href="https://www.oracle.com/java/technologies/downloads/#java8" target="_blank">Download do Java</a>
  <br>
  <br>
  <h4>Especificações de Banco de Dados:</h4>

  <br>
    <p><b>PostgreSQL -</b> a partir da versão 2.0, este banco vem configurado por padrão na instalação do sistema. Pode ser utilizado em UBS com servidor local ou para instalações centralizadas. É recomendado para qualquer tipo de instalação.
    <br>
    <br>
    O banco de dados PostgreSQL é um software livre, portanto, sem custo de licença ou aquisição. Para mais informações acesse: http://www.postgresql.org/. É recomendado o uso da versão 9.6 ou superior.
    <br>
    <br>
    <b>Banco de Dados Oracle</b> - optando por este banco de dados, podem ser utilizadas as versões Oracle XE 11g, Oracle Standard Edition 11g ou Oracle Enterprise Edition 11g.
    </p>  
  <h4>Especificações técnicas de hardware, por acessos simultâneos:</h4>
  <br>
  <b>Centralizadores Municipais:</b>
  <br>
  <br>
<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Requisitos mínimos para a instalação do e-SUS APS em Centralizadores Municipais:</th>            
    </tr>
  </thead>

  <tbody>
    <tr>      
      <td>Ambiente</td>    
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>16GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 13000 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>1 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>    
    <tr>      
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -
XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=500M"</td>      
    </tr>
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>
     
     
  </tbody>

</table>

  <br>
  <b>Centralizadores Estaduais:</b>
  <br>
  <br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Requisitos mínimos para a instalação do e-SUS APS em Centralizadores Estaduais:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>      
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>32GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 13000 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>3 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec
Parametrização PostgreSQL: PGConfig 2.0
Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=500M"</td>      
    </tr>        
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>
     
     
  </tbody>
</table>

  <br>
  <b>Para 40 usuários simultâneos:</b>
  <br>
  <br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Ambiente para até 40 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
  <tr>      
      <td>Usuários simultâneos</td>      
      <td>40</td>
    </tr>
    <tr>      
      <td>Ambiente</td>      
      <td>Servidor único para aplicação e banco de dados</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>8GB  Barramento DDR4  Mínimo 1600MHz</td>      
    </tr>    
    <tr>      
      <td>Processador: </td>
      <td>Quad Core 2.20 GHz  Pontuação mínima de 2500 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>      
      <td>Disco:</td>
      <td>100 GB  Velocidade de escrita mínima 80 MB/seg  Velocidade de leitura mínima 350 MB/sec</td>      
    </tr>            
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

  <br>
  <b>Para 100 usuários simultâneos:</b>
  <br>
  <br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Ambiente para até 100 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>      
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>8GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Quad Core 2.20 GHz - Pontuação mínima de 5000 pontos no PassMark/CPUBenchmark  </td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>120 GB - Velocidade de escrita mínima 200 MB/seg - Velocidade de leitura mínima 350 MB/sec</td>      
    </tr>        
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

  <br>
  <b>Para 1000 usuários simultâneos:</b>
  <br>
  <br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Ambiente para até 1000 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>      
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>8GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>16GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 10000 pontos no PassMark/CPUBenchmark </td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>750 GB - Velocidade de escrita mínima 400 MB/seg - Velocidade de leitura mínima 700 MB/sec</td>      
    </tr>   
    <tr>      
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=300M"</td>      
    </tr>
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

  <br>
  <b>Para 2500 usuários simultâneos:</b>
  <br>
  <br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Ambiente para até 2500 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>      
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>16GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>16GB - Barramento DDR4 - Mínimo 1600MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 13000 pontos no PassMark/CPUBenchmark  </td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>1 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>   
    <tr>      
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -
XX:MaxMetaspaceSize=1024M -XX:ReservedCodeCacheSize=300M"</td>      
    </tr>
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>

  <br>
  <b>Para 4000 usuários simultâneos:</b>
  <br>
  <br>

<table class="table table-striped">
  <thead class="thead-dark">
    <tr>
      <th style ="text-align:center;" scope="col" colspan="2">Ambiente para até 4000 usuários simultâneos:</th>            
    </tr>
  </thead>
  <tbody>
    <tr>      
      <td>Ambiente</td>      
      <td>2 servidores (aplicação e banco de dados)</td>
    </tr>
    <tr>      
      <td>Sistema Operacional</td>
      <td>Ubuntu Server 64 bits ou Windows Server 64 bits</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Aplicação:</td>
      <td>16GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Memória RAM - Banco de Dados:</td>
      <td>32GB - Barramento DDR4 - Mínimo 2133MHz</td>      
    </tr>
    <tr>      
      <td>Processador: </td>
      <td>Octa Core 2.20 GHz - Pontuação mínima de 15000 pontos no PassMark/CPUBenchmark</td>      
    </tr>
    <tr>      
      <td>Disco Aplicação:</td>
      <td>100 GB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>
    <tr>      
      <td>Disco BD:</td>
      <td>2 TB - Velocidade de escrita mínima 700 MB/seg - Velocidade de leitura mínima 1000 MB/sec</td>      
    </tr>   
    <tr>      
      <td>Parametrização do PostgreSQL:</td>
      <td>PGConfig 2.0 Parametrização set "JAVA_OPTS=-Xms4096M -Xmx10240M -XX:MetaspaceSize =512M -</td>      
    </tr>
     <tr>      
      <td>Banco de Dados PostgreSQL:</td>
      <td>Versão mínima: 9.6</td>      
    </tr>
     <tr>      
      <td>Banco de Dados Oracle: </td>
      <td>Versão mínima: 12.2c</td>      
    </tr>    
     
  </tbody>
</table>  
</div>

  
  <div class="tab-pane fade" id="nav-download" role="tabpanel" aria-labelledby="nav-download-tab">  
    <h2>Download do e-SUS PEC:</h2>
    <br>
    <p>O Prontuário Eletrônico do Cidadão (PEC), é multiplataforma e compatível com os sistemas operacionais: <b>Microsoft Windows e GNU/Linux</b>, arquitetura x64.
    <br>
    <br>
    Para download da aplicação, basta acessar o seguinte endereço eletrônico: https://sisaps.saude.gov.br/esus/
    <br>
    <br>
    Clicar na opção "Download" no canto superior direito e selecionar a versão desejada:
    <br>
    <br>
    <img src ="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/download.png">
    <br>
    <br>
    </p>  
  </div>

  <div class="tab-pane fade" id="nav-install" role="tabpanel" aria-labelledby="nav-install-tab">
    <h1>Instalação do PEC:</h1>
    <br>
    <br>
    A instalação do e-SUS PEC seguirá conforme descrição dos passos abaixo:    
    <br>
    <h3>Verificando a versão do JAVA:</h3>
    <br>
    <br>
    <p>Após o download do instalador do e-SUS APS PEC em sua versão mais atual, o profissional deve validar se o servidor possui o Java 8 instalado. A verificação quanto a instalação e versão do java pode ser confirmada no prompt de comando no Windows, com o comando java -version. Caso não esteja instalado, o Java 8 de 64 bits pode ser obtido através do seguinte link: Java SE Runtime Environment 8 Downloads.
    <br>
    <br>
    <img src ="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/java_version.gif">
    <br>
    <br>
    Para a nova versão do e-SUS APS, os passos para a instalação são semelhantes em ambos sistemas operacionais (Windows e Linux). Antes de iniciar a instalação é necessário validar se o usuário logado no computador possui privilégios de administrador.
    Para a execução do arquivo de extensão .jar, basta que o profissional dê um duplo clique no arquivo. Caso a execução do arquivo não ocorra com o duplo clique, a execução deverá ser realizada via linha de comando, executado em modo de interface gráfica. Abaixo são apresentadas as etapas de instalação conforme o tipo de execução do arquivo realizada.
    <br>
    <br>
    <b>Instalação do sistema através do duplo clique no arquivo instalador</b>
     Após o duplo clique no arquivo instalador, a interface gráfica (modal/wizard) será aberta com as 6 etapas da instalação, conforme as imagens e descrições apresentadas a seguir.
    <br>
    <br>
    Após duplo clique na aplicação, aparecerá a tela abaixo: 
    <br>
    <br>
    <img src ="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/instalacao_esus.PNG">
    <br>
    <br>
    Selecione o tipo de instalação: Produção ou Treinamento.
    <br>
    <br>
    <img src ="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/tipo_instalacao.PNG">
    <br>
    <br>
    Informe se possui um banco de dados instalado e caso positivo, informe a "URL da instalação", "usuário" e "senha"; caso não possua, assinale "não" e marque a opção de restauração do banco de dados, caso exista um  backup existente:
    <br>
    <br>
    <img src ="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/possui_db.PNG">
    <br>
    <br>
    Verifique o resumo da instalação e clique em "instalar":
    <br>
    <br>
    <img src ="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/resumo_instalacao.PNG">
    <br>
    <br>
    Aguarde a instalação do PEC:
    <br>
    <br>
    <img src ="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/instalacao.PNG">
    <br>
    <br>
    E conclua a instalação clicando em "Finalizar":
    <br>
    <br>
    <img src ="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/instalacao_concluida.PNG">
    <br>
    <br>
    Aguarde o serviço da apliação e banco de dados assumirem o status de "Em execução" e digite o endereço padrão da instalação, à definição das configurações iniciais:
    <br>
    <br>
    Endereço padrão da instalação do e-SUS PEC: https://localhost:8080/esus
    <br>
    <br>
    <img src ="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/nome_instalacao.gif">
    </p>
  </div>

  <div class="tab-pane fade" id="nav-chave" role="tabpanel" aria-labelledby="nav-chave-tab">
    
  <h2>Novo fluxo para geração de contra-chave e-SUS APS:</h2>  
  <br>

  <p>A partir do dia <b>11/05/2021</b> a geração de contra-chave para o sistema e-SUS APS, exigirá uma segunda etapa de validação! O técnico responsável pela instalação solicitará ao detentor do <b>CNPJ do Fundo Municipal de Saúde (FMS)</b> a geração de um <b>token</b>, o qual será gerado a partir 
  da plataforma e-GESTOR, utilizando-se o CNPJ e a senha do FMS.</p>
  <br>
  <b>1ª Etapa:</b>
  <br>
  <br>
  <p>O detentor do CNPJ do Fundo Municipal de Saúde (FMS) deverá acessar a plataforma e-Gestor, a partir do endereço eletrônico https://acesso-egestoraps.saude.gov.br/login e se autenticar conforme tela abaixo: 
    <br>
    <br>
    <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/gerar_token.PNG">
    <br>
    <br>
    Na tela seguinte, clicar em “Instalação/Atualização PEC e-SUS APS”: 
    <br>
    <br>
    <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/gerar_token_2.PNG">
    <br>
    <br>
    O responsável deverá selecionar o campo “Gestor” e o “Motivo” à geração do token. Em 
    seguida, clicar em “Gerar Código”: 
    <br>
    <br>
    <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/gerar_token_3.PNG">
    <br>
    <br>
    O sistema emitirá alerta de “Código de autenticação gerado com sucesso”: 
    <br>
    <br>
    <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/gerar_token_4.PNG">
    <br>
    <br>
    Na guia “Códigos Gerados”, será possível visualizar o token que deverá ser repassado ao técnico responsável pela instalação e-SUS APS:
    <br>
    <br>
    <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/gerar_token_5.PNG">
    <br>
    <br>
    <b>OBS.: O token gerado terá a validade de 24 horas. Após este prazo, será necessário novo 
      código para geração da contra-chave.</b>
  </p>
  <br>
  <p><b>2ª Etapa:</b>
  De posse da chave gerada pelo responsável do FMS, o técnico da instalação acessará o “Gerador de contra-chave” a partir do seu perfil: 
  <br>
  <br>
  <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/contra-chave-1.PNG">
  <br>
  <br>
  Em seguida, deverá inserir o token gerado e clicar em “Liberar Acesso”: 
  <br>
  <br>
  <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/contra-chave-2.PNG">
  <br>
  <br>
  Na tela seguinte, informar a chave de instalação, para então conseguir gerar a contra-chave: 
  <br>
  <br>
  <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/contra-chave-3.PNG">  

  </p>
  </div>
  
  <div class="tab-pane fade" id="nav-xml" role="tabpanel" aria-labelledby="nav-xml-tab">
    <h1>Gerar XML - e-GESTOR AB:</h1>
    <br>
    <p>Desde a versão 5.0 do Prontuário Eletrônico do Cidadão (PEC), a geração do XML para importação no PEC, não é mais feita via <b>Portal CNES</b>, devendo ser feita exclusivamente via e-GESTOR AB, utilizando o perfil de Gestor Municipal de Saúde, conforme seguem as etapas abaixo: </p>    
    <br>
    <b>1º Etapa:</b>
    <br>
    <br>
    <p>Acessar o e-GESTOR AB no seguinte endereço eletrônico: https://acesso-egestoraps.saude.gov.br/login. O Gestor Municipal deverá se autenticar utilizando suas credenciais GOV.BR, para acesso ao serviço:
    <br>
    <br>
    <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/egestor_ab.PNG">
    <br>
    <br>
    <b>2º Etapa:</b>
    <br>
    <br>
    No painel "Gestor Municipal", o responsável deverá clicar em "XML-ESUS-APS" e em seguida, escolher um dos dois tipos de XML disponíveis: <b>XML v.2.1 e XML v.3.0.</b> A versão 3.0 é compatível apenas com versões iguais ou superiores ao PEC 5.0:
    <br>
    <br>
    <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/egestor_ab_1.PNG">
    <br>
    <br>
    <b>3º Etapa:</b>
    <br>
    <br>
    Na animação abaixo, é possível visualizar a geração do XML para PEC:
    <br>
    <br>
    <img src="https://raw.githubusercontent.com/SAPS-MS/Pilotos/main/docs/Apoio%20a%20Implantacao/media/gerar_xml.gif">
    </p>
  </div>

</div>


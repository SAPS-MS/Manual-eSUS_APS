**MINISTÉRIO DA SAÚDE**<br>
Secretaria de Atenção Primária à Saúde<br>
Departamento de Saúde da Família<br>
Coordenação-Geral de Informação da Atenção Primária<br>

**e-SUS Atenção Primária à Saúde**<br>
PRONTUÁRIO ELETRÔNICO DO CIDADÃO – PEC<br>
MANUAL DE USO<br>

### Orientações Gerais:

O conteúdo deste manual foi elaborado utilizando Markdown. Orientações em relação a utilização deste método de escrita pode ser acessado em [Markdown Guide](https://www.markdownguide.org/basic-syntax/).

O template utilizado neste manual é o [Just the Docs](https://pmarsceill.github.io/just-the-docs/). Para maiores informações e customização, acesse o repositório no GitHub [Just the Docs](https://github.com/pmarsceill/just-the-docs).

### Estrutura:

O manual está organizado em capítulos. Cada arquivo `.md` contém um capítulo. Atualmente o manual é composto por 11 capítulos. O arquivo `index.md` é a página principal de acesso do manual.

O arquivo `_config.yml` contém as configurações de funcionamento do template atualmente utilizado. Altere este arquivo apenas se souber o que está fazendo.

Os arquivos de pec_imagem devem ser gravados na pasta `\media\`, de preferência em formato `.png`.

A pasta `\_sass\` contém os arquivos de customização (`.scss`), que podem ser realizados no esquema de cores (`\color_schemes\`), seja em customizações em geral (`\custom\`)

### Atualizações:

As atualizações dos manuais do e-SUS APS devem observar as seguintes premissas, observando o funcionamento da [Política de Controle de Versão do Sistema e-SUS APS](https://cgiap-saps.github.io/e-SUS-APS-v.4.1/00_base_conceitual/#2-pol%C3%ADtica-de-controle-de-vers%C3%A3o-do-sistema-e-sus-aps).

- **Versões de manutenção correção (*revision*):** Em caso de atualização de conteúdo em versões de correção, manter a atualização no projeto de manual da versão de melhorias atual.

- **Versões de melhoria (*minor*) e novidades (*major*):** os manuais destas versões precisam ter projetos independentes no GitHub. Para isto é necessário duplicar a versão anterior e continuar as atualizações.

#### Baixando o projeto
Utilize o [GitHub Desktop](https://desktop.github.com/) para baixar o projeto em seu computador. Após a instalação, faça o *login* na sua conta GitHub. Escolha o projeto e selecione a opção `Clone`. O GitHub Desktop irá salvar uma cópia do projeto no seu computador.

#### Atualização de conteúdo:

Utilize o [Atom](https://atom.io/) para realizar as edições dos arquivos e os respectivos envios (também conhecido como *commit*). É possível realizar todas as operações de *commit* a partir do Atom. Para isto é necessário ativar o pacote de integração do GitHub disponível no próprio Atom (menu `Packages` > `GitHub` > `Toggle GitHub Tab`). Após configurar sua conta GitHub no Atom é necessário clicar na opção `Git` no canto inferior direito do Atom. Será apresentado uma aba com informações relacionadas ao repositório em que você estará trabalhando, os arquivos que foram identificados com alguma alteração e as opções de *commit*. Não esqueça de salvar as alterações antes de realizar o *commit*. Após salvar, os arquivos alterados estarão no bloco `Unstaged Changes`. Clique na opção `Stage All` e os arquivos estarão prontos para serem enviados para o repositório no GitHub. Clique em `Commit to main` para confirmar as alterações no arquivo.

> *Sempre que for realizar uma atualização de conteúdo é desejável que inclua um resumo das alterações na descrição do commit. Isto facilitará o entendimento da alteração realizada por outros usuários do repositório.*

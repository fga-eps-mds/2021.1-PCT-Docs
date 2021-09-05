# Guia de Contribuição

## Como contribuir?

Se você é um **usuário externo** ao time de desenvolvimento do projeto "Povos e Comunidades Tradicionais" (PCTs) e quer contribuir com a nossa proposta, você deve fazer um **fork** do repositório e seguir os passos a frente. Para quem já faz parte do nosso time de desenvolvimento, basta seguir esses passos:

1. Criar sua [_issue_](#política-de-issues)
1. Criar uma [_branch_](#política-de-branchs)
1. Fazer seus [_commits_](#política-de-commits)
1. Abrir um [_Pull Request_](#política-de-pull-requests)

---

## Política de _Issues_

* As _issues_ devem possuir um nome simples que descreva com poucas palavras o seu propósito;
* A descrição da _issue_ deve relatar mais a funcionalidade ou _bug_ a ser solucionado. Não é obrigatório inserir uma descrição se o nome da _issue_ já consegue descrever bem o objetivo, mas nós recomendamos colocar sempre :)
* Lembre-se sempre de identificar a _issue_ com as _**labels**_ referentes. Isso ajuda o nosso trabalho na hora de mapear quais são as demandas de cada área do projeto.

### _Issues_ para novas funcionalidades

* Novas funcionalidades devem ser descritas como _user stories_, conforme a [metodologia]() aplicada no nosso projeto;
* Essas _issues_ devem ser acompanhadas de uma lista de critérios de aceitação que garantem que ao implementar o objetivo será atendido, tanto em termos de funcionalidade, usabilidade, design e qualidade de código;
* No nosso repositório nós já disponibilizamos um [template básico de US](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/.github/ISSUE_TEMPLATE/user_story_template.md) para essas _issues_, com alguns critérios comuns a maioria das funcionalidades.
* Para melhor identificar essas _issues_ o nome deve seguir o seguinte padrão:

    > US - Nome da Issue

### _Issues_ para histórias técnicas

* Histórias técnicas devem ser descritas conforme o padrão definido na [metodologia]() desse projeto;
* Também há um template básico para as histórias técnicas, [template TS](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/.github/ISSUE_TEMPLATE/technical_story_template.md)
* Para melhor identificar essas _issues_ o nome deve seguir o seguinte padrão:

    > TS - Nome da Issue

### __Issues__ genéricas

* Por último, existe um template para issues genéricas, tais como issues de documentação, ou qualquer tipo de issue fora do escopo de US e TS.
* [template genérico](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/.github/ISSUE_TEMPLATE/generic_template.md)

---

## Política de _Branchs_

### Branch _master_

A _branch master_ é a _branch_ estável do projeto, onde estará o código de produção. _Commits_ e _pushes_ para essa _branch_ estarão bloqueados. Somente serão aceitos _pull requests_ para essa _branch_ oriundos da _branch dev_.

#### Branch _dev_

A _branch dev_ será a _branch_ de desenvolvimento, na qual será unificado novas funcionalidades e correções no código visando gerar uma nova versão estável.

### Nomenclatura das _branchs_

Os nomes das _branchs_ devem estar em **inglês** e serem objetivos e claros, especificando em poucas palavras a intenção da _branch_. Além do mais, devem referenciar a _issue_ relacionada no início do nome, conforme o seguinte padrão:

> `x-branch-name`

Onde x refere-se ao número da _issue_.

#### _Branchs_ de Documentação

_Branchs_ cujo foco seja unicamente atualizar a documentação do repositório devem seguir o seguinte padrão:

> `doc/x-branch-name`

### _Branchs_ de novas funcionalidades

_Branchs_ cujo foco seja inserir uma nova funcionalidade no sistema, em geral relacionadas as _user stories_ devem seguir o seguinte padrão:

> `feat/x-branch-name`

### _Branchs_ para correção de _bugs_

_Branchs_ cujo foco seja corrigir funcionalidade no sistema, em geral relacionadas as _user stories_ devem seguir o seguinte padrão:

> `bugfix/x-branch-name`

### _Branchs_ para refatoração de código

_Branchs_ cujo foco seja refatorar uma funcionalidade no sistema, em geral relacionadas as _techical stories_ devem seguir o seguinte padrão:

> `refact/x-branch-name`

### _Branchs_ para problemas críticos em produção

_Branchs_ cujo foco seja corrigir algum problema crítico em produção, o qual não possa esperar até a próxima _release_ devem seguir o seguinte padrão:

> `hotfix/x-branch-name`

### _Branchs_ para lançamento de versão

> `release/stable-x.x.x`

Onde x.x.x refere-se ao número da versão que será lançada.

---

## Política de _Commits_

### Mensagem do _Commit_

A descrição dos _commits_ podem estar tanto em **inglês** quanto em **português** e devem ser sucintas e objetivas, representando claramente o que está sendo alterado naquele _commit_. A mensagem deve estar acompanhada do número da _issue_ relacionada, como no exemplo abaixo:

> `git commit -m'#X my message'`

__Onde X representa o número da _issue_ relacionada.__

### _Commits_ com pareamento

Quando houver pareamento o _commit_ deve vir acompanhado da mensagem: `Co-authored-by: CoAuthorName <coauthoremail@mail.com>`. Para tal deve-se seguir os seguintes passos:

1. `git commit -s`
1. Inserir a descrição do _commit_ na primeira linha
1. Na linha seguinte inserir a mensagem `Co-authored-by: CoAuthorName <coauthoremail@mail.com>`, com os respectivos dados do co-autor.

## Política de _Pull Requests_

Os _Pull Requests_ podem possuir a descrição em **inglês** ou **português** e devem seguir as seguintes recomendações:

* _Pull Requests_ originados de _branchs_ classificadas como _feature_, _documentation_ e _bugfix_ devem ser abertos para a _branch_ _dev_.

* _Pull Requests_ originados de _branchs_ _hotfix_ devem ser abertos direto para _branch master_.

### _Pull Requests_ em progresso

_Pull Requests_ que ainda não estão prontos para serem aceitos devem conter a sinalização _WIP - Work in Progress_ logo no início do nome. Exemplo:

> `WIP: my pull request`

### Condições para aprovação do _Pull Request_

Para que o _pull request_ seja aceito nas _branchs_ oficiais ele deve atender os seguintes pontos:

* Funcionalidade, correção ou refatoração completa;
* _Build_ de integração contínua passando;
* Manter a cobertura do código acima de 90%;
* Estar de acordo com as métricas de qualidade de código descritas no plano de qualidade.

### _Pull Requests_ de Lançamento de Versão

Lançamentos de novas versões a partir _dev_ deve ser realizado seguindo os seguintes passos:

1. Criar uma _branch_ _release_ a partir da _dev_ com o número da nova versão
1. Lançar a _tag_ do nova _release_
1. Atualizar a _master_ com a nova _release_

## Referências

* [Guia de contribuição IndicaAi](https://github.com/fga-eps-mds/2018.2-IndicaAi/blob/devel/CONTRIBUTING.md)

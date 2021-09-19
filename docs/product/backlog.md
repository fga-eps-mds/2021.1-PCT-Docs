# Backlog

## Histórico de Versão

| Data       | Versão | Descrição                                                 | Autores                             |
| ---------- | ------ | --------------------------------------------------------- | ----------------------------------- |
| 29/08/2021 | 0.1    | Realização do Backlog com base nos requisitos elicitados. | Letícia Karla Araújo e Julio Litwin |
| 12/09/2021 | 0.2    | Adição de contextualização do Backlog                     | Lucas Maciel                        |
| 12/09/2021 | 0.3    | Migração do Backlog para uma planilha do Google Sheets    | Lucas Maciel                        |
| 12/09/2021 | 0.4    | Detalhamento das US's e Épicos                            | Lucas Gomes                         |
| 13/09/2021 | 0.5    | Adicionando os critérios de aceitação                      | Julio Litwin                        |
| 13/09/2021 | 1.0    | Adicionando novas US's e alterando critérios de aceitação  | Lucas Gomes                        |

## 1. Introdução

O Backlog do produto consiste em uma lista de funcionalidades priorizadas, contendo uma descrição curta das funcionalidades desejadas para o produto de software.
No Scrum, o Backlog do produto pode ser alterado a medida que o produto é desenvolvido, tanto para um aumento de escopo ou alterações de requisitos.

### 1.1 Épicos e Funcionalidades (Epic and Features)

Épico: É uma história de usuário que ainda não foi detalhada, ou é muito longa, ou ainda está cheia de incertezas e, portanto, não pode ser transformada em um incremento de produto. Portanto, em um Backlog, um Épico representa uma coleção de funcionalidades que são agrupadas logicamente a partir de um escopo definido.

Feature: É uma "funcionalidade" ou uma "característica".


| Épico | Feature | US's relacionadas |
|--|--|--|
| EP01 - Pesquisa | F01 - Pesquisa Avançada | [US01](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us01), [US02](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us02), [US22](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us22)  |
| EP01 - Pesquisa | F02 - Visualização  | [US03](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us03), [US04](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us04) e [US23](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us23) |
| EP01 - Pesquisa | F03 - Armazenamento  | [US05](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us05) e [US24](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us24) |
| EP01 - Pesquisa | F04 - Exportação  | [US06](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us06) |
| EP02 - Usuário  | F05 - Cadastro  | [US07](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us07) e [US08](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us08) |
| EP02 - Usuário  | F06 - Entrada | [US09](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us09) e [US10](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us10) |
| EP03 - Atualizações | F07 - Feed de Atualizações  | [US11](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us11) e [US12](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us12) |
| EP04 - Manter Dados | F08 - Inserção de fontes de dados  | [US13](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us13), [US14](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us14), [US15](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us15), [US16](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us16), [US17](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us17), [US18](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us18) e [US19](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us19), [US20](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us20) |
| EP04 - Manter Dados | F09 - Categorização dos dados  | [US21](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/docs/product/backlog.md#us21) |


### 1.2 História de Usuário (User Story)

Uma história do usuário é um formato curto para escrever os requisitos para construir um produto. Deve ser inteligível para clientes e consumidores.

#### US01
##### Realizar buscas de informação.

| **Épico** |EP01 - Pesquisa |
| ---: | :------- |
| **Feature** |F01 - Pesquisa Avançada |
| **Descrição** |Eu, como usuário, desejo realizar buscas no site. |
| **Critérios de aceitação** | - Deve mostrar campo para digitar a busca do usuário <br> - Deve mostrar botão para pesquisar <br> - Deve verificar se o texto não é nulo |


#### US02
##### Selecionar filtros de buscas.

| **Épico** |EP01 - Pesquisa |
| ---: | :------- |
| **Feature** |F01 - Pesquisa Avançada |
| **Descrição** |Eu, como usuário, desejo selecionar filtros de busca.|
| **Critérios de aceitação** | - Deve mostrar campos de filtros para a busca <br>- Deve utilizar os filtros quando for pesquisar |

#### US03
##### Visualizar resultado da pesquisa.

| **Épico** |EP01 - Pesquisa |
| ---: | :------- |
| **Feature** |F02 - Visualização |
| **Descrição** | Eu, como usuário, desejo visualizar os resultados da minha pequisa. |
| **Critérios de aceitação** | - Verificar se a pesquisa obteve resultados <br> - Mostrar todos os resultados obtidos em ordenadamente  |

#### US04
##### Ler resultado da pesquisa.

| **Épico** |EP01 - Pesquisa |
| ---: | :------- |
| **Feature** |F02 - Visualização |
| **Descrição** | Eu, como usuário, desejo ler um resultado, a partir da pesquisa. |
| **Critérios de aceitação** | - Ser redirecionado para o resultado em nova aba (ou na mesma aba)  |

#### US05
##### Salvar pesquisa desejada no perfil.

| **Épico** |EP01 - Pesquisa |
| ---: | :------- |
| **Feature** |F03 - Armazenamento |
| **Descrição** | Eu, como usuário, desejo salvar minha pesquisa no meu perfil. |
| **Critérios de aceitação** | - Deve mostrar ícone para salvar a pesquisa <br> - Estar logado na conta do perfil |

#### US06
##### Salvar pesquisa desejada no perfil.

| **Épico** |EP01 - Pesquisa |
| ---: | :------- |
| **Feature** |F04 - Exportação |
| **Descrição** | Eu, como usuário, desejo exportar a minha pesquisa salva. |
| **Critérios de aceitação** | - Deve mostrar ícone para exportar a pesquisa <br> - Estar logado na conta do perfil <br> - Ter a pesquisa já salva no perfil. |

#### US07
##### Fazer cadastro.

| **Épico** |EP02 - Usuário	 |
| ---: | :------- |
| **Feature** |F05 - Cadastro |
| **Descrição** | Eu, como usuário, desejo fazer o meu cadastro no site. |
| **Critérios de aceitação** | - Deve mostrar a opção de cadastro <br> - Fazer verificação via email |

#### US08
##### Editar cadastro.

| **Épico** |EP02 - Usuário |
| ---: | :------- |
| **Feature** |F05 - Cadastro |
| **Descrição** | Eu, como usuário, desejo editar o meu cadastro. |
| **Critérios de aceitação** | - Mostrar informações atuais <br> - Confirmar edição dos dados através da senha do usuário  |

#### US09
##### Fazer login.

| **Épico** |EP02 - Usuário |
| ---: | :------- |
| **Feature** |F06 - Entrada |
| **Descrição** | Eu, como usuário, desejo fazer o meu login no site. |
| **Critérios de aceitação** | - Deve possuir campos para preencher os dados <br> - Validar os dados de acesso <br> - Disponibilizar acesso às páginas  |

#### US10
##### Realizar logout.

| **Épico** |EP02 - Usuário |
| ---: | :------- |
| **Feature** |F06 - Entrada |
| **Descrição** | Eu, como usuário, desejo realizar logout no site. |
| **Critérios de aceitação** | - Deve haver ícone para o logout <br> - Retornar a tela de login <br> - Não permitir o usuário acessar as funcionalidades do aplicativo na qual exigem estarem logado  |

#### US11
##### Ver o feed das últimas atualizações de informações.

| **Épico** |EP03 - Atualizações |
| ---: | :------- |
| **Feature** |F07 - Feed de Atualização |
| **Descrição** | Eu, como usuário, desejo ver o feed das últimas atualizações. |
| **Critérios de aceitação** | - Devem ser apresentadas as últimas notícias inseridas no banco <br> - Toda notícia deve quando clicada, encaminhar para a sua fonte <br> - As notícias devem serem rotativas  |

#### US12
##### Ver o feed das últimas atualizações da nova cartografia social.

| **Épico** |EP03 - Atualizações |
| ---: | :------- |
| **Feature** |F07 - Feed de Atualização |
| **Descrição** | Eu, como usuário, desejo ver as últimas atualizações do site da nova cartografia social. |
| **Critérios de aceitação** | - Devem ser apresentadas as últimas notícias do site da nova cartografia social <br> - Toda notícia deve quando clicada, encaminhar para a sua fonte <br> - As notícias devem serem rotativas  |

#### US13
##### Adicionar  novas fontes de dados pelo próprio site.

| **Épico** |EP04 - Manter Dados|
| ---: | :------- |
| **Feature** |F08 - Inserção de fontes de dados |
| **Descrição** | Eu, como usuário privilegiado, gostaria de poder adicionar novas fontes de dados pelo próprio site, criando um novo crawler. |
| **Critérios de aceitação** |
- O scraper deve ser capaz de coletar o corpo (HTML) de páginas da 3 primeiras fontes (TCU, Senado, Diário Oficial)<br>
- As páginas devem ser minimamente filtradas a partir das palavras-chave (keywords)<br>
- Os dados brutos devem ser salvos na base de dados do serviço de Scraper<br>
- O fomulário de cadastro no frontend deve estar funcionando e deve ser intuitivo<br>
- Deve ser possível realizar cadastro e atualização das fontes de dados<br> |

#### US14
##### Adicionar  novas palavras-chaves para melhoramento do modelo de machine learning.

| **Épico** |EP04 - Manter Dados|
| ---: | :------- |
| **Feature** |F08 - Inserção de fontes de dados |
| **Descrição** | Eu, como usuário privilegiado, gostaria de adicionar palavras-chave para melhorar o modelo de machine learning, auxiliando a filtragem de notícias nos sites. |
| **Critérios de aceitação** | -  |

#### US15
##### Realizar a 1ª alimentação da base da dados.

| **Épico** |EP04 - Manter Dados|
| ---: | :------- |
| **Feature** |F08 - Inserção de fontes de dados |
| **Descrição** | Eu, como administrador, gostaria de utilizar um crawler em um determinado site para realizar a 1ª alimentação da base de dados. |
| **Critérios de aceitação** | -  |

#### US16
##### Realizar a 2ª alimentação da base da dados.

| **Épico** |EP04 - Manter Dados|
| ---: | :------- |
| **Feature** |F08 - Inserção de fontes de dados |
| **Descrição** | Eu, como administrador, gostaria de utilizar um crawler em um determinado site para realizar a 2ª alimentação da base de dados. |
| **Critérios de aceitação** | -  |

#### US17
##### Realizar a 3ª alimentação da base da dados.

| **Épico** |EP04 - Manter Dados|
| ---: | :------- |
| **Feature** |F08 - Inserção de fontes de dados |
| **Descrição** | Eu, como administrador, gostaria de utilizar um crawler em um determinado site para realizar a 3ª alimentação da base de dados. |
| **Critérios de aceitação** | -  |

#### US18
##### Realizar a 4ª alimentação da base da dados.

| **Épico** |EP04 - Manter Dados|
| ---: | :------- |
| **Feature** |F08 - Inserção de fontes de dados |
| **Descrição** | Eu, como administrador, gostaria de utilizar um crawler em um determinado site para realizar a 4ª alimentação da base de dados. |
| **Critérios de aceitação** | -   |

#### US19
##### Realizar a 5ª alimentação da base da dados.

| **Épico** |EP04 - Manter Dados|
| ---: | :------- |
| **Feature** |F08 - Inserção de fontes de dados |
| **Descrição** | Eu, como administrador, gostaria de utilizar um crawler em um determinado site para realizar a 5ª alimentação da base de dados. |
| **Critérios de aceitação** | -  |

#### US20
##### Realizar agendamento do crawler da 1ª alimentação da base da dados.

| **Épico** |EP04 - Manter Dados|
| ---: | :------- |
| **Feature** |F09 - Categorização dos dados |
| **Descrição** | Eu, como administrador, gostaria de realizar o agendamento do crawler da 1ª alimentação da base de dados |
| **Critérios de aceitação** | - Definir periodicidade <br> - Implementar agendamento do crawler <br> - Realizar testes |

#### US21
##### Categorização dos Dados.

| **Épico** |EP04 - Manter Dados|
| ---: | :------- |
| **Feature** |F09 - Categorização dos dados |
| **Descrição** | Eu, como administrador, gostaria de utilizar técnicas de machine learning para realizar a categorização dos dados que alimentarão a base |
| **Critérios de aceitação** | - Definir categorias <br> -  |

#### US22
##### Aba de Busca Avançada.

| **Épico** |EP01 - Pesquisa|
| ---: | :------- |
| **Feature** |F01 - Pesquisa Avançada |
| **Descrição** | Eu, como usuário, desejo acessar uma aba específca para busca avançada |
| **Critérios de aceitação** |   |

#### US23
##### Aba de Sobre Nós.

| **Épico** |EP01 - Pesquisa|
| ---: | :------- |
| **Feature** | F02 - Visualização |
| **Descrição** | Eu, como usuário, desejo acessar uma aba sobre as informações do projeto Nova Cartografia Social |
| **Critérios de aceitação** | - Aba na navbar <br> - Detalhamento sobre o projeto Nova Cartografia Social <br> - Detalhamento sobre a equipe de desenvolvimento e clientes  |

#### US24
##### Lista de Pesquisas Salvas.

| **Épico** |EP01 - Pesquisa|
| ---: | :------- |
| **Feature** | F03 - Armazenamento |
| **Descrição** | Eu, como usuário, desejo acessar as pesquisas salvas no meu perfil. |
| **Critérios de aceitação** | - Mostrar a lista de pesquisas salvas <br> - Mostrar botão para exportação da lista <br> - Reabrir pesquisa salva  |


### 1.3 Prioridade

A prioridade é um recurso importante para o backlog, com ele é possível definir qual deverá ser a ordem de construção das funcionalidades, de acordo com sua prioridade, levando em consideração quais são as funcionalidades mais importantes do produto.
Normalmente, a prioridade é definida utilizando a técnia MoSCoW (Must have, Should have, Could have, Won't have (agora)).

### 2 Tabela de Backlog

<iframe
    src="https://docs.google.com/spreadsheets/d/e/2PACX-1vTPwvqZjO0pHQbZQRrWkvkYV0XlD31loCOU-NE-BKJs4t_fZRPw3gTOg-YV_1pv0jHd7_AejE11Xd-b/pubhtml"
    style="height: 100vh;"
>
</iframe>

# Custo Estimado

## Histórico de Revisão

| Data  | Versão | Descrição | Autor(es) |
|-------|--------|-----------|-----------|
|12/09|0.1|Criação do documento|[Lucas Gomes](@LGomees)|
|12/09|0.2|Adição dos custos|[Lucas Gomes](@LGomees)|
|12/09|0.3|Alteração de valores do custo|[Lucas Gomes](@LGomees)|

## Introdução

O custo estimado para o projeto inclui todos os insumos necessários para a realização do mesmo, contabilizando gastos de material, de pessoal e de aquisição de ferramentas.

## Aquisição 

Levando em consideração um notebook com um processador intel core i7 de última geração, 8GB de memória RAM e 256GB de memória interna no SSD (para um melhor desempenho na criação de modelos de Machine Learning), sendo vendido a [4.199,00 na data de 12/09/2021](https://www.zoom.com.br/notebook/notebook-samsung-book-np550xda-ks1br-intel-core-i7-1165g7-15-6-8gb-ssd-256-gb-11-geracao-windows-10?_lc=20088&searchterm=notebook%20i7)

|Item a ser adquirido|Finalidade|Valor(R$)|Quantidade|Total(R$)|Fornecedor|
|:------------------:|:--------:|:-------:|:--------:|:-------:|:--------:|
|Notebook|Desenvolvimento e planejamento|Média R$ 4.199,00|9|R$ 37.791,00|Samsung|

## Pessoal 

Para calcular o custo da mão de obra do projeto, podemos pensar em dois possíveis cenários:
* Cenário sem Pandemia: Utilizando como base os valores do relatório de gestão da UnB de 2016, divulgado pelo Decanato de Planejamento e Orçamento da UnB, obtendo o valor do custo de um aluno do campus da UnB FGA, de R$ 26.040,00 ao ano. Com esse valor podemos chegar ao custo por hora de um aluno.
* Cenário com Pandemia: Como a estrutura da universidade não está sendo utilizada por conta do distanciamento social, podemos levar em consideração o salário médio de um desenvolvedor júnior em Brasília (R$ 2.963,00) como base para o cálculo da hora do aluno ao desenvolver o projeto, sendo um valor de R$ 18,50 a hora. 

Analisando as necessidades da matéria, utilizaremos o cenário sem a pandemia, levaremos em consideração as seguintes variáveis:

* O custo de um aluno por semestre na FGA com base no valor anual é de R$ (26.040,00/12) x 4 meses, que equivale a R$ 8.680,00.
* Com base no cronograma da disciplina de Engenharia de Produto de Software, no semestre 2021-1 o semestre possui 16 semanas, por tanto o custo por sprint (8.680,00/ 16 sprints) equivale a R$ 542,50 por sprint para cada aluno.

|Número de Alunos| Custo total por sprint | Custo total para 16 sprints | 
|:---:|:------------:|:-------------------:|
|9| R$ 4.882,50 | R$ 78.120,00 |


## Ferramentas

|Ferramenta|Finalidade|Preço|
|:--------:|:--------:|:---:|
|Linux/Windows|Sistema Operacional para desenvolvimento|R$ 0,00|
|Git e Github|Gerenciamento de versão do código|R$ 0,00|
|Zenhub|Centralizar e organizar as tarefas a serem feitas|R$ 0,00|
|Google Drive|Gerenciamento e evolução das documentações|R$ 0,00|
|Discord e Telegram|Comunicação do grupo de forma remota|R$ 0,00|
|SonarCloud|Melhoria de e verificação de qualidade de código|R$ 0,00|


## Total

|Tipo de insumo|Custo|
|:------------:|:---:|
|Recursos humanos| R$ 78.120,00|
|Equipamentos e serviços| R$ 37.791,00|  
|Ferramentas| R$ 0,00|  
|Total|R$ 115.911,00|

## EVM Agile

O EVM Agile possui particularidades em relação ao EVM tradicional, contendo métricas particulares à metodologia como histórias de usuário, sprints, pontos de histórias de usuário e etc.

Para ter acesso a planilha, clique [aqui](https://docs.google.com/spreadsheets/d/1BeQMp6tplsHfuIUWcC5x4k6TzeLXBIrHd1GruboG2zg/edit#gid=1444792691).

## Referências

Relatório de Gestão 2016, Universidade de Brasília. Disponível em http://www.dpo.unb.br/images/phocadownload/documentosdegestao/relatoriogestao/Relatrio-de-Gesto-2016.pdf. Acesso em 12 de setembro de 2021.

Zoom, Site para comparação de preços, Disponível em: https://www.zoom.com.br/. Acesso em 12 de setembro de 2021.

Glassdoor, Site para análise de salários, Disponível em https://www.glassdoor.com.br/Sal%C3%A1rios/bras%C3%ADlia-desenvolvedor-j%C3%BAnior-sal%C3%A1rio-SRCH_IL.0,8_IM1010_KO9,29.htm. Acesso em 12 de setembro de 2021.

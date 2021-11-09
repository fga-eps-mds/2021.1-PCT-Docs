# Plano de Qualidade

|    Data    | Versão |      Descrição       |           Autor(es)            |
| :--------: | :----: | :------------------: | :----------------------------: |
| 08/11/2021 |  1.0   | Documentação da Análise de Qualidade | Guilherme Mendes |

## Introdução

Para a análise e coleta de métricas do projeto, foi realizada a integração com a ferramenta do SonarQube para todos os serviços desenvolvidos. Sendo possível a visualização de métricas que norteiam o processo de melhoria e qualidade do código. 

A partir do modelo Q-Rapids de qualidade, foram extraídas as seguintes métricas: 

### Complexidade (*Complexity*)
* Quantidade de caminhos independentes ou ciclos encontrados em um código.

### Densidade de linhas comentadas (*Comment Lines Density*)
* Número de linhas comentadas no código.

### Densidade de linhas duplicadas (*Duplicated Lines Density*)
* Quantidade de linhas de código duplicados.

### Tempo de execução de testes (*Test Execution Time*)
* Tempo de execução de testes unitários.

### Cobertura de testes (*Coverage*)
* Cobertura de testes unitários executados com sucesso.

Com a utilização do jupyter notebook [analytics.ipynb](https://github.com/fga-eps-mds/2021.1-PCTs-Docs/blob/main/analytics-notebooks/analytics.ipynb) foram gerados os seguintes gráficos.

#### Legenda
* m1 - COMPLEXITY
* m2 - COMMENTS
* m3 - DUPLICATIONS
* m4 - TEST SUCCESS DENSITY
* m5 - TEST EXECUTION TIME
* m6 - COVERAGE

## Repositório [Scraper](https://github.com/fga-eps-mds/2021.1-PCTs-Scraper)

![scraper](https://imgur.com/priP41I.png)

## Repositório [Frontend](https://github.com/fga-eps-mds/2021.1-PCTs-Frontend)

![frontend](https://imgur.com/6alvhIh.png)
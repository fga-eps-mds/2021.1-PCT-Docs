# Plano de Qualidade

|    Data    | Versão |      Descrição       |           Autor(es)            |
| :--------: | :----: | :------------------: | :----------------------------: |
| 08/11/2021 |  1.0   | Documentação da Análise de Qualidade | Guilherme Mendes |
| 12/11/2021 |  2.0   | Atualizado e corrigido a documentação de Análise de Qualidade | Julio Litwin |

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

## Repositório: [Scraper](https://github.com/fga-eps-mds/2021.1-PCTs-Scraper)

![scraper](https://imgur.com/priP41I.png)

## Repositório: [Documents API](https://github.com/fga-eps-mds/2021.1-PCTs-Documents-API)

![documentsapi](https://imgur.com/amb9vyC)

## Repositório: [ML Training](https://github.com/fga-eps-mds/2021.1-PCTs-ML-Training)

![ml](https://imgur.com/QUtN2Rl)

## Repositório: [Frontend](https://github.com/fga-eps-mds/2021.1-PCTs-Frontend)

![frontend](https://imgur.com/6alvhIh.png)


### Análise

Observando-se todas a métricas apresentadas, pode se concluir que com os valores são bem abaixo do esperado, diante de tomadas de decisões, tais como prioridades a serem realizadas, como consequência, houve uma enorme carência relacionado aos testes nos demais projetos, foi realizado testes apenas nos projetos: Documents API e no Scraper.

Com o gráfico de Confiabilidade e Manutenibilidade, os valores estão basicamente se opondo um ao outro. Tais dados pode se ver claramente por questões de impactos ocorridos diante ao seu desenvolvimento do projeto. Tais como decisões tomadas, problemas relacionados ao time também, como saídas de alguns integrantes (ocorrendo uma carência para desenvolvimento maior), curva de aprendizados, desafios diante ao desenvolvimento e outras circunstâncias.

Pode se reparar diante aos valores do Reliability com a sua depedência referente aos testes, tais como teste de unidades, testes de execução e dentre outros, há um gráfico não constante e bem abaixo do esperado. Contudo visando o futuro e as melhorias, então há uma dependência para implementações de testes, em todos os projetos e visando o 100% diante do coverage.

Com o Maintainalibity, também se encontra com valores abaixo do esperado, tais como valores podem ser solucionados com a ajuda do SonarQube, tais como qualidade de código, complexidades, comentários, duplicações de códigos e dentre outros. Pode se ver que na última linha do gráfico, foi visto um ganho maior, visando valores melhores para ser atingindos. 
# Documento de Planejamento de Qualidade

|    Data    | Versão |      Descrição       |           Autor(es)            |
| :--------: | :----: | :------------------: | :----------------------------: |
| 12/09/2021 |  0.1   | Abertura e edição do documento | Guilherme Mendes |


## Introdução

De acordo com o PMBOK, a gerência de qualidade do projeto inclui os processos requeridos para garantir que o produto irá satisfazer as necessidades para as quais ele foi empreendido. 
Dessa forma, a qualidade de um projeto de software é fundamental e deve ocorrer de forma contínua. Logo, este documento tem por objetivo descrever o planejamento e gerenciamento de qualidade que irá ocorrer durante sua execução, realizando análises de requisitos levantados anteriormente pela equipe.

## Processo de qualidade

Inicialmente foi proposto no processo de qualidade a divisão em dois principais âmbitos: Produto e Artefatos.
A fim de garantir a qualidade dos artefatos desenvolvidos as seguintes de atividades:

![](https://i.imgur.com/YLyh5Dw.png)

### Desenvolvimento dos Artefatos
Consiste na elaboração dos Planos de Gerenciamento, feitos pela equipe de gestão, bem como, Documento de Visão, Documento de Arquitetura e os demais artefatos elaborados pela equipe de desenvolvimento.
### Apuração de Qualidade 
Consiste na revisão dos artefatos produzidos sendo responsabilidade da equipe de gerenciamento, sendo realizada por outros integrantes para identificar possíveis erros.
### Melhorias 
Caso os artefatos não sejam validados, deve-se verificar a construção dos mesmos, revisar e propor melhorias.

## Qualidade do código

Para garantir a qualidade do software produzido, serão elaborados o seguinte processo de validação:

![](https://i.imgur.com/LDCotCd.png)

### Realizar Medições
Consiste em coletar as métricas com relação ao código, utilizando uma ferramenta que proporciona a análise de métricas relacionadas ao código desenvolvido.

### Exportar métricas e relatórios
Consiste em documentar e extrair os dados das métricas obtidas para que possa ser observado parâmetros que auxiliem na revisão da qualidade do código.

### Revisar Código
Os códigos desenvolvidos passarão por revisões e validações onde serão apontados possíveis melhorias por outros integrantes caso necessário.

### Propor melhorias: 
Consiste na proposta de melhoria para o código, baseada nas métricas coletadas, no código produzido e na análise dos pull requests.

Além disso, serão realizadas extrações a partir das métricas coletadas por meio de pipelines e com o uso da ferramenta [SonarCloud](https://sonarcloud.io/code-quality), cobertura de testes e a qualidade do código em geral.

## Requisitos de qualidade

### Manutenibilidade 
Através das coletas de métricas de análise do código, configurações de pipelines para validação, CI/CD, cobertura de testes realizadas por ferramentas podemos inferir a manutenção do projeto de software.

### Portabilidade
Levando em consideração a portabilidade e a facilidade com que será possível modificar o software, com isso, serão desenvolvidos containers Docker que isolaram os ambientes da aplicação e simplificam execuções de builds, pipelines, instalações e etc.
### Usabilidade
A aplicação deve possuir possuir uma interface intuitiva e de fácil acesso para os variados públicos alvo.
### Segurança 
A aplicação deve tratar de forma segura as informações extraídas e armazenadas.
### Escalabilidade
A aplicação deve ser capaz de escalar conforme o crescimento do número de usuários e para implementação de novas funcionalidades.
### Confiabilidade
A aplicação deve ser capaz de recuperar dados confiáveis a respeito dos povos e comunidades tradicionais e possuir capacidade de disponibilidade estando de acordo com as convenções, normas e regulamentações de confiabilidade.


## Referências Bibliográficas
PMI. Um guia do conhecimento em gerenciamento de projetos. Guia PMBOK 5a. ed. - EUA: Project Management Institute, 2013.

Engenharia de software - Qualidade de produto. [NBR ISO/IEC 9126-1]. https://jkolb.com.br/wp-content/uploads/2014/02/NBR-ISO_IEC-9126-1.pdf 

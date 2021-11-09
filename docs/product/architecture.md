# Documento de Arquitetura - PCTs

## Histórico de Revisão
|Data|Versão|Alteração|Autor|  
|----|------|---------|-----|  
|24/08/2021|0.1|Abertura do documento de Arquitetura|Guilherme Mendes Pereira|  
|09/09/2021|0.2|Introdução| Letícia Karla |
|09/09/2021|0.3|Representação Arquitetural - Tecnologias|Guilherme Mendes Pereira|
|09/09/2021|0.4|Metas e Restrições|Lucas Gomes Silva e Guilherme Mendes Pereira|
|09/09/2021|0.5|Representação Arquitetural - Microsserviços|Lucas Maciel|
|09/09/2021|0.6| Visão Lógica (Diagramas)|Caio Fernandes|
|12/09/2021|0.7| Revisão e refatoração do Documento por completo|Miguel Alves|
|12/09/2021|0.8| Visão Lógica |Caio Fernandes|
|12/09/2021|0.9| Representação Arquitetural (Novos Diagramas)| Miguel Alves|
|12/09/2021|0.10| Visão de Casos de Uso | Lucas Silva|
|13/09/2021|0.11| Evolução da Modelagem de BD | Caio Fernandes|
|13/09/2021|1.0| Adição Pipeline DevOps | Lucas Maciel |
|09/11/2021|1.0| Atualização dos diagramas Diagrama de Relações, Serviços, DER e Lógico | Lucas Maciel |

## 1. Introdução
### 1.1 Finalidade
Este documento tem por finalidade apresentar a arquitetura adotada para o projeto PCTs e relatar e explanar, de maneira clara para que o entendimento se torne facilitado, as decisões tomadas em nível arquitetural em relação ao projeto. Nele será possível visualizar as estruturas que constituem a arquitetura e colaboram para o funcionamento da aplicação, desde o diagrama de relações entre os microsserviços à visão lógica da arquitetura.

### 1.2 Escopo
O projeto PCTs consiste em uma aplicação, consumida na forma de um site, com o objetivo de facilitar a busca de informações relevantes acerca dos PCTs, a fim de contribuir para a disseminação de conhecimento, criação de políticas públicas, realização de pesquisas e projetos e informar os acontecimentos atuais a cerca desses PCTs, de maneira que possa contribuir para a proteção de seus direitos. Tais informações serão extraídas somente de fontes públicas oficiais, tais como sites governamentais, a fim de manter e garantir a segurança da relevância dessas informações. Em suma, é um Sistema de busca que visa trazer praticidade e eficiência na recuperação de informações relevantes a respeito desse assunto.

### 1.3 Definições, acrônimos e abreviações
|Definições, acrônimos e abreviações | Significado|
|-|-|
|App|Aplicativo. Também pode ser usado  |
|API| Application Programming Interface ou Interface de Programação de Aplicações|
|PCT|Povos e Comunidades Tradicionais|
|CSS|Cascading Style Sheets ou Folhas de Estilo em Cascata|
|HTML|HyperText Markup Language ou Linguagem de Marcação de HiperTexto|
|Framework|Pacote de códigos prontos que podem ser utilizados no desenvolvimento de softwares|
|Microsserviços|Construção de aplicações as dividindo em serviços independentes. Estes serviços se comunicam entre si usando APIs.|
|Crawler/Scrapper|Programas usados pelos mecanismos de busca para explorar a internet de maneira automática e fazer download de conteúdo web.|
|Machine Learning (ML)|Aprendizado de Máquina|


## 2. Representação Arquitetural
### 2.1 Diagrama de Relações


* Versão 1 (Planejada):
![ArchitecturalRepresentation](https://i.imgur.com/JJNYleS.png)

* Versão Executada (Simplificada):
![ArchitecturalRepresentationV2](https://i.imgur.com/JLX8izy.jpg)


### 2.2 Representação dos Microsserviços
A arquitetura do projeto será desenvolvida por meio de microsserviços, ou seja, serviços com um escopo definido que tem o objetivo de executar um pequeno conjunto de funcionalidades. As vantagens de se utilizar uma arquitetura de microsserviços residem nas capacidades de escalabilidade, baixo acoplamento entre os serviços, organização dos serviços por capacidades negociais ou assuntos específicos e maior manutenibilidade.

![MicroServicesRepresentation](https://i.imgur.com/vYYsA0B.png)

* **Documents API:** Serviço ou API responsável por armazenar, organizar e entregar os resultados de buscas de documentos para os usuários
* **Users API (não implementado):** API de usuários, onde será armazenado alguns poucos dados de perfil de usuários, além das funcionalidades que permitem uma utilização personalizada do serviço, tais como a funcionalidade de salvamento de pesquisas.
* **Scraper Service:** Serviço  responsável pela coleta e extração de informações das fontes de dados adicionadas ao serviço.
* **ML Training Service:** Módulo de Machine Learning. Este serviço possui uma plataforma com os modelos para categorização, agrupamento e classificação dos documentos extraídos.
* **Frontend:** Módulo de apresentação do serviço ao usuário final. Consiste em um website responsivo capaz de se adaptar desde telas de computadores, até pequenas telas de celular,  sem perder a qualidade visual.

### 2.3 Tecnologias
#### 2.3.1 ReactJS
![ReactJS](https://i.imgur.com/PhHItms.png)

É um framework de código aberto voltado para a aplicação de criação de páginas web. A mesma se utiliza de HTML, CSS e JavaScript para ser aplicada. É possível desenvolver interfaces divididas em componentes reutilizáveis e utilização de bibliotecas e pacotes diferenciados para usos específicos. Grande parte dos seus benefícios e relevância reside na possibilidade componentização relatada, habilitando um grande reaproveitamento de código. 

#### 2.3.2 Django
![Django](https://i.imgur.com/rF4Pnir.jpg)

O Django é um framework de código aberto escrito em Python, seguindo o princípio de DRY (Don’t Repeat Yourself). Permitindo assim otimizar ainda mais a fase de desenvolvimento da aplicação. Dessa forma, viabilizando através do Django REST framework os microsserviços presentes no projeto por meio de API's.


#### 2.3.3 Python
![Python](https://i.imgur.com/yWfzoMD.jpg)

Python é uma linguagem de programação de alto nível, utilizada na programação dos microsserviços do back-end da aplicação.

#### 2.3.4 Postgres (Serviço de usuários)
![Postgres](https://i.imgur.com/BmY1SSk.png)

Sistema de gerenciamento de banco de dados relacional (RDBMS) gratuito e de código aberto que enfatiza extensibilidade e conformidade com SQL.


#### 2.3.5 MondoDB (Serviço de documentos)
![Postgres](https://i.imgur.com/Eoat4tO.jpg)

A tecnologia MongoDB é um banco de dados open source orientado a documentos. Classificado como NoSQL, a tecnologia utiliza documentos com padrão JSON.


#### 2.3.6 Scrapy (Serviço Scraper)
![Scrapy](https://i.imgur.com/Gtt2uOr.png)

Scrapy é um framework de web-crawling gratuito e de código aberto escrito em Python. Projetado originalmente para web scraping, também pode ser usado para extrair dados usando APIs ou como um web crawler de uso geral


#### 2.3.7 Metaflow (Serviço de ML)
![Metaflow](https://i.imgur.com/JU2Ttpj.png)

Metaflow é uma biblioteca Python que auxilia na construção e gerência de projetos de ciência de dados. O Metaflow foi originalmente desenvolvido na Netflix para aumentar a produtividade dos cientistas de dados que trabalham em uma ampla variedade de projetos, desde estatísticas clássicas até aprendizado profundo de última geração.


## 3. Metas e Restrições da Arquitetura
### 3.1 Metas
O negócio ao qual este projeto faz parte tem por objetivo Dar visibilidade e Facilitar o acesso às informações sobre os PCTs. Desta forma, as metas principais do projeto e para estar arquitetura consistem em:
* Centralizar e facilitar a busca de informações relevantes relacionadas aos PCTs;
* Rotular e correlacionar tais informações;

### 3.2 Restrições
* **Prazo:** O escopo definido e proposto para o projeto deve ser concluído até o final da disciplina de EPS;
* **Linguagem:** A aplicação será desenvolvida em português do Brasil;
* **Conectividade:** É necessária conexão com a internet para utilização do App;

### 3.3 Requisitos Não Funcionais
* **Usabilidade:** A aplicação deve possuir uma interface intuitiva e de fácil acessso para todos os públicos;
* **Segurança:** A aplicação deve tratar de forma sgura os dados armazenados (usuário);
* **Escalabilidade:** A aplicação deve ser capaz de escalar conforme o crescimento do número de usuários e para implementação de novas funcionalidades;
* **Confiabilidade:** A aplicação deve ser capaz de recuperar dados confiáveis e relevantes a respeito dos povos e comunidades tradicionais;

## 4. Visão de Caso de Uso
A visão lógica descreve as partes significativas do ponto de vista da arquitetura do modelo de design, como sua divisão em camadas, pacotes, classes e interfaces.

### 4.1 Atores dos Casos de Uso

|Ator|Descrição|  
|----|---------|
| Usuário | O usuário poderá realizar buscas e visualizar o resultado no site, além de  <s>salvar</s> e exportar as buscas <s>salvas</s>. |
| Usuário Privilegiado | O usuário privilegiado poderá adicionar novas fontes de dados e palavras-chaves pelo próprio site. |
| Administrador | O administrador poderá utilizar o crawler em determinados sites a fim de alimentar a base de dados, onde deve acontecer uma categorização dos dados utilizando técnicas de machine learning. |

### 4.2 Descrições dos Casos de Uso
Os casos de uso citados na tabela a seguir são épicos, são eles:

|Épico|Caso de uso|Descrição|  
|-----|-----------|---------|
| EP01 | Pesquisa | Tem por objetivo dar ao usuário a possibilidade de realizar pesquisas avançadas e visualizá-las e, também, <s>salvar</s> e exportar as pesquisas |
| <s>EP02</s> | <s>Usuário</s> (não implementado) | Com o intuito de gerenciamento do cadastro pessoal do usuário, o mesmo poderá se cadastrar e editar o seu cadastro, além de fazer login e logout. |
| <s>EP03</s> | <s>Atualizações</s> (não implementado) | <s>O usuário poderá visualizar as últimas atualizações provenientes da nova cartografia social.</s> |
| EP04 | Manter dados | Usuário privilegiado e administrador poderá realizar ações a fim de gerenciar a base de dados e sua coleta. |

## 5. Visão Lógica
### 5.1 Visão Geral

Visando a utilização de microsserviços, faz-se necessário a implementação de bancos de dados separados por serviços. De acordo com a necessidade e responsabilidade de cada serviço.
Para a nossa arquitetura, os serviços de <s>usuários</s>, documentos e dos crawlers terão bancos de dados. <s>Sendo que a modelagem de usuários irá salvar as informações referentes aos usuários e seus históricos de busca</s>.
E a modelagem para o serviço de Documentos irá simplesmentes salvar cada informação extraída.
Também tem-se o banco dos crawlers, onde são armazenadas informações da fonte de dados e a periodicidade da coleta de dados, além do armazenamento das execuções realizadas.

### 5.2 Diagrama de Entidade Relacionamento
#### 5.2.1 Crawlers
![DERCrawlers](https://i.imgur.com/yG55ATI.jpg)
#### 5.2.2 Documents-API
![DERDocumentsAPI](https://i.imgur.com/7a6WNs4.jpg)
### 5.3 Diagrama Lógico
#### 5.3.1 Crawlers
![LogicalCrawlersApi](https://i.imgur.com/RyytbuB.jpg)
#### 5.3.2 Documents-API
![LogicalDocumentsAPI](https://i.imgur.com/NRbpH43.jpg)

## 6. Pipeline DevOps

Um pipeline de DevOps consiste em um conjunto de processos e ferramentas automatizados que permitem que desenvolvedores e profissionais de operações colaborem na construção e implantação de código para diferentes ambientes e estágios da produção de um software.

![PipelineDevOps](https://i.imgur.com/OTI0REE.png)

## 7. Referências
* RASCHKA, Sebastian; MIRJALILI, Vahid. Python Machine Learning: machine learning and deep learning with python, scikit-learn, and tensorflow 2, third edition. 3. ed. Shangai: International Journal Of Knowledge-Based Organizations, 2021. 770 p.

* KORPELA, J.. Lurching toward Babel: html, css and xml. Computer, [S.L.], v. 31, n. 7, p. 104-106, jul. 1998. Institute of Electrical and Electronics Engineers (IEEE). http://dx.doi.org/10.1109/2.689682. Disponível em: https://ieeexplore-ieee-org.ez54.periodicos.capes.gov.br/stamp/stamp.jsp?tp=&arnumber=689682. Acesso em: 01 set. 2021

* D. Mazinanian and N. Tsantalis, "CSSDev: Refactoring Duplication in Cascading Style Sheets," 2017 IEEE/ACM 39th International Conference on Software Engineering Companion (ICSE-C), 2017, pp. 63-66, doi: 10.1109/ICSE-C.2017.7.

* R. Petrasch, "Model-based engineering for microservice architectures using Enterprise Integration Patterns for inter-service communication," 2017 14th International Joint Conference on Computer Science and Software Engineering (JCSSE), 2017, pp. 1-4, doi: 10.1109/JCSSE.2017.8025912.

* L. Wei-jiang, R. Hua-suo, H. Kun and L. Jia, "A New Algorithm of Blog-Oriented Crawler," 2009 International Forum on Computer Science-Technology and Applications, 2009, pp. 428-431, doi: 10.1109/IFCSTA.2009.110.

* [DevOps Pipeline](https://www.atlassian.com/devops/devops-tools/devops-pipeline). Atlassian. Acesso em: 13 set. 2021

* [Projeto dulce](https://dulce-work-schedule.github.io/especificacao/arquitetura.html). Acesso em: 13 set.2021

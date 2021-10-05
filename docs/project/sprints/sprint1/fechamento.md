# Ata da Sprint Planning

|    Data    | Versão |         Descrição         |           Autor(es)           |
| :--------: | :----: | :-----------------------: | :---------------------------: |
| 20/09/2020 |  1.0   | Redação da ata de fechamento | Lucas Silva |

Os documentos de Fechamento de sprint deverão seguir o seguinte padrão:

# Fechamento da Sprint 01

**Data**: 20 de Setembro de 2021

**Redigida por**: ```Lucas Silva```

**Participantes**: 
* ```Miguel Alves```
* ```Lucas Gomes de Oliveira```
* ```Letícia Araújo```
* ```Lude Yuri ```
* ```Guilherme Mendes```
* ```Lucas Gomes Silva```
* ```Lucas Maciel Aguiar```
* ```Julio Litwin```

## Notas pré reunião
- Caio não participou do fechamento por motivos de estar presente em uma reunião do trabalho no mesmo horário.
- Era necessário marcar uma reunião com o professor Hilmer e não aconteceu.
- Miguel mencionou sobre a comunicação da equipe, onde é necessário melhorar a comunicação tanto entre os integrantes quanto com os professores.

## Review

* ```Lucas Maciel, Lude Yuri e Guilherme Mendes```: Tiveram dificuldade para se reunir e de sete itens propostos para o Scraper, apenas três foram realizadas (setup do scrapy e bibliotecas, script base e salvamento dos dados brutos em banco), faltando a criação de uma API para controle do scraper, CRUD de scrapers (genreciar as fontes), integrar scraper com a API e teste de cobertura da API. Algumas dificuldades foram:
    1. Comunicação entre os serviços: Dúvida sobre qual seria a melhor maneira de armazenar os dados brutos para o serviço ML Training (Database no serviço de Scraper, Message Queue/Broker) em questão de arquitetura?
    2. Possibilidade de utilizar um orquestrador/pipeline de dados?
* ```Caio, Julio e Lucas Silva```: Foi finalizado a parte do banco de dados, mas o scraper não. Não foi realizado pareamento entre os três integrantes. Há uma certa dificuldade em utilizar o Scrapy por falta de conhecimento com o framework, mas o integrante Lucas Maciel tem ajudado tirando dúvidas; 
* ```Miguel, Lucas Gomes e Letícia Araujo```: A US está quase finalizada, faltando apenas a criação dos testes.

## Retrospectiva

* ```Lucas Maciel, Lude Yuri e Guilherme Mendes```: Descrição dos pontos positivos, negativos e melhorias para a sprint seguinte
    * Positivos: ```Houve uma melhoria na estrutura do script do scraper e foi inicializado o setup do banco de dados em MongoDB```
    * Negativos: ```Comunicação, disponibilidade, incerteza sobre arquitetura e recursos```
    * Melhorias: ```Definição melhor da comunicação entre microsserviços, melhoria no entendimento a respeito do scraper```
* ```Caio, Julio e Lucas Silva```: Descrição dos pontos positivos, negativos e melhorias para a sprint seguinte
    * Positivos: ```PontosPositivos```
    * Negativos: ```Comunicação, disponibilidade```
    * Melhorias: ```PossíveisMelhorias```
* ```Miguel, Lucas Gomes e Letícia Araujo```: Descrição dos pontos positivos, negativos e melhorias para a sprint seguinte
    * Positivos: ```US está quase finalizada```
    * Negativos: ```Comunicação, disponibilidade, dependência do cliente```
    * Melhorias: ```Definir uma melhor identidade visual do site```
## Notas pós reunião

- Marcar reunião com o professor Hilmer;
- Houve um entedimento entre os problemas envolvendo a comunicação e o grupo se comprometeu em realizar as melhorias.
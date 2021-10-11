# Dailies da Sprint 4

|    Data    | Versão |         Descrição         |           Autor(es)           |
| :--------: | :----: | :-----------------------: | :---------------------------: |
| 10/10/2021 |  1.0   | Adição das dailies da sprint | Lucas Maciel |

## 1. Daily 1

**Data**: ```07``` de ```10``` de ```2021```

**Redigida por**: ```Lucas Maciel```

**Participantes**:

* ```Caio Fernandes```
* ```Guilherme Mendes```
* ```Lucas Maciel Aguiar```
* ```Lucas Gomes Silva```
* ```Miguel Alves```
* ```Lucas Gomes de Oliveira```
* ```Letícia Karla Araújo```

**Pauta da Reunião**:

> Relatos sobre o andamento das issues da Sprint por cada pareamento
>
> Modelo de resposta da Daily:
>
> 1. O que vocês fizeram das atividades da sprint até agora?
> 2. Como vocês organizaram o pareamento?
> 3. Tiveram alguma dificuldade em específico?

### 1.1 Notas

* ```US02, US22 - Miguel Alves, Lucas Gomes de Oliveira, Letícia Karla Araújo```:
  1. Alinhamos sobre a separação das telas para cada desenvolvedor, e hoje começamos a desenvolver
  2. Como são muitos pontos ,inicialmente a gente vai desenvolver a tela sozinho, e caso necessário a gente pede ajuda um para o outro.
  3. Nenhuma dificuldade até o momento

* ```US02 - Caio Fernandes, Guilherme Mendes```:
  1. Comecei a estudar como conectar com o mongo Atlas para processar os documentos. Encontrei um problema que foi a modelagem do django. Como o django utiliza a própria ORM para tratar os dados, fica complicado entender a modelagem.
  2. O pareamento ocorre todos os dias, eu e o @guilhermemendes  sempre estamos em call, por conta de outros projetos.
  3. No blockers

* ```US20 - Lucas Maciel```:
  1. O que eu fiz até agora foi lançar as releases do Scraper e da API de documentos
  2. *
  3. No PR do Frontend houve problemas,  não consegui executar na minha máquina e tive problemas para fazer o merge com a dev

* ```US07, US08, US09, US10 - Lucas Gomes Silva, Lude Yuri , Julio Cesar Litwin```:
  1. Não foi possível se reunirem
  2. *
  3. Não conseguiram organizar o tempo para se reunirem

## 2. Daily 2

**Data**: ```09``` de ```10``` de ```2021```

**Redigida por**: ```Lucas Maciel```

**Participantes**:

* ```Lucas Maciel Aguiar```
* ```Lucas Gomes Silva```
* ```Miguel Alves```
* ```Julio Cesar Litwin```
* ```Lucas Gomes de Oliveira```
* ```Letícia Karla Araújo```

**Pauta da Reunião**:

> Relatos sobre o andamento das issues da Sprint por cada pareamento
>
> Modelo de resposta da Daily:
>
> 1. O que vocês fizeram das atividades da sprint até agora?
> 2. Como vocês organizaram o pareamento?
> 3. Tiveram alguma dificuldade em específico?

### 2.1 Notas

* ```US02, US22 - Miguel Alves, Lucas Gomes de Oliveira, Letícia Karla Araújo```:
  1. As atividades da sprint foram iniciadas, mas até então não  havia ocorrido nenhum avanço maior. Eles devem evoluir durante o final de semana.
  2. Como temos algumas atividades a mais nessa sprint, dividimos as responsabilidades entre os membros que foram alocados para o frontend e, conforme a necessidade, existe o auxílio entre nós.
  3. Sim, questão de docker não rodando em um sistema específico. Problemas também com horários em choque com outras matérias e trabalho profissional. Problemas pessoais ainda dificultando um pouco o andamento constante dos avanços

* ```US02 - Caio Fernandes, Guilherme Mendes```:
  1. *
  2. *
  3. *

* ```US20 - Lucas Maciel```:
  1. Eu tô ainda fazendo testes da estratégia de scheduler e quais softwares utilizar.
  2. *
  3. Tá meio complicado achar uma solução definitiva. Mas estou considerando utilizar o celery no django para a execução dos jobs + celery beat para agendamento

* ```US07, US08, US09, US10 - Lucas Gomes Silva, Lude Yuri , Julio Cesar Litwin```:
  1. Então, eu tava mexendo um pouco com Django e tava montando o básico da API pra mexer nos users
  2. Separamos as US pra cada um e qualquer problema ou dúvida, um comunicar ao outro
  3. Tô tendo problema em subir o docker, mas isso acredito que seja por conta do meu SO, mas mesmo utilizando o WSL não tô conseguindo

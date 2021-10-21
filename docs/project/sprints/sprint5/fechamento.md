# Fechamento da Sprint 05

|    Data    | Versão |          Descrição           |                 Autor(es)                  |
| :--------: | :----: | :--------------------------: | :----------------------------------------: |
| 18/10/2021 |  1.0   | Redação da ata de fechamento | [Lude Ribeiro](https://github.com/luderibeiro) |
| 20/10/2021 | 2.0 | Correção de escrita e inserção de justificativas | [Lucas Gomes de Oliveira](https://github.com/LGomees) |

**Data**: ```18``` de ```Outubro``` de ```2021```

**Redigida por**: ```Lucas Maciel```

**Participantes**: 
* ```Caio Fernandes```
* ```Guilherme Mendes```
* ```Lucas Maciel Aguiar```
* ```Lucas Gomes Silva```
* ```Lude Yuri ```
* ```Julio Cesar Litwin```
* ```Letícia Karla Araújo```


## Notas pré reunião

* -

## Review

| Descrição da Tarefa | Responsável(eis) | Pontuação | Concluída? | Débito Técnico? |
| ------------------- | ---------------- | --------- | -------------- |---|
| ```US02``` | ```Caio Fernandes, Guilherme Mendes, Miguel Alves``` |```13``` | Não Concluída |  |
| ```US22``` | ```Miguel Alves``` | ```5``` | Não Concluída |  |
| ```US07``` | ```Lude Yuri, Lucas Gomes de Oliveira``` | ```20``` | Não Concluída |  |
| ```US09``` | ```Lude Yuri, Lucas Gomes de Oliveira``` | ```8``` | Não Concluída |  |
| ```US08``` | ```Lucas Silva, Julio Cesar Litwin, Letícia Karla Araújo``` | ```8``` | Não Concluída |  |
| ```US10``` | ```Lucas Silva, Julio Cesar Litwin, Letícia Karla Araújo``` | ```5``` | Não Concluída |  |
| ```US15``` | ```Lucas Maciel``` | | Débito não concluído |
| ```US20``` | ```Lucas Maciel``` | ```20``` | Não Concluída | |


* ```US02 - Caio Fernandes, Guilherme Mendes```:
    * Ficamos com o objetivo de integrar o modelo ao backend, realizando a predição dos dados já extraídos.
    * Tivemos impedimentos por conta da obtenção do dado via pandas e transformação do mesmo em um dataframe, já que a modelagem segue o padrão do django orm.
    * Decidimos por realizar todas essas tarefas através do nosso serviço de documentos. Até então, estávamos tentando via jupyter notebook.
    * Estamos finalizando as rotas de aplicar a predição e obter todos os dados extraídos.
    * Essa segunda é essencial para análise aprofundada do dado.  Essa análise é necessária para o desenvolvimento da pipeline de processamento de texto extraído, para que o modelo tenha o melhor entendimento possível.

* ```US02, US22 - Miguel Alves```:
  * Infelizmente a realização da US foi comprometida pois todos os integrantes alocados para o seu desenvolvimento tiveram problemas pessoais das mais diversas naturezas. A saúde de familiares, cirurgias de emergência e até casos mais íntimos com risco à vida de familiares e internação. Dessa forma, a US não foi evoluída
* ```US07, US09 - Lude Yuri```:
  * Fiquei com o cadastro e com o login de usuário no back mas não consegui concluir no prazo e ainda está sendo produzido pretendo terminar o mais breve possível talvez amanhã
* ```US07, US09 - Lucas Gomes de Oliveira```:
  * Comecei o desenvolvimento da US porém por conta de estar em uma localidade que estava sem energia (durante dois dias), fui impedido de continuar o trabalho. 
* ```US08, US10 - Lucas Silva, Julio Cesar Litwin```:
  * Basicamente finalizamos a parte de edição de perfil, faltando apenas a validação dos testes, mas acredito que ainda hoje ela esteja finalizada. Mas como estamos compartilhando a mesma branch com o Lude, estamos dependendo da US dele pra subir o PR
* ```US08, US10 - Letícia Karla Araújo```:
  * US08 - Consegui implementar a tela de visualização de perfil
  * US08 - Não ficou concluída e por que não havia protótipo. Então, bem provável que vou ter que refatorar.
  * US10 - Criou boão de logout
  * US10 - Não adicionou a ação
* ```US15, US20 - Lucas Maciel```:
  * Setup inicial do Agendador
  * Não conseguiu fazer o deploy no Heroku


## Retrospectiva

* ```Lucas Maciel, Lucas Gomes Silva```: Descrição dos pontos positivos, negativos e melhorias para a sprint seguinte
    * Positivos: ```A equipe conseguiu desenvolver a pagina de busca, primeiro modelo de ML desenvolvido```
    * Negativos: ```Comunicação, carência de padrões na organização dos repositórios, falta de testes de cobertura, falta de compromisso, sem releases```
    * Melhorias: ```Começar a criar mais testes, padronizar os repositórios, melhorar a sincronia das tarefas entre os membros```
* ```Miguel Alves,Lucas Gomes e Letícia Araújo```: Descrição dos pontos positivos, negativos e melhorias para a sprint seguinte
    * Positivos: ```Boa recuperação na sprint por parte da equipe```
    * Negativos: ```Problemas pessoais com os membros da equipe, Comunicação fora do pareamento, Problemas técnicos```
    * Melhorias: ```Comunicação com o restante do time, Desenvolvimento ao longo da sprint```
* ```Lude Ribeiro, Julio Litwin```: Descrição dos pontos positivos, negativos e melhorias para a sprint seguinte
    * Positivos: ```Aprendeu um pouco de Python```
    * Negativos: ```Comunicação```
    * Melhorias: ```Comunicação```
* ```Caio Fernandes e Guilherme Mendes```: Descrição dos pontos positivos, negativos e melhorias para a sprint seguinte
    * Positivos: ```Conseguiram terminar o primeiro modelo```
    * Negativos: ```Comunicação```
    * Melhorias: ```Comunicação, constancia de trabalho, melhor planejamento```

## Notas pós reunião

* Rever o planejamento das USs

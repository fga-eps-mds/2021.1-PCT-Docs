# Fechamento da Sprint 08

|    Data    | Versão |          Descrição           |                 Autor(es)                  |
| :--------: | :----: | :--------------------------: | :----------------------------------------: |
| 08/11/2021 |  1.0   | Redação da ata de fechamento | [Lucas Gomes de Oliveira](https://github.com/LGomees) |

Data: 08 de Novembro de 2021

Redigida por: Lucas Gomes de Oliveira

Participantes: 
* Caio Fernandes
* Guilherme Mendes
* Lucas Maciel Aguiar
* Lucas Gomes Silva 
* Julio Cesar Litwin
* Lucas Gomes de Oliveira


## Notas pré reunião

* Infelizmente tivemos mais uma perda. O Miguel Alves solicitou a retirada da disciplina, impactando negativamente no desenvolvimento de algumas atividades.
* Após conversa com a Profª Sheila, devemos fazer uma adaptação da página de monitoramento para que não seja acessada por qualquer pessoa que usufrua do site.

## Review

| Descrição da Tarefa | Responsável(eis) | Pontuação | Concluída? | Débito Técnico? |
| ------------------- | ---------------- | --------- | ------- | -------- |
| ```US22 - Eu, como usuário, desejo acessar uma aba específica para busca avançada``` | ```Lucas Maciel``` | ```2``` | Sim | Não| 
| ```US02 - Eu, como usuário, desejo selecionar filtros de busca.``` | ```Lucas Maciel``` | ```13``` | Sim | Não|
| ```US06 - Eu, como usuário, desejo exportar a minha pesquisa``` | ```Lucas Maciel, Lucas Gomes de Oliveira``` | ```13``` | Sim | Não|
| ```US25 - Eu, como administrador, gostaria de monitorar o status de execução dos scrapers``` | ```Lucas Gomes de Oliveira``` | ```8``` | Sim | Não|
| ```Implementação do Jupiter Notebook de Analitics``` | ```Julio Litwin``` |  | Sim | |
| ```Continuação do tratamento do Metaflow``` | ```Caio Fernandes, Guilherme Mendes``` |  | Sim | |
| Desenvolvimento Extra: |  |  |  | |
| ```US09 - Eu, como usuário, desejo fazer o meu login no site``` | ```Lucas Maciel``` | ```8``` | Sim | Não| 
| ```US13 - Eu, como usuário privilegiado, gostaria de poder adicionar novas fontes de dados pelo próprio site, criando um novo crawler.``` | ```Lucas Maciel``` | ```20``` | Sim | Não| 




* US02, US22, US13 - Lucas Maciel:
  * Filtros de Busca: Implementados os filtros de fonte, categorias (estático, pois não tem uma tabela na api de documentos com as categorias possíveis), filtro da data que o documento/página foi encontrado.
  * Aba de busca avançada: Utilização da propria aba de resultados para aplicar os filtros, preferi não ter que criar outra página para isso.
  * Além disso, foi implementada uma Modal para que possam ser adicionadas novas fontes de dados diretamente pelo usuário dentro do site, assim como novas palavras-chave para pequisa.
* US06, US25 - Lucas Gomes, Lucas Maciel, Lucas Gomes Silva:
  * O endpoint para exportação em formato CSV foi implementado, juntamente com sua comunicação com o frontend.
  * Foi implementada a tela de monitoramento dos status de execução dos scrappers, juntamente com a listagem das fontes que estão sendo buscadas para a pesquisa integrada.
* US17 - Julio Cesar Litwin:
  * 
* Continuação do tratamento do Metaflow - Caio Fernandes, Guilherme Mendes:
    * Caio e eu evoluímos o script de metaflow e criamos o github actions para automatizar o treinamento do modelo e geração de reports. 
    * Atualizamos o modelo com os novos dados enviados pelos formulários gerando uma nova versão de treinamento e release.
    * Normalização dos dados enviados.


## Retrospectiva

* Lucas Gomes, Lucas Maciel: Descrição dos pontos positivos, negativos e melhorias para a sprint seguinte
    * Positivos: Issues importantes para o usuário foram concluidas, houve pareamento.
    * Negativos: Não validamos a aceitação do cliente através do formulário, desistência da disciplina por parte de outro membro, acúmulo de atividades.
    * Melhorias: Aumentar cobertura de testes, validar features com  o usuário.

* Julio Litwin: Descrição dos pontos positivos, negativos e melhorias para a sprint seguinte
    * Positivos: 
    * Negativos: 
    * Melhorias: 

* Caio Fernandes e Guilherme Mendes: Descrição dos pontos positivos, negativos e melhorias para a sprint seguinte
    * Positivos: Alinhamento do time.
    * Negativos: Perca de um integrante do grupo.
    * Melhorias: Comunicação, organizacao.

## Notas pós reunião

* Devemos fazer um overview do projeto e organizar a apresentação final para a cliente. Analisar todos os artefatos e corrigir erros visualizados.

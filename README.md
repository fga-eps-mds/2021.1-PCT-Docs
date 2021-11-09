# 2021.1-PCT-Docs

Repositório de documentos do projeto "Povos e Comunidades Tradicionais"

PCTs é um projeto desenvolvido para facilitar a busca de documentos que possam contribuir para a proteção de povos e comunidades tradicionais. É um Sistema de busca que visa a praticidade na recuperação de informações relevantes a respeito desse assunto.

## Repositórios do Projeto

- [PCTs-Frontend](https://github.com/fga-eps-mds/2021.1-PCTs-Frontend): Repositório do frontend da aplicação
- [PCTs-Documents-API](https://github.com/fga-eps-mds/2021.1-PCTs-Documents-API): Repositório da base de dados de informações/documentos extraídos das fontes
- [PCTs-Users-API](https://github.com/fga-eps-mds/2021.1-PCTs-Users-API): Repositótio de microserviço de usuários
- [PCTs-Scraper](https://github.com/fga-eps-mds/2021.1-PCTs-Scraper): Repositório do extrator de dados (scraper)
- [PCTs-ML-Training](https://github.com/fga-eps-mds/2021.1-PCTs-ML-Training): Repositório da construção de modelos de Machine Learning

## Executar Documentação Localmente

Installation

---------------
Faça o checkout do projeto

```shell
git clone git@github.com:fga-eps-mds/2021.1-PCTs-Docs.git
```

Instale as bibliotecas de sistema necessárias para usar o docsfy
(vide https://docsify.js.org/#/quickstart?id=preview-your-site)

Instalando via npm:

```shell
npm i docsify-cli -g && docsify serve docs
```

Também é possível via Python usando:

```shell
python -m http.server 3000
```

Contributing
-----------------

1. Clone it.
2. Create a branch (`git checkout -b new_docs`)
3. Commit your changes (`git commit -am "Added new doc"`)
4. Push to the branch (`git push origin new_docs`)
5. Open a [Pull Request] [1]

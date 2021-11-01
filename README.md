# Boas vindas ao repositório do projeto de Front-End Online Store!

Esse projeto foi feito como comprovação dos conhecimentos adquiridos no curso da Trybe, foi feito em grupo, um projeto para listar vários produtos ou procurar por algum especÍfico, utilizando a api do mercado livre porque seria mais viável utilizar um banco de dados já pronto e listado.


# Sumário

- [Habilidades](#habilidades)
- [O que foi utilizado](#intruções-para-entregar)
  - [Linter](#linter)
  - [Usando o Trello como ferramenta kanban](#usando-o-trello-como-ferramenta-kanban)
- [Como utilizar](#Como-utilizar)

# Habilidades

Nesse projeto, você será capaz de:

* Utilização de Métodos Ágeis como Kanban e Scrum
* Utilização do framework React.js
* Linguagem utilizada foi JavaScript
* Utilização do RTL para testes
* Utilização dos Linters para padronização do código

## Documentação da API do Mercado Livre

Sua página _web_ irá consumir os dados da API do _Mercado Livre_ para realizar a busca de itens da sua loja online. Para realizar essas buscas, vocês precisarão consultar os seguintes _endpoints_:

- Para listar as categorias disponíveis:
  - Tipo da requisição: `GET`
  - Endpoint: https://api.mercadolibre.com/sites/MLB/categories
- Para buscar por itens por termo:
  - Tipo da requisição: `GET`
  - Parâmetro de busca $QUERY (este parâmetro deve ser substituído pelo valor do campo de busca)
  - Endpoint: https://api.mercadolibre.com/sites/MLB/search?q=$QUERY
- Para buscar itens por categoria:
  - Tipo da requisição: `GET`
  - Parâmetro de busca $CATEGORY_ID (este parâmetro deve ser substituído pelo ID da categoria selecionada)
  - Endpoint: https://api.mercadolibre.com/sites/MLB/search?category=$CATEGORY_ID
- Para buscar itens de uma categoria por termo:
  - Tipo da requisição: `GET`
  - Parâmetro de busca $QUERY (este parâmetro deve ser substituído pelo valor do campo de busca)
  - Parâmetro de busca $CATEGORY_ID (este parâmetro deve ser substituído pelo ID da categoria selecionada)
  - Endpoint: https://api.mercadolibre.com/sites/MLB/search?category=$CATEGORY_ID&q=$QUERY

Se você quiser aprender mais sobre a API do _Mercado Livre_, veja a [documentação](https://developers.mercadolivre.com.br/pt_br/itens-e-buscas).

### Exemplo de requisição de busca

```
"https://api.mercadolibre.com/sites/MLB/search?category=MLB1055&q=Motorola"
```

O retorno desse endpoint será algo como o exemplo que temos [neste arquivo](exemplo-motorola.json).

⚠ **ATENÇÃO! Se der erro de CORS aperte `ctrl + shift + r` no seu navegador** ⚠

### Linter

Para garantir a qualidade do seu código de forma a tê-lo mais legível, de mais fácil manutenção e seguindo as boas práticas de desenvolvimento nós utilizamos neste projeto os linters `ESLint` e `Stylelint`. 

### Usando o Trello como ferramenta kanban

Uma forma para organizar o projeto em grupo foi a utilização do Trello.

Para duplicar, basta seguir os passos:

- Acesse o [link do board](https://trello.com/b/9mjukxCq/frontend-online-store)
- Abra o menu no canto superior direito
- Selecione "copiar quadros"
- Defina o time do seu grupo e um título para o board
- Clique em `criar`
- Personalize seu novo kanban!

---
### Como utilizar
Entre no terminal, e vá até o diretório que vc quer que esteja este projeto, digite git clone e a url desse repositório (https://github.com/AndersonPedrosa35/project-frontend-online-store), assim que carregar, entre no diretório do projeto e digite ```npm install``` para baixar e carregar as dependências do projeto.

Entre no diretório do projeto, e digite ```yarn start``` ou ```npm start```

Então o projeto será carregado na porta 3000 da sua rede local(localhost);

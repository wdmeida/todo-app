# todo-app

## Projeto

Projeto desenvolvido durante o [Curso de React+Redux na Udemy](https://www.udemy.com/react-redux-pt). O projeto consiste no desenvolvimento de um sistema de gerenciamento de tarefas. Foi desenvolvido uma API e um APP utilizando para consumo da mesma.

### API

A Api foi desenvolvida utilizando as seguintes tecnologias:

* [Node.js](https://nodejs.org/en/)
* [Node-Restful](https://github.com/baugarten/node-restful)
* [Mongo DB](https://www.mongodb.com/)


### APP

O App foi desenvolvido utilizando as seguintes tecnologias:

* [React](https://facebook.github.io/react/)
* [Redux](http://redux.js.org/)

## Executando o Projeto

### API

Para executar o projeto é necessário que o mongo esteja executando. No terminal, execute o seguinte comando:

```$ mongod```

Abra uma nova instância do terminal, entre na pasta do projeto "todo-app" e dentro da pasta backend, instale as dependências do projeto:

```$ npm install```

Após instalar as dependências, rode a API com o seguinte comando:

```$ npm run production```

A aplicação ficará rodando em segundo plano. Chegou a hora de executar o App.

### APP

Entre no diretório do app, "frontend" e instale as dependências:

```$ npm install```

Após intalar as dependências, execute a aplicação com o seguinte comando:

```$ npm run dev```

Abra o navegador, e acesse ```http://localhost:8080``` para abrir a aplicação.


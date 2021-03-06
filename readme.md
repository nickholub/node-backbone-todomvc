node-backbone-todomvc
===============

Node.js + Backbone.js TodoMVC (fork of [TodoMVC](https://github.com/tastejs/todomvc) with Node.js back-end instead of local storage).
All persistence (CRUD) is in-memory, no database is required.

## Usage

 Install dependencies:

    $ npm install

 Start Node.js server:

    $ node app

 Application will be available at http://localhost:3000

## REST API

 Express.js GET/POST/PUT/DELETE

    app.get('/todos', getTodos);
    app.post('/todos', createTodo);
    app.put('/todos/:id', updateTodo);
    app.delete('/todos/:id', deleteTodo);
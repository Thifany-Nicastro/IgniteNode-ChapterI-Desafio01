# Desafio 01 - Conceitos do Node.js

## :dart: Objetivo

Criar uma aplicação para gerenciar *todos* de usuários.

## :white_check_mark: Requisitos

### Rotas da aplicação
- [x] POST /users
- [x] GET /todos
- [x] POST /todos
- [x] PUT /todos/:id
- [x] PATCH /todos/:id/done
- [x] DELETE /todos/:id

### Específicação dos testes
- [x] Should be able to create a new user
- [x] Should not be able to create a new user when username already exists
- [x] Should be able to list all user's todos
- [x] Should be able to create a new todo
- [x] Should be able to update a todo
- [x] Should not be able to update a non existing todo
- [x] Should be able to mark a todo as done
- [x] Should not be able to mark a non existing todo as done
- [x] Should be able to delete a todo
- [x] Should not be able to delete a non existing todo
# Desafio 01 - Conceitos do Node.js

## :dart: Objetivo ##

Criar uma aplicação para gerenciar *todos* de usuários.

## :checkered_flag: Requisitos ##

### Rotas da aplicação
- [x] POST /users
- [x] GET /todos
- [x] POST /todos
- [x] PUT /todos/:id
- [x] PATCH /todos/:id/done
- [x] DELETE /todos/:id

### Específicação dos testes
- [ ] Should be able to create a new user
- [ ] Should not be able to create a new user when username already exists
- [ ] Should be able to list all user's todos
- [ ] Should be able to create a new todo
- [ ] Should be able to update a todo
- [ ] Should not be able to update a non existing todo
- [ ] Should be able to mark a todo as done
- [ ] Should not be able to mark a non existing todo as done
- [ ] Should be able to delete a todo
- [ ] Should not be able to delete a non existing todo
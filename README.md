# json-server-base

Esse é o repositório com a base de JSON-Server + JSON-Server-Auth já configurada, feita pelo aluno Lucas Reiser.

## Endpoints

Para mais informações (https://www.npmjs.com/package/json-server-auth).

### Cadastro

POST /register

O endpoint irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.

### Usuários

GET /users/userId

O endpoint irá mostrar todos os dados do usuário.

### Login

POST /login

O endpoint é usado para realizar login com um dos usuários cadastrados na lista de "Users".

### Food

POST /foods

O endpoint é usado para realizar cadastrar novos pratos, sendo separados por vegetarianos ou
não vegetarianos. É necessário ter o token de autorização para fazer o cadastro.

GET /foods

O endpoint mostra os pratos cadastrados.

### Drink

POST /drinks

O endpoint é usado para realizar cadastrar novas bebidas, sendo separados por alcoolicos ou
não alcoolicos. É necessário ter o token de autorização para fazer o cadastro.

GET /drinks

O endpoint mostra as bebidas cadastrados.

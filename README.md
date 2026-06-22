# Modelagem-arquitetura-MEAM
# BetCup - Sistema de Gerenciamento de Apostas Esportivas

## Descrição

O BetCup é um sistema web desenvolvido utilizando a arquitetura MEAN (MongoDB, Express, Angular e Node.js), com o objetivo de permitir que usuários realizem apostas em partidas esportivas, acompanhem seus palpites e consultem suas apostas registradas.

O sistema possui funcionalidades de autenticação, cadastro de usuários, gerenciamento de apostas e consulta de apostas realizadas.

 Tecnologias Utilizadas

 Frontend

* Angular
* HTML5
* CSS3
* TypeScript

 Backend

* Node.js
* Express.js

 Banco de Dados

* MongoDB

---

 Estrutura do Projeto

 Frontend

frontend/

├── login/

├── cadastro/

├── apostas/

├── minhas-apostas/

├── services/

├── models/

└── app-routing.module.ts

 Backend

backend/

├── config/

├── routes/

├── controllers/

├── models/

├── middleware/

└── server.js

---

 Funcionalidades

* Cadastro de usuários
* Login de usuários
* Visualização de partidas disponíveis
* Registro de apostas
* Consulta de apostas realizadas
* Gerenciamento de partidas
* Controle de usuários
* Integração com banco de dados MongoDB

---

 Execução do Backend

Instalar as dependências:

npm install

Executar o servidor:

npm start

Servidor disponível em:

http://localhost:3000

---

 Execução do Frontend

Instalar as dependências:

npm install

Executar a aplicação Angular:

ng serve

Aplicação disponível em:

http://localhost:4200

---

 Banco de Dados

O sistema utiliza MongoDB para armazenamento das informações de usuários, partidas e apostas.

Coleções principais:

* usuarios
* jogos
* apostas

---

## Autor

Projeto acadêmico desenvolvido para a disciplina de Desenvolvimento Web utilizando a arquitetura MEAN.


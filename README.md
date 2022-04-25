# Projeto Trabalhando com Middlewares
* Esta é uma aplicação NodeJS que simula a implementação de uma Todo List(lista de tarefas) na parte do Back-End, onde realiza-se o CRUD (Create, Read, Update, Delete) dos todos.

* O objetivo principail foi treinar e aprimorar o manuseio de `Middlewares` dentro NodeJS com a Biblioteca Express.

* Contudo, este é um projeto desenvolvido como Desafio do curso Ignite NodeJS da [Rocketseat](https://www.rocketseat.com.br/).

* Caso goste do projeto marque a estrelinha⭐ para me ajudar 👍 e me siga para ver outros projetos que postar

## 🚀 Technologies
✔ [NodeJS](https://nodejs.org/en/)
<br>
✔ [JavaScript](https://www.javascript.com/)
<br>
✔ [Library Express](https://expressjs.com/)
<br>
✔ [Package Nodemon](https://www.npmjs.com/package/nodemon)
<br>
✔ [Package uuid](https://www.npmjs.com/package/uuid)
<br>
✔ [VS Code](https://code.visualstudio.com/)


## ⚙ Settings
* Segue os comandos para baixar e executar o projeto na sua máquina:
    - `git clone` + `URL do Projeto`: clonar este repositório
    - `cd Pasta_do_Projeto`: acessa a pasta do projeto no terminal
    - `yarn`: para baixar as dependências do projeto
    - `yarn dev`:
        * Executa/Roda o servidor da aplicação.
        * Abra http://localhost:3333 para ver o servidor rodando.
        * O servidor será recarregado se você fizer edições no código, e se tiver algum erro será mostrado.
        > 🚨 Dica
        > Você pode utilizar o [Insômnia](https://insomnia.rest/download) para testar as rotas da aplicação.
    - `yarn test`: para rodar os arquivos de teste da aplicação.


## Routes

### /users(POST)
* Descrição: rota de criação de usuário
* Parâmetros:
    - `name`(string): pelo body da requisição
    - `username`(string): pelo body da requisição

### /users/:id(GET)
* Descrição: rota para buscar dados de um usuário específico.
* Parâmetros:
    - `id`(string): pelo rota da requisição

### /users/:id/pro(PATCH)
* Descrição: rota para atualizar o plano de assinatura de um usuário específico.
* Parâmetros:
    - `id`(string): pelo rota da requisição

### /todos(GET)
* Descrição: rota que devolve os todos de um usuário específico.
* Parâmetros:
    - `username`(string): pelo headers da requisição

### /todos(POST)
* Descrição: rota para criar um todo na conta de um usuário específico.
* Parâmetros:
    - `username`(string): pelo headers da requisição
    - `title`(string): pelo body da requisição
    - `deadline`(string): pelo body da requisição

### /todos/:id(PUT)
* Descrição: rota para atualizar um todo específico de um usuário.
* Parâmetros:
    - `username`(string): pelo headers da requisição
    - `id`(string): pela rota da requisição (id do todo)
    - `title`(string): pelo body da requisição
    - `deadline`(string): pelo body da requisição

### /todos/:id/done(PATCH)
* Descrição: rota para colocar todo como feito.
* Parâmetros:
    - `username`(string): pelo headers da requisição
    - `id`(string): pela rota da requisição (id do todo)

### /todos/:id(DELETE)
* Descrição: rota para deletar um todo específico de um usuário.
* Parâmetros:
    - `username`(string): pelo headers da requisição
    - `id`(string): pela rota da requisição (id do todo)


## ✍ Author
<img alt="PabloXT14" title="PabloXT14" src="https://avatars.githubusercontent.com/u/71723595?s=400&u=f7a1ec0c2e1f7cd1acf79f61043dbc75b1079de6&v=4" width="100">
<p>
    Made with 💜 by PabloXT14
</p>
<p align="left">
    <a href="https://www.linkedin.com/in/pabloalan/" target="_blank">
        <img align="center" src="https://img.shields.io/badge/LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="Linkedin Pablo Alan" />
    </a>
    <a href="mailto:pabloxt14@gmail.com" target="_blank">
        <img align="center" src="https://img.shields.io/badge/Gmail-FF0000?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail Pablo Alan" />
    </a>
</p>

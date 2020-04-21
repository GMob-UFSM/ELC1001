## Ambiente de desenvolvimento

* [NodeJS](https://nodejs.org/en/download/)
* Ambiente para testar APIs REST (e.g. [Postman](https://www.postman.com/downloads/), [Insomnia](https://insomnia.rest/download/), etc.)

## Executando o projeto

1. Navegue até a pasta raíz do seu projeto no terminal
2. Execute `npm install` para instalar as dependências
3. Execute `npm start` para iniciar o projeto
    * Por padrão, a API está configurada para executar na porta 3000
    * Quando você fizer mudanças nos arquivos do projeto, o script detectará e reiniciará a API automaticamente
    * Para parar a execução da API, use `Ctrl + C`

## Informações extras

Como o login e registro não estão implementados, se você precisa construir uma rota que usa as informações da variável `req.user` (usuário que está fazendo a requisição), você pode controlar essas dados modificando o objeto criado no arquivo `auth.js` (na pasta `middleware`).

Você pode importar o arquivo [`gmob-moda.postman_collection.json`](gmob-moda.postman_collection.json) no POSTMAN para ter uma ideia de quais são as rotas e quais parâmetros são passados para ela.

O arquivo `.env.dev` já contem um acesso de desenvolvimento a um banco de dados MongoDB hospedado no [MongoDB Atlas](https://www.mongodb.com/cloud/atlas), que é um ambiente que disponibiliza instâncias do Mongo de forma gratuita.

Você pode usar esse banco disponibilizado ou criar o seu próprio, basta modificar o arquivo `.env.dev` com o acesso ao seu banco de dados (seja ele local ou hospedado na nuvem).
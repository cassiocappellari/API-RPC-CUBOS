# API-RPC-CUBOS

<div align="center">
  [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/e8d418ee169e2dfac74a#?env%5BDevelopment%5D=W3sia2V5IjoiYmFzZVVSTCIsInZhbHVlIjoiaHR0cDovL2xvY2FsaG9zdDo1MDAwIiwiZW5hYmxlZCI6dHJ1ZX1d)
</div>

## :interrobang: Sobre:
O desafio se refere ao desenvolvimento de uma API RPC para gerenciamento de uma fila de pessoas.


## :pushpin: Rotas:
- Cadastrar usuário: ```baseURL/createUser``` (Método POST)
- Adicionar à fila: ```baseURL/addToLine``` (Método POST)
- Buscar usuário na fila: ```baseURL/findPosition``` (Método GET)
- Ver fila: ```baseURL/showLine``` (Método GET)
- Filtrar fila: ```baseURL/filterLine``` (Método GET)
- Tirar da fila: ```baseURL/popLine``` (Método DELETE)


## :construction_worker: Como usar:

Para clonar e executar essa aplicação você vai precisar dos seguintes softwares instalados em seu computador: 
- [Git](https://git-scm.com/)
- [Node](https://nodejs.org/en/)


### :electric_plug: Instalar dependências e rodar a aplicação:

```bash
# Clone este repositório:
$ git clone https://github.com/i-ramoss/API-RPC-CUBOS.git

# Entre no repositório:
$ cd API-RPC-CUBOS

# Instale as dependências:
$ npm install

# Inicie o servidor
$ npm start

# A aplicação estará rodando na porta 5000 (http://localhost:5000/)
```

Feito com :green_heart: por **Ian Ramos** :fire: [Entre em contato!](https://www.linkedin.com/in/ian-ramos/)

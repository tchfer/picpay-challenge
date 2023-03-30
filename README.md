# desafio-angular-picpay
Desenvolvimento do desafio para frontends com angular da Picpay

-------------------------

# **Desafio Frontend PicPay**

## Setup do projeto

- Angular CLI: 12.1.4
- Node: 12.20.2
- Angular: 12.1.4

## Como Rodar?

- Instale as dependências usando o comando `npm install`
- Na raiz do repositório, rode este comando `ng serve` para iniciar o servidor de desenvolvimento.
- A Aplicação estará disponível na porta `http://localhost:4200/`

<br/>

### **API**

Para o seu desafio ser mais interativo, estamos utilizando um mock de API, chamado JSON Server. Portanto, é necessário que você instale-o globalmente em sua máquina para ter os recursos da lib.

**1 -** Como instalar? <br/>
`npm install -g json-server`

**2 -** e para rodar (deixar aberto em uma outra aba do terminal, para que ele fique escutando suas ações de CRUD!), digite o seguinte comando na RAÍZ do projeto: `npm run api`

Link para mais detalhes: https://github.com/typicode/json-server

**Rotas:** <br />
`GET: /tasks`<br />
`POST: /tasks`<br />
`PUT: /tasks`<br />
`PATCH: /tasks`<br />
`DELETE: /tasks`<br />

`GET: /account` <br />
`POST: /account` <br />
`PUT: /account` <br />
`PATCH: /account` <br />
`DELETE: /account` <br />
<br/>

### **Models**:<br />

Tasks - Esta é sua lista com agenda de pagamentos. Aqui você cadastrar, editar e excluir um pagamento.<br />
` { "id": 5, "name": "Anthea Pundy", "username": "apundy4", "title": "Software Engineer III", "value": 177.19, "date": "2021-01-01T14:09:51Z", "image": "https://robohash.org/quiaautomnis.png?size=150x150&set=set1", "isPayed": true },`

Account - você usará este usuário para Login da plataforma<br />
`{ "id": 0, "name": "usuario", "email": "usuario@gmail.com", "password": "usuario" }`

<br/>

**Usuário para utilizar no login:**<br />
` "email": "usuario@gmail.com", "password": "usuario"`
<br/>

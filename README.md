Este projeto foi criado em [NodeJS](https://nodejs.org/en/docs/). 

## Introdução

Está API REST foi desenvolvida com fins estudantis, você terá total acesso para consulta-lá tanto no seu localhost, quanto ao [Site](http://35.199.116.113/).

## `Baixando arquivos necessários`

Você precisará fazer dowload do Node.js(https://nodejs.org/en/download/).
Ao instalar o Node.js, na raiz do projeto digite o seguinte comando:

```bash
npm i
```

## Dando Start

Na raiz do projeto digite o seguinte comando

```bash
npm run start
```
## Sobre as Rotas

**Alunos**
Get de alunos/Listar todos os alunos:

`localhost:3000/alunos`

Show de alunos/Ver aluno específico:
`localhost:3000/alunos/<id>`

**Usuários**
Get de usuário/Listar todos os usuários:
`localhost:3000/users`

### Requisições de edição de valores na API / indicado usar o [Insomnia](https://insomnia.rest/download/).

POST de usuário/Registrar um usuário:
`Ao utilizar um método POST na rota /users/ irá ser registrado um usuário`

PUT de usuário/Registrar um usuário:
`Ao utilizar um método PUT na rota /users/ o usuário será atualizado`

DELETE de usuário/Registrar um usuário:
`Ao utilizar um método DELETE na rota /users/ o usuário será atualizado`




## Relevante

Neste projeto me aprofundei nas seguintes tecnologias e métodos aplicáveis:

- NodeJS
- Express
- MariaDB
- SQL
- Criação de Tokens
- Criação e aplicação de Middlewares
- Integrações JSON
- Criação de modelos de banco de dados
- Utilização do multer para carregar fotos
- Fazer deploy da aplicação

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
# endpoints

Os seguintes endpoints estão configurados:

## Home - não há nada aqui

- `/` - GET

## Usuários (users)

- `/users` - DELETE - Apaga o usuário logado
- `/users` - PUT - Atualiza o usuário logado
- `/users` - POST - Cria um usuário
- `/users/:id` - GET - Mostra o usuário do ID enviado (rota desativada)
- `/users` - GET - Mostra todos os usuários (rota desativada)

**Dados para usuários (JSON)**

```
{
	"nome": "nome válido",
	"password": "senha válida",
	"email": "email_valido@email.com"
}
```

## Tokens

- `/tokens` - POST - Obtém o token JWT

**Dados para tokens (JSON)**

```
{
	"email": "admin@email.com",
	"password": "123456"
}
```

## Aluno

- `/alunos/:id` - DELETE - Apaga o aluno do ID enviado
- `/alunos/:id` - PUT - Atualiza o aluno do ID enviado
- `/alunos` - POST - Cria um aluno
- `/alunos/:id` - GET - Mostra o aluno do ID enviado
- `/alunos` - GET - Mostra todos os alunos


**Dados para tokens (JSON)**

```
{
	"nome": "Nome",
	"sobrenome": "Sobrenome",
	"email": "email@email.com",
	"idade": "50",
	"peso": "80.04",
	"altura": "1.90"
}
```

## Fotos

Atenção aqui, esse é o único endpoint `multipart/form-data` para envio de arquivos.

- `/fotos` - POST - Recebe um arquivo de foto JPG ou PNG e um `aluno_id`.

**Dados para fotos (multipart/form-data)**

```
{
	"foto": (ARQUIVO.PNG|


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

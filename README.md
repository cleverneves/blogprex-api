# Blogpress API

API para aplicações de Blog.

## Pré-requisitos:
- Node.js
- Docker
- Docker-compose

## Como utilzar o projeto:

```sh
# Subindo o ambiente
docker-compose up -d
```

## Variaveis de ambiente

```sh
DB_PORT=
DB_NAME=
DB_HOST=
DB_USER=
DB_PASS=

API_PORT=
DATABASE_URL=postgres://${DB_USER}:${DB_PASS}@${DB_HOST}:${DB_PORT}/${DB_NAME}
```

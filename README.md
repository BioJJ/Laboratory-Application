# Laboratory

## Description

Tarefa:

- Construir uma API para manutenção de laboratórios e exames.

Funcionalidades desejadas:

Laboratório:

- cadastrar um novo laboratório;
- obter uma lista de laboratórios ativos;
- atualizar um laboratório existente;
- remover logicamente um laboratório ativo.
- Exames:
  - cadastrar um novo exame;
  - obter uma lista de exames ativos;
  - atualizar um exame existente;
  - remover logicamente um exame ativo.
- Associação:
  - associar um exame ativo à um laboratório ativo;
  - desassociar um exame ativo de um laboratório ativo;
    **Importante:**
  - Um exame pode estar associado a mais de um laboratório;
  - O cadastro de um laboratório/exame é considerado ativo e recebe um `id` gerado automaticamente.

## Running the app

```bash
# development
$ docker-compose up -d


# API documentation (Swagger)
$ localhost:3000/api


```

#

## Aplicações:

- API -> https://github.com/BioJJ/laboratory-api
- API with Microservice -> https://github.com/BioJJ/laboratory-microservice-external

## Technologies used

The technologies or tools listed below figure between the most relevant on the development of this project:

- Docker version 19.03.12
- Docker-compose version 1.27.4

BACKEND

- Framework: NestJs + TypeOrm
  "@nestjs/common": "^7.6.15",
  "@nestjs/core": "^7.6.15",
  "@nestjs/platform-express": "^7.6.15",
  "@nestjs/swagger": "^4.8.0",
  "reflect-metadata": "^0.1.13",
  "rimraf": "^3.0.2",
  "rxjs": "^6.6.6",
  "swagger-ui-express": "^4.1.6"

## Stay in touch

- Author - https://www.linkedin.com/in/jefferson-coelho/
- Website - https://github.com/BioJJ
- Twitter - https://twitter.com/bio_jefferson

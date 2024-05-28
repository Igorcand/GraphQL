# GraphQL project with go lang module gqlgen

## Sobre o Projeto ##

Este projeto implementa uma API GraphQL utilizando a biblioteca gqlgen em Go. A API permite consultar e manipular dados de cursos e catecorias através de um esquema GraphQL bem definido. O projeto demonstra como configurar e utilizar gqlgen para criar um servidor GraphQL robusto e escalável.

## Tecnologias usadas ##
- Go
- Qglgen
- Sqlite
  

## Como rodar ##

```bash

go mod init github.com/igorcand/GraphQL

go run github.com/99designs/gqlgen init

go mod tidy

go run github.com/99designs/gqlgen generate

go run cmd/server/server.go

```

## Autor ##

Igor Cândido Rodrigues

https://www.linkedin.com/in/igorc%C3%A2ndido/

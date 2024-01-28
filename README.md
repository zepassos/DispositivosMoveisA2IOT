# Projeto DeMalas | mba-es-25-grupo-01

## Sobre o projeto

Este projeto é voltado para o desenvolvimento da aplicação DeMalas.

## Objetivo

## Integrantes



## Tecnologias utilizadas



## Configuracao e execucao backend

1. Instale o PostgreSQL em sua máquina (última versão): https://www.enterprisedb.com/downloads/postgres-postgresql-downloads, e defina a master password. Caso queria acessar a base com mais praticidade pode ser instalado o pgAdmin

2. Acesse o projeto deMalas.API > Connected Services > Secrets.json, e insira a chave para conexão com o firebase

3. Acesse o projeto deMalas.API > appsettings.json e busque por ConnectionStrings > Postgresql > Password e coloque a senha definida no master do pgsql

4. No terminal do projeto deMalas.Infrastructure execute o comando 'update-database', isso fará com que o Entity Framework se contecte com o postgresql e crie o banco de dados da aplicação

5. Para rodar o app, execute o projeto deMalas.API

## Documentacao API

Swagger: https://localhost:7244/swagger/index.html

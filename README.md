# Projeto DeMalas | mba-es-25-grupo-01

## Sobre o projeto

Este projeto é voltado para o desenvolvimento da aplicação DeMalas.

O DeMalas foi pensado para possibilitar conectar viajantes de todos os cantos do mundo que queiram criar, compartilhar, planejar experiências, dicas e recomendações.

A plataforma proporciona uma comunidade engajada e inspiradora para explorar o mundo e criar memórias inesquecíveis.

## Objetivo

Nosso projeto visa melhorar a experiência de viagem, abordando desafios comuns, como conectar viajantes com destinos semelhantes, facilitar interações entre viajantes, fornecendo conteúdo em fóruns com o objetivo de simplificar e melhorar toda a experiência dos viajantes.

## Integrantes

* Celina Valmo
* Douglas Camargo
* José Passos
* Laura Rosa
* Sayonara Alice

## Tecnologias

#### Frontend
* Next.js
* Node.js

#### Backend
* C#
* .NET Core
* Postgresql

## Configuração e execução frontend (de-malas-frontend)

1. Crie na raiz do projeto um arquivo .env.local e defina as sequintes variáveis

* NEXT_PUBLIC_FIREBASE_API_KEY
* NEXT_PUBLIC_FIREBASE_AUTH_DOMAIN
* NEXT_PUBLIC_FIREBASE_PROJECT_ID
* NEXT_PUBLIC_FIREBASE_STORAGE_BUCKET
* NEXT_PUBLIC_FIREBASE_MESSAGING_SENDER_ID
* NEXT_PUBLIC_FIREBASE_APP_ID
* NEXT_PUBLIC_BACKEND_API_URL

2. Após isso execute o comando **npm install**

3. Ainda na raiz do projeto execute o comando **npm run dev**

## Configuração e execução backend (de-malas-backend)

1. Instale o PostgreSQL em sua máquina (última versão): https://www.enterprisedb.com/downloads/postgres-postgresql-downloads, e defina a master password. Caso queria acessar a base com mais praticidade pode ser instalado o pgAdmin

2. Acesse o projeto deMalas.API > Connected Services > Secrets.json, e insira a chave para conexão com o firebase

3. Acesse o projeto deMalas.API > appsettings.json e busque por ConnectionStrings > Postgresql > Password e coloque a senha definida no master do pgsql

4. No terminal do projeto deMalas.Infrastructure execute o comando **update-database**, isso fará com que o Entity Framework se contecte com o postgresql e crie o banco de dados da aplicação

5. Para rodar o app, execute o projeto deMalas.API

## Documentação API

Swagger: https://localhost:7244/swagger/index.html

<img width="1430" alt="image" src="https://github.com/zepassos/DispositivosMoveisA2IOT/assets/57042115/fda63df3-2dda-468b-831e-21eb9bbeeec1">


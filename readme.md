# Library App - Fullstack

## Backend - node.js & express

Backend simples com mock de dados e apenas comandos do tipo read.

## Frontend - AngularJS

Frontend utilziando AngularJS para visualização das informações dos livros existente no backend.

## Docker & Docker Compose

Solução containerizada e composta para simplificar a execução e teste.

## Comandos

docker-compose up --build # Cria e inicializa ambos os containers utilzando as configurações do arquivo .env

## Dados do banco

O bando sqlite utilizado nos testes foi incluido junto ao codigo da aplicação. Toda via, é possível gerar novamente o banco executando os seguintes scripts.

yarn sequelize-cli db:migrate
yarn sequelize-cli db:seed:all

## Portas de acesso

A porta configurada para acesso ao frontend foi a porta 8080.
A porta configurada para o acesso a api foi a porta 8000.
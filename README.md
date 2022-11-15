# Comunicação de Sistemas com GraphQL.

## Introdução
Este projeto consiste no entendimento dos conceitos de uma comunicação de sistemas com GraphQL. Este framework criado pelo Facebook, possibilita o cliente solicitar aquilo que ele precisa para renderizar na tela. 

## Configuração do projeto
Ele pode ser baixado conforme abaixo:
```sh
$ git clone https://github.com/SamuelDevMobile/GranphQL_Golang.git
```
Abra-o no seu VSC (Visual Studio Code)
![Captura de Tela 2022-11-02 às 00 48 46](https://user-images.githubusercontent.com/26841238/199391008-6f05552d-ef78-4e67-8206-2d5e123e1950.png)

Use o comando abaixo para acessar o data.db. Se não tiver o sqlite3, instale-o, é bem simples.
```sh
sqlite3 data.db
```
Você precisará criar duas tabelas.
```sh
create table categories (id string, name string, description string);
```
```sh
create table courses (id string, name string, description string, category_id string);
```
Se você já tiver golang instalado, pode executar o comando.
```sh
go run cmd/server/server.go
```
<img width="665" alt="Captura de Tela 2022-11-15 às 01 49 30" src="https://user-images.githubusercontent.com/26841238/201829124-839e9c8b-5567-4c06-a1d9-a6001a77d3c8.png">

Divirta-se ;)
<img width="1435" alt="Captura de Tela 2022-11-15 às 01 50 43" src="https://user-images.githubusercontent.com/26841238/201829250-f00f5ac5-6edb-49f6-a5de-e495602e75ae.png">

Se não tiver o golang instalado, recomendo usar docker para criar um container em golang :)

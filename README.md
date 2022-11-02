# Comunicação de Sistemas com GraphQL.

## Introdução
Este projeto consiste no entendimento nos conceitos de uma comunicação de sistemas chamada GraphQL. Este framework criado pelo Facebook, possibilita o cliente solicitar aquilo que ele precisa para renderizar na tela. 

## Configuração do projeto
Ele pode ser baixado conforme abaixo:
```sh
$ git clone https://github.com/SamuelDevMobile/GranphQL_Golang.git
```
Abra-o no seu VSC (Visual Studio Code)
![Captura de Tela 2022-11-02 às 00 48 46](https://user-images.githubusercontent.com/26841238/199391008-6f05552d-ef78-4e67-8206-2d5e123e1950.png)

Você precisará criar duas tabelas usando o sqlite3. Se não tiver o sqlite3, instale-o, é bem simples.
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
Se não tiver o golang instalado, recomendo usar docker para criar um container em docker :)

## Ambiente de teste
```
Feito localmente parça. ;)
```

## Volte sempre :)

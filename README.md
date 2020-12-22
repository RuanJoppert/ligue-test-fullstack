# Ligue test fullstack
Teste para seleção de desenvolvedores fullstack

## Objetivo do teste
Desenvolver uma API REST em Nodejs que utilize os métodos **GET, POST, PUT, DELETE**

## Especificação
Monte uma base de usuários com a seguinte estrutura:

```
nome: varchar
sexo: char
idade: integer
hobby: varchar
datanascimento: date
```

Utilize o ​banco de dados​ de sua preferência para armazenar os dados que a API irá
consumir.

## API endpoints

```
GET /developers
Codes 200
```
Retorna todos os desenvolvedores

```
GET /developers?
Codes 200 / 404
```
Retorna os desenvolvedores de acordo com o termo passado via querystring e
paginação

```
GET /developers/{id}
Codes 200 / 404
```
Retorna os dados de um desenvolvedor

```
POST /developers
Codes 201 / 400
```
Adiciona um novo desenvolvedor

```
PUT /developers/{id}
Codes 200 / 400
```
Atualiza os dados de um desenvolvedor

```
DELETE /developers/{id}
Codes 204 / 400
```
Apaga o registro de um desenvolvedor

## Vaga frontend
Caso deseje se candidatar para frontend deverá criar também uma aplicação que consuma os endpoints da api, UI/UX fica a critério do desenvolvedor, porém deverá ser SPA (single-page application)
 
## Entrega
A aplicação deve rodar em docker, possuir um script para geração das tabelas no banco de dados e TESTES UNITÁRIOS.

Após finalizado o link do projeto, por e-mail, no github com explicação no README

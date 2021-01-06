# Big Game Survey 
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/math-thomaz/sds1/blob/master/LICENSE) 

# Sobre o projeto

https://sds1-math.netlify.app/

Big Game Survey é uma aplicação full stack web construída durante a 1ª edição da **Semana DevSuperior** (#sds1), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

A aplicação consiste em uma pesquisa de preferência de games, onde os dados são coletados em uma API e depois são listados no app web, que também apresenta um dashboard com gráficos baseados nestes dados.

## Aspectos Técnicos (Front end)
Para o desenvolvimento, foi utilizado o combo Javascript (ES6) + Typescript + React. Utilizamos conceitos de componentização para elementos fixos como Header, os Hooks useEffect e useState para obter e armazenar os dados e Axios para realizar as requisições à API.

## Layout web
![Web 1](https://github.com/math-thomaz/assets/blob/master/DevSuperior/sds1/img1.PNG)

![Web 2](https://github.com/math-thomaz/assets/blob/master/DevSuperior/sds1/img2.PNG)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Front end
- HTML / CSS / JS (ES6) / TypeScript
- ReactJS
- Apex Charts
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

```bash
## Back end
Pré-requisitos: Java 11

## Entre na pasta do projeto back end:
cd backend

## Execute o projeto:
./mvnw spring-boot:run

## Front end web
Pré-requisitos: npm / yarn

## Entre na pasta do projeto front end web:
cd front-web

## Instale as dependências:
yarn install

## Execute o projeto:
yarn start
```

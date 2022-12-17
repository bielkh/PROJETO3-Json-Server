
# Projeto individual, Módulo 3 - Json Server | Gabriel da Silva Rocha

O objetivo do terceiro projeto individual do programa Programadores Cariocas é criar uma fake API Rest em JSON Server.


## Autor
- [Gabriel da Silva Rocha](https://twitter.com/biel2kh)


## Funcionalidades

- [Clientes](https://restaurantebiel.onrender.com/clientes)
- [Chefes de cozinha](https://restaurantebiel.onrender.com/chefes)
- [Funcionários](https://restaurantebiel.onrender.com/funcionarios)
- [Menu](https://restaurantebiel.onrender.com/menu)


## Demonstração
https://restaurantebiel.onrender.com/ 
Se quiser clonar esse repositório, você precisa fazer isso: 
- 1 - Clone meu repositório
- 2 - no terminal, faça "npm -i"
- 3 - depois faça ng serve
- E pronto. Happy Coding!



## Rotas Personalizadas
Rotas personalizadas utilizadas para manipulação de informações


| metodo  | caminho       | response                           |
| :---------- | :--------- | :---------------------------------- |
| `GET (see all)` | `/"nome do caminho"/list	` | 	/:recurso|
| `GET` | `	/"nome do caminho"/get/:id	` | /:recurso/:id|
| `POST` | `/"nome do caminho"/create		` | 	/:recurso|
| `PUT` | `/"nome do caminho"/update/:id	` | /:recurso/:id|
| `DELETE` | `/"nome do caminho"/delete/:id` | /:recurso/:id|

###Nomes dos caminhos:
- Funcionarios
- Clientes
- Chefes
- Menu

## Referência

 - [Digital Ocean](https://www.digitalocean.com/community/tutorials/json-server)
 - [Dev.To](https://dev.to/youssefzidan/deploying-fake-back-end-server-database-using-json-server-github-and-heroku-1lm4#:~:text=%20Deploying%20Fake%20Back-End%20Server%20%26%20DataBase%20Using,3%20Creating%20the%20server%0ACreate%20account%20on...%20More%20)
 - [Render](https://dashboard.render.com/)
 - [NPM](https://www.npmjs.com/package/json-server)

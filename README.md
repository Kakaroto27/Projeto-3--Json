# Projeto individual, Módulo 3 - Json Server | André Carlos S. da Silva

O objetivo do terceiro projeto individual do programa Programadores Cariocas é criar uma fake API Rest em JSON Server.


## Autor
- [André Carlos S. da Silva]


## Funcionalidades

- [Bebidas](https://mod3-json.onrender.com/Bebidas)
- [Petiscos]https://mod3-json.onrender.com/Petiscos)
- [Funcionários](https://mod3-json.onrender.com/funcionarios)
- [users](https://mod3-json.onrender.com/menu)


## Demonstração
https://mod3-json.onrender.com
Se quiser clonar esse repositório, você precisa fazer isso: 
- 1 - Clone meu repositório
- 2 - no terminal, faça "npm -i"
- 3 - depois faça ng serve
- E pronto. Happy Coding!



## Rotas Personalizadas
Rotas personalizadas utilizadas para manipulação de informações


| metodo  | caminho       | exemplo                      |
| :---------- | :--------- | :---------------------------------- |
| `GET (see all)` | `/"nome do caminho"/	` | 	/Bebidas|
| `GET` | `	/"nome do caminho"/get/:id	` | /Petiscos|
| `POST` | `/"nome do caminho"/create		` | 	/users/"ele vai criar automaticamente uma id nova"|
| `PUT` | `/"nome do caminho"/update/:id	` | /Bebidas/"mudar o que tem dentro da id de escolha"|
| `DELETE` | `/"nome do caminho"/delete/:id` | /users/delete/"id que você quer deletar"|

### Nomes dos caminhos:
- Funcionarios
- users
- Bebidas
- Petiscos

## Referência

 - [Digital Ocean](https://www.digitalocean.com/community/tutorials/json-server)
 - [Dev.To](https://dev.to/youssefzidan/deploying-fake-back-end-server-database-using-json-server-github-and-heroku-1lm4#:~:text=%20Deploying%20Fake%20Back-End%20Server%20%26%20DataBase%20Using,3%20Creating%20the%20server%0ACreate%20account%20on...%20More%20)
 - [Render](https://dashboard.render.com/)
 - [NPM](https://www.npmjs.com/package/json-server)

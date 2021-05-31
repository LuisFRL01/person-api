# Person API

O Projeto consiste em uma API REST com Spring Boot feito para o bootcamp Code Anywhere da Digital Innovation One.
Para o desenvolvimento da API foi foi utilizado o [Spring initializr](https://start.spring.io/) para criar o projeto com 
suas dependências, a versão 11 do Java, Gradle e a IDE Intellj IDEA Community Edition.
[Link do projeto no heroku.](https://personapi-live-dio.herokuapp.com/)

## API Endpoints
### GET
* /api/v1/people - Recupera todas as pessoas cadastradas.
* /api/v1/people/id - Recupera uma pessoa pelo o id informado.
### POST
* /api/v1/people - Cria uma pessoa.
### Body
~~~javascript
{
    "firstName": "joão",
    "lastName": "silva",
    "cpf": "0000000000",
    "birthDate": "dd/MM/yyyy",
    {
        "type": "HOME"
        "number": "00000000000"
    }
}
~~~
### PUT
* /api/v1/people/id - Altera uma pessoa pelo o id informado.
### DELETE
* /api/v1/people/id - Deleta uma pessoa pelo o id informado.

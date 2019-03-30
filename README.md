# ApiRest
Api Rest com Swagger

## Iniciando

Faça o Download do arquivo zip (apirest.zip) e extraia o seu conteúdo dentro de seu Workspace.

### Pré-requisistos

* EclipseIDE
* Postgresql

### Instalação e Configuração
No Eclipse, Importe o apirest.zip em: **File > Import > Maven > Existing Maven Projects > Next** - 
Selecione a pasta que foi extraída no Workspace e aperte em **Finish.**

Após importado o projeto, o eclipse fará o download de todos os pré-requisitos do projeto. Espere concluir essa etapa.

No Eclipse, procure pela pasta **src/main/resources**. Dentro terá um arquivo com o nome **application.properties**. Neste arquivo é necessário configurar o database, user e password do postgres. O padrão é **postgres** para tudo (database, user e password).

### Consumindo a API
O Swagger-UI foi implementado com a aplicação REST para se ter uma API Online e navegavel com a descrição dos métodos utilizados (cadastrar, remover, atualizar e listar usuários) além de poder consumir a API pelo browser.

Primeiramente, Inicie a aplicação

No Browser, digite: (http://localhost:8080/swagger-ui.html)

### Desenvolvido Com

* [Maven](https://maven.apache.org/)
* [Swagger](https://swagger.io/)
* [Spring Boot](https://spring.io/projects/spring-boot)

## Autor

* **Alan Giovanni**

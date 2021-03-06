# ApiRest
Api Rest com Spring Boot e Swagger-Ui.

## Iniciando

Faça o Download do arquivo zip (apirest.zip) e extraia o conteúdo dentro de seu Workspace do Eclipse.

### Pré-requisistos

* EclipseIDE
* JDK 8.0
* Postgresql

### Instalação e Configuração
No Eclipse, Importe a pasta apirest em: **File > Import > Maven > Existing Maven Projects > Next** - 
Selecione a pasta que foi extraída no Workspace e aperte em **Finish.**

Após importado o projeto, o eclipse fará o download de todas as dependências do projeto. Espere concluir essa etapa.

Na aba Project Explorer, procure pela pasta **src/main/resources** dentro do projeto apirest. Haverá um arquivo com o nome **application.properties**. Neste arquivo é necessário configurar o database, user e password do postgres. O padrão é **postgres** para tudo (database, user e password).

### Consumindo a API
O Swagger-UI foi implementado com a aplicação REST para se ter uma API Online e navegável com a descrição dos métodos utilizados (cadastrar, remover, atualizar e listar usuários) e exemplos de como utilizar também, além de poder consumir a API pelo próprio browser.

Primeiramente, Inicie a aplicação no Eclipse, em seguida vá para http://localhost:8080/swagger-ui.html

**Obs:** A Matrícula é gerada automaticamente no cadastro, portanto não é necessário informá-la. Para atualizar um usuário, a matrícula precisa ser correspondente, todos os campos restantes são atualizáveis.

### Métodos HTTP utilizados na API
* PUT /api/atualizar: Atualiza um usuário específico


* POST /api/cadastrar: Cadastra um usuário com o Hash da Senha em SHA-256.


* DELETE /api/deletar/{matricula}: Deleta um usuário específico através da matricula


* GET /api/listar: Retorna uma lista de usuarios


* GET /api/listar/{nome}: Retorna um único usuario pelo nome

### Desenvolvido Com

* [Maven](https://maven.apache.org/)
* [Swagger](https://swagger.io/)
* [Spring Boot](https://spring.io/projects/spring-boot)

## Autor

* **Alan Giovanni**

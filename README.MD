##### **Aula 01 - Construção back-end de uma aplicação de To-Do List**

- [X] Conceitos essenciais de Spring Boot
- [X] Configurar o Ambiente de desenvolvimento com Java e Maven
- [X] Instalar extensões e criar a estrutura do projeto

##### Aula 02 - Integração ao Banco de Dados

- [X] Conhecimentos em Java e Spring Framework
- [X] Integrações com Banco de Dados
- [X] Seguir na construção do projeto com ferramentas modernas

* [X] Inclusão da Library para o Maven "Lombok"

  - https://projectlombok.org/
  - Atalho para Getters / Setters

###### 
    @Data

    publicclassUserModel{

    privateStringusername;

    privateStringname;

    privateStringpassword;

    //getters / setters

    }

* [X] Configuração do Bando de Dados- Instalar as dependencias

- http://h2database.com/html/main.html
- https://spring.io/projects/spring-data-jpa

##### **Aula 03 - Implementando segurança nos dados do usuário**

- [X] Aspectos cruciais de Segurança e Estruturação, para garantir um acesso seguro à sua Aplicação

- Criptografar password

- library : https://github.com/patrickfav/bcrypt

- Implementar a listagem de To Do

##### **Aula 04 - Atualizando tarefas e validação de rotas**

* [X] Aprimorar a Aplicação focando em segurança e funcionalidades essenciais
* [X] Atualizar tarefas e validação de Rotas
* [X] Enriquecer a interatividade do usuário com a Aplicação

##### **Aula 05 - Deploy do Back-End**

* [X] Validações e ferramentas
* [X] Try Catch
* [X] Deploy da Aplicação Spring Boot coom RENDER
* [X] Maneiras de Executar a aplicação -

  - Executar a aplicação direto no terminal  :  mvn spring-boot:run

  * Na pasta JAVA Projects > botão de Debug

  - Na pasta TdoListApplication.java > Run

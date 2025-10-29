🧩 Cadastro de Usuário — CRUD com Spring Boot

Este projeto é um exemplo simples de CRUD (Create, Read, Update, Delete) de usuários, desenvolvido em Java com Spring Boot.
O objetivo é compreender o funcionamento básico de um backend REST, utilizando o Postman para testar as requisições.

🚀 Tecnologias utilizadas

Java 17+

Spring Boot

Spring Data JPA

Lombok

H2 Database (ou outra de sua escolha)

Postman (para testes de API)

📁 Estrutura do Projeto
src/
 └── main/java/com/javanauta/cadastro_usuario/
      ├── business/
      │    └── UsuarioService.java
      ├── controller/
      │    └── UsuarioController.java
      └── infrastructure/
           ├── entity/
           │    └── Usuario.java
           └── repository/
                └── UsuarioRepository.java

                Observações

As exceções são lançadas com mensagens simples (RuntimeException) apenas para fins didáticos.

O projeto pode ser facilmente expandido com DTOs, tratamento de exceções global (ExceptionHandler) e validações com Bean Validation.

Ideal para quem está aprendendo os fundamentos de Spring Boot CRUD + REST API.

📬 Testes com Postman

Você pode importar as requisições no Postman manualmente:

Inicie o projeto com mvn spring-boot:run

Acesse: http://localhost:8080/usuario

Use os métodos POST, GET, PUT e DELETE conforme os exemplos acima

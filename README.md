# Projeto E-Diaristas

## Descrição

O projeto "E-Diaristas" foi desenvolvido durante a Imersão Multi Stack da TreinaWeb, utilizando o framework Spring Boot e seguindo o modelo MVC (Model-View-Controller). Este projeto se destaca por sua arquitetura robusta e funcionalidade como uma API REST.

## Dependências do Projeto

- Spring Boot
- Spring Web MVC
- Thymeleaf
- Spring Data JPA
- Bean Validation

## Tecnologias utilizadas

[![My Skills](https://skillicons.dev/icons?i=html,css,js,python,php,java,mysql,figma)](https://skillicons.dev)

## Dependências de Desenvolvimento

- Spring Boot Devtools
- Lombok

## Requisitos

- Java 17
- Maven 3.8

## Como testar esse projeto na minha máquina?

Clone este repositório e entre na pasta do projeto.

```sh
git clone https://github.com/Davi504/-projeto-e-diaristas
cd /-projeto-e-diaristas
```

Atualize as configurações de acesso ao banco de dados no arquivo [application.properties](src/main/resources/application.properties).

```properties
spring.datasource.url=jdbc:mysql://host:porta/banco_de_dados
spring.datasource.username=usuario
spring.datasource.password=senha
```

Execute o projeto através do Maven.

```sh
mvn spring-boot:run
```

Acesse a aplicação em [http://localhost:8080/admin/servicos](http://localhost:8080/admin/servicos).

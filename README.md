# Projeto E-Diaristas

## Descrição
O projeto "E-Diaristas" foi desenvolvido durante a Imersão Multi Stack da TreinaWeb, utilizando o framework Spring Boot e seguindo o modelo MVC (Model-View-Controller). Este projeto se destaca por sua arquitetura robusta e funcionalidade como uma API REST.

## Processo de Desenvolvimento
O desenvolvimento deste projeto foi dividido em várias etapas:
1. **Planejamento e design do banco de dados**: Estruturação das tabelas e relações.
2. **Implementação do backend usando Spring Boot**: Desenvolvimento das APIs e lógica do servidor.
3. **Desenvolvimento do frontend com Thymeleaf**: Criação da interface do usuário.
4. **Integração do frontend e backend**: Conexão das funcionalidades entre cliente e servidor.
5. **Testes e depuração**: Garantia de qualidade e correção de bugs.
6. **Implantação do projeto em um servidor**: Configuração para produção.

## Dependências do Projeto
- Spring Boot
- Spring Web MVC
- Thymeleaf
- Spring Data JPA
- Bean Validation

## Dependências de Desenvolvimento
- Spring Boot Devtools
- Lombok

## Tecnologias Utilizadas
[![My Skills](https://skillicons.dev/icons?i=html,css,bootstrap,java,spring)](https://skillicons.dev)

## Requisitos
- Java 17
- Maven 3.8

## Como Rodar o Projeto na Sua Máquina
1. Clone este repositório e entre na pasta do projeto:
    ```sh
    git clone https://github.com/Davi504/-projeto-e-diaristas
    cd /-projeto-e-diaristas
    ```

2. Atualize as configurações de acesso ao banco de dados no arquivo [application.properties](src/main/resources/application.properties):
    ```properties
    spring.datasource.url=jdbc:mysql://host:porta/banco_de_dados
    spring.datasource.username=usuario
    spring.datasource.password=senha
    ```

3. Execute o projeto através do Maven:
    ```sh
    mvn spring-boot:run
    ```

4. Acesse a aplicação em [http://localhost:8080/admin/servicos](http://localhost:8080/admin/servicos)

## Licença
Este projeto é licenciado sob os termos da licença MIT.

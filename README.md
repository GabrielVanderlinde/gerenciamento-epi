# Gerenciamento de EPIs

Aplicação de linha de comando para cadastro de equipamentos de proteção individual (EPIs), controle de estoque e acompanhamento de empréstimos e devoluções. Projeto desenvolvido para praticar desenvolvimento backend com Java e Spring Boot.

## Tecnologias

- Java 17
- Spring Boot
- Spring Data JPA e Hibernate
- MySQL
- Maven

## Funcionalidades

- Cadastro e gerenciamento de EPIs
- Controle de empréstimos e devoluções
- Acompanhamento de estoque
- Persistência dos dados em banco relacional
- Interface via terminal (CLI)

## Como executar

### Pré-requisitos

- JDK 17 ou superior
- Maven
- MySQL

Clone o repositório e acesse a pasta:

```bash
git clone https://github.com/GabrielVanderlinde/gerenciamento-epi.git
cd gerenciamento-epi
```

Configure a conexão com o banco de dados nas propriedades da aplicação. Exemplo:

```properties
spring.datasource.url=jdbc:mysql://localhost/epi_db
spring.datasource.username=SEU_USUARIO
spring.datasource.password=SUA_SENHA
```

Compile e execute:

```bash
mvn clean install
mvn spring-boot:run
```

> Ajuste as configurações de conexão de acordo com o ambiente local. Não publique credenciais reais.

## Estrutura conceitual

```text
Interface CLI → Serviços → Repositórios → MySQL
```

## Objetivo do projeto

Consolidar conhecimentos de Java, Spring Boot, persistência de dados e organização da lógica de negócio.

## Autor

Gabriel Vanderlinde
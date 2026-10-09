# Gerenciamento de EPIs

Sistema de gerenciamento de EPIs e controle de empréstimos desenvolvido em Java 17 e Spring Boot. Interface via terminal (CLI) com persistência em MySQL.

## Overview

Aplicação CLI para gerenciamento profissional de equipamentos de proteção individual, rastreamento de empréstimos e controle de estoque. Desenvolvida com foco em funcionalidade, persistência de dados e arquitetura limpa.

## Tech Stack

- Java 17
- Spring Boot
- Spring Data JPA
- Hibernate
- MySQL
- Maven

## Features

- Cadastro de EPIs
- Gerenciamento de empréstimos
- Rastreamento de devolução
- Controle de estoque
- Registros de histórico
- Interface CLI intuitiva
- Persistência em MySQL

## Getting Started

### Prerequisites

- Java 17+
- Maven
- MySQL

### Installation

```bash
git clone https://github.com/GabrielVanderlinde/gerenciamento-epi.git
cd gerenciamento-epi
```

### Database configuration

```properties
spring.datasource.url=jdbc:mysql://localhost/epi_db
spring.datasource.username=root
spring.datasource.password=root
```

### Run the application

```bash
mvn clean install
mvn spring-boot:run
```

## Architecture

```text
Controller (CLI)
  ↓
Service Layer
  ↓
Repository (Data Access)
  ↓
MySQL Database
```

## Notes

This project demonstrates practical Spring Boot development with CLI interface, business logic implementation, and database persistence.

## License

MIT

## Author

Gabriel Vanderlinde

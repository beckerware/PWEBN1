# PWEBN1

Este repositório contém o projeto da disciplina **Programação Web N1**, desenvolvido como parte do curso de Sistemas de Informação. O objetivo é aplicar conceitos de desenvolvimento web utilizando Java e o framework Spring Boot.

## Tecnologias Utilizadas

- **Java 17+**
- **Spring Boot**
- **Maven**
- **Thymeleaf**
- **Spring MVC**
- **Spring Data JPA**
- **H2 Database** (para testes locais)

## Estrutura do Projeto

O projeto segue a estrutura padrão de aplicações Spring Boot:

```
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── beckerware/
│   │   │           └── pwebn1/
│   │   │               ├── controllers/
│   │   │               ├── models/
│   │   │               ├── repositories/
│   │   │               └── services/
│   │   └── resources/
│   │       ├── templates/
│   │       └── application.properties
│   └── test/
├── pom.xml
├── mvnw / mvnw.cmd
└── HELP.md
```

## Como Executar

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/beckerware/PWEBN1.git
   cd PWEBN1
   ```

2. **Execute a aplicação:**

   ```bash
   ./mvnw spring-boot:run
   ```

3. **Acesse no navegador:**

   ```
   http://localhost:8080
   ```

## Licença

Este projeto está licenciado sob a [Licença MIT](LICENSE).

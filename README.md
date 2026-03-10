# Forum Hub - Challenge ONE (Back-End)

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)

## 📝 Descrição do Projeto

O **Forum Hub** é uma API REST desenvolvida como desafio final da especialização de Back-End do programa **Oracle Next Education (ONE)** em parceria com a **Alura**. 

O objetivo é replicar o funcionamento de um fórum de discussões, permitindo que usuários criem tópicos, respondam a dúvidas, visualizem discussões e gerenciem seus perfis, focando no desenvolvimento de operações CRUD (Create, Read, Update, Delete) e seguindo as melhores práticas do modelo REST.

---

## 🚀 Funcionalidades

A API permite realizar as seguintes operações:

- **Tópicos:**
  - Cadastrar um novo tópico (título, mensagem, autor e curso).
  - Listar todos os tópicos (com paginação e ordenação).
  - Detalhar um tópico específico.
  - Atualizar os dados de um tópico.
  - Excluir um tópico.
- **Segurança:**
  - Autenticação de usuários via Token JWT.
  - Restrição de acesso a endpoints sensíveis.
- **Validações:**
  - Regras de negócio para evitar tópicos duplicados.
  - Tratamento de erros e exceções customizados.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem:** Java 17+
- **Framework:** Spring Boot 3
- **Gerenciamento de Dependências:** Maven
- **Persistência de Dados:** Spring Data JPA / Hibernate
- **Banco de Dados:** MySQL
- **Segurança:** Spring Security + JWT (JSON Web Token)
- **Documentação:** SpringDoc (Swagger UI)
- **Migrações:** Flyway

---

## 📋 Pré-requisitos

Antes de começar, você precisará ter instalado em sua máquina:
- [Java JDK 17+](https://www.oracle.com/java/technologies/downloads/)
- [Maven](https://maven.apache.org/)
- [MySQL](https://www.mysql.com/)

---

## ⚙️ Configuração e Execução

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/GermanoMacieira/Challenge_ONE__Forum_Hub.git](https://github.com/GermanoMacieira/Challenge_ONE__Forum_Hub.git)

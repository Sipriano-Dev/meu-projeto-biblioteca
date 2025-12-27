# 📚 Biblioteca API

API REST para gerenciamento de livros, desenvolvida com Spring Boot e PostgreSQL.

Este projeto começou como uma aplicação simples e está sendo evoluído gradualmente com boas práticas, conceitos aprendidos e novas tecnologias, servindo também como projeto de estudo e portfólio.

## 🚀 Tecnologias utilizadas

- Java 21
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Docker
- Maven
- Postman (testes de API)

## 📌 Funcionalidades atuais (CRUD funcional)

- Criar livro
- Listar livros
- Buscar livro por ID
- Atualizar livro
- Deletar livro

## 🧠 Modelagem

Entidade Livro:
- id (Long)
- titulo (String)
- autor (String)
- isbn (String)
- anoPublicacao (Integer)
- criadoEm (LocalDateTime)

## 🔗 Endpoints

POST /livros  
GET /livros  
GET /livros/{id}  
PUT /livros/{id}  
DELETE /livros/{id}

## 🐘 Banco de dados

- PostgreSQL
- Banco: biblioteca
- Porta: 25432 (Docker)

Configuração disponível em application.yml.

## ▶️ Como executar o projeto

1. Subir o PostgreSQL com Docker
2. Configurar o application.yml
3. Executar a aplicação Spring Boot
4. Testar os endpoints via Postman

## 🛠️ Próximos passos planejados

- [x] Estrutura inicial do projeto
- [x] CRUD básico de livros
- [x] Integração com PostgreSQL
- [x] Configuração com Docker
- [ ] DTOs e validação de dados
- [ ] Tratamento global de exceções
- [ ] Paginação e ordenação
- [ ] Documentação com Swagger/OpenAPI
- [ ] Testes unitários
- [ ] Testes de integração
- [ ] Autenticação e autorização (Spring Security)
- [ ] Migrations com Flyway

## 📖 Observação

Este projeto é incremental e reflete minha evolução prática com o ecossistema Spring.
Cada melhoria será implementada de forma consciente, priorizando clareza, boas práticas e aprendizado real.

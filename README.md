# ☕ Projeto CRUD em Java com Spring Boot 🌱

Esse aqui é o meu primeiro projeto CRUD usando **Java**, **Maven** e **Spring Boot**. É literalmente o começo da história: onde eu apanhei, aprendi, xinguei o Maven (um pouco), e no final consegui fazer rodar.

## 🚀 O que o projeto faz?

A aplicação faz o básico (e o necessário):  
Permite **Criar**, **Listar**, **Atualizar** e **Deletar** registros de um banco de dados de usuários.  
Ou seja, um CRUD raiz mesmo.

## 🧱 Tecnologias Utilizadas

| Ferramenta | Para quê |
|-----------|----------|
| **Java 17+** | Linguagem principal |
| **Spring Boot** | Framework que deixou tudo menos caótico |
| **Maven** | Gerenciador de dependências (o vilão e o herói ao mesmo tempo) |
| **Spring Data JPA** | Conversar com o banco sem escrever SQL na marra |
| **H2** | Banco de dados |
| **Postman** | Testar as requisições de forma bonita |

## ⚙️ Como rodar o projeto

1. Clone o repositório:
```
git clone https://github.com/Bifaniii/projeto-crud
```
2. Entre na pasta do projeto:
```
cd projeto-crud
```
3. Rode o projeto:
```
mvn spring-boot:run
```
4. API vai estar disponível em:  
```
http://localhost:8080/
```

## 🧠 Estrutura do Projeto
```bash
src/
└── main/
    ├── java/
    │   └── com/
    │       └── bifani/
    │           └── projeto_crud/
    │               ├── business/
    │               │   └── UsuarioService.java
    │               ├── controller/
    │               │   └── UsuarioController.java
    │               ├── infrastructure/
    │               │   └── entitys/
    │               │       └── Usuario.java
    │               └── repository/
    │                   └── UsuarioRepository.java
    └── resources/
        └── application.properties
````
## 🎯 Objetivo
Aprender a dinâmica do Spring Boot na prática:
Controller → Service → Repository → Banco

## 🔧 Possíveis melhorias
- Adicionar validações (Bean Validation)  
- Documentar com Swagger  
- Criar um front para consumir a API  
- Fazer deploy futuramente

---
> Feito com ☕, paciência e um toque de 🌱.

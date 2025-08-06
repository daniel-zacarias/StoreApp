# 🛍️ Loja de Roupas - Spring Boot com Clean Architecture

Este projeto simula uma **loja de roupas online**, com o objetivo de reforçar conceitos práticos e teóricos de arquitetura de software moderna usando **Java 21** e **Spring Boot**.

---

## 🎯 Funcionalidades

- ✅ CRUD completo de **Usuários**
- ✅ CRUD completo de **Itens (roupas)**
- ✅ Controle de acesso com **roles de usuário** (`ADMIN`, `USER`, etc.)
- ✅ **Autenticação e autorização com Spring Security**
- ✅ Estrutura baseada em **Clean Architecture**
- ✅ Integração com **banco de dados relacional** (PostgreSQL, MySQL, etc.)
- ✅ Estrutura preparada para testes e extensões futuras

---

## 🧱 Arquitetura

A aplicação segue os princípios da **Clean Architecture**, garantindo:

- Separação clara de responsabilidades
- Independência de frameworks
- Alta testabilidade
- Fácil manutenção e escalabilidade

> 📌 Camadas principais:  
`Domain` → `Application (Use Cases)` → `Infrastructure` → `Interface (Controllers)`

## 🚀 Tecnologias Utilizadas

- Java 21 
- Spring Boot 3+
- Spring Security
- Spring Data JPA
- Maven
- PostgreSQL ou MySQL
- JUnit e Mockito
- Docker (Opcional)

---

## 🛠️ Como Rodar o Projeto

### Pré-requisitos

- Java 21 instalado
- Docker (opcional, mas recomendado)
- PostgreSQL rodando localmente (ou em container)
- IDE (IntelliJ, VS Code, etc.)

### Executando com Maven

```bash
./mvnw spring-boot:run
```

### Executando com Docker (exemplo)

```bash
docker-compose up --build
```

---

## 📁 Estrutura de Pastas

```
src/
├── domain/
├── application/
├── infrastructure/
```

---

## ✍️ Autor

Projeto desenvolvido por Zacarias como reforço prático para estudos de arquitetura e desenvolvimento backend.

---

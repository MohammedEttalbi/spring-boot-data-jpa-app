# 🧩 Spring Boot Data JPA App

A clean and modular Spring Boot application demonstrating the integration of **Spring Data JPA** for database access and persistence using the **Java Persistence API**.

---

## 📝 Description

This project provides a structured backend setup using **Spring Boot** and **Spring Data JPA**. It leverages the power of JPA to simplify CRUD operations, entity management, and relational mapping in Java. The application is designed following industry best practices for layered architecture and data access abstraction.

---

## ⚙️ Technologies Used

| Technology         | Purpose                                      |
|--------------------|----------------------------------------------|
| **Java 17+**       | Programming language                         |
| **Spring Boot**    | Application framework and runtime container |
| **Spring Data JPA**| Data access abstraction with JPA             |
| **Maven**          | Dependency and build management              |
| **H2/MySQL** | Relational database (configurable)       |
| **JPA**            | Object-relational mapping                    |
| **Lombok** (optional) | Reducing boilerplate in model classes     |

---

## 🔧 Features

- Entity-relationship modeling
- Repository pattern using `JpaRepository`
- Auto-database schema generation
- CRUD operations with minimal code
- Easy database switching (H2, MySQL)
- Optional REST API (if added later)

---

## ▶️ Getting Started

```bash
# Clone the repository
git clone https://github.com/MohammedEttalbi/spring-boot-data-jpa-app.git

# Navigate to the project folder
cd spring-boot-data-jpa-app

# Run the application (Maven)
mvn spring-boot:run

# Spring Boot Microservices API

A backend application built using **Spring Boot** and **Microservices architecture** to demonstrate scalable, modular, and maintainable RESTful services.  
This project showcases how independent services communicate and handle business logic in a distributed system.

---

## 🚀 Features
- Microservices-based architecture
- RESTful APIs
- Service-to-service communication
- Centralized configuration
- Exception handling and validation
- Scalable and maintainable backend design

---

## 🛠️ Tech Stack
- Java
- Spring Boot
- Spring Web (REST APIs)
- Spring Data JPA
- MySQL
- Maven
- Git

---

## 🏗️ Architecture

The application follows a **microservices architecture**:

- Each service handles a specific business capability
- Services communicate via REST APIs
- Loose coupling between services
- Independent deployment and scalability

This architecture improves flexibility, fault isolation, and maintainability.

---

## 🔄 Workflow

1. Client sends a request to a microservice
2. The microservice processes business logic
3. Data is stored or retrieved from the database
4. Response is returned to the client via REST APIs

---

## ▶️ How to Run

### Prerequisites
- Java 8 or above
- Maven
- MySQL

### Steps
```bash
# Clone the repository
git clone https://github.com/AnishaB123/springboot-microservices-api.git
cd springboot-microservices-api

# Build the project
mvn clean install

# Run the application
mvn spring-boot:run
```

## 👩‍💻 Author
**Anisha Reddy Bojja**  
Master’s in Information Systems & Technology  
University of North Texas

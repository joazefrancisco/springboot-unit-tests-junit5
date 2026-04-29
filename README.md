# 🧪 Spring Boot Unit Tests with JUnit 5

This project demonstrates how to implement **unit testing in a Spring Boot application using JUnit 5**, focusing on service-layer testing, assertions, and test structure best practices.

---

## 📌 Overview

The goal of this project is to practice **unit testing in Spring Boot applications** using JUnit 5.

It focuses on testing business logic in isolation, without relying on external systems such as databases or APIs.

---

## ⚙️ Technologies

- Java 17+
- Spring Boot
- JUnit 5 (JUnit Jupiter)
- Mockito (if applicable)
- Maven

---

## 🧩 What is being tested

This project focuses on:

- Service layer unit tests
- Business logic validation
- Isolated test execution
- Assertions using JUnit 5

---

## Testing Approach

The project follows the **unit testing principle**:

- Tests are isolated from Spring context when possible
- External dependencies are mocked
- Focus on logic validation, not integration

---

## Test Flow

1. Arrange (prepare data)
2. Act (execute method)
3. Assert (validate results)

---

## How to Run Tests

### Run all tests

```bash
mvn test

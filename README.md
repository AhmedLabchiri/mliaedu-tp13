# DemoApplication – Banking SOAP Service

## Description
This project is a **Spring Boot application** demonstrating a simple banking service using **SOAP web services** with **JPA/Hibernate** and an **H2 in-memory database**.  
It provides endpoints to manage accounts (`Compte`) and clients, and exposes a SOAP service via **Apache CXF**.

---

## Features
- SOAP Web Service endpoint: `/ws` exposing `BanqueWS`
- H2 in-memory database for testing
- JPA/Hibernate for entity persistence
- Auto-populated sample data at startup
- Accessible H2 console at `/h2-console`

---

## Technologies Used
- Java 17
- Spring Boot 3.5.9
- Apache CXF
- JPA/Hibernate 6
- H2 Database
- Maven

---

## Getting Started

### Requirements
- Java 17+
- Maven
- IDE like IntelliJ IDEA (optional)

### Build & Run

1. Clone the repository:
```bash
git clone https://github.com/yourusername/demo1.git
cd demo1

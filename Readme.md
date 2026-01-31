# JP Morgan Chase & Co. – Software Engineering Virtual Experience (Forage)

This repository contains my solution for the **JP Morgan Chase & Co. Software Engineering Virtual Experience Program** hosted on **Forage**.  
The project simulates real-world backend engineering tasks commonly handled by software engineers in enterprise environments.

---

## 📌 Project Overview

The simulation focuses on building and debugging a backend system using **Java and Spring Boot**, with integrations involving **Kafka**, **REST APIs**, and an **in-memory database**.  
Each task is validated using automated test cases, mimicking production-level development workflows.

---

## 🛠️ Technologies Used

- **Java 17**
- **Spring Boot**
- **Apache Kafka**
- **RESTful APIs**
- **H2 In-Memory Database**
- **Maven**
- **JUnit / Spring Boot Test**
- **Git & GitHub**

---

## 📂 Project Structure


forage-midas/
│── src/main/java/
│ └── com/jpmc/midascore/
│ ├── controller/ # REST Controllers
│ ├── component/ # Kafka listeners & services
│ ├── entity/ # JPA entities
│ ├── repository/ # Data repositories
│ └── MidasCoreApplication.java
│
│── src/main/resources/
│ └── application.yml
│
│── services/
│ └── transaction-incentive-api.jar
│
│── pom.xml

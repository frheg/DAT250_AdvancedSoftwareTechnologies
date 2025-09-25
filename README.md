# DAT250 Advanced Software Technologies

This repository contains a composite project of various technologies and frameworks learned during the DAT250 Advanced Software Technologies course at HVL, Bergen. The project is not an official assignment, but rather a personal project for learning and experimentation, so it will also contain some non-course-related technologies.

## Project Structure

The project is built on Java Springboot, and will utilize the following technologies:

- **Backend**: Java Springboot (Spring Web)
- **Frontend**: React
- **Database**: MongoDB
- **Vector Database**: Qdrant
- **Graph Database**: Neo4j
- **Cache**: Redis
- **Containerization**: Docker
- **Orchestration**: Kubernetes
- **Message Broker**: RabbitMQ
- **API Testing**: Bruno
- **Build Tool**: Maven
- **Data Serialization**: JSON and XML
- **Dependency Injection**: Spring Framework
- **CI/CD**: GitHub Actions
- **Object-Relational Mapping (ORM)**: Hibernate

## Prerequisites

Before running the project, make sure you have installed all dependencies in the build.gradle file. You can do this by running the following command in the terminal:

```bash
    ./gradlew build
```

This will download and install all necessary dependencies for the project.

## Running the Project

To run the project, you can use the following command:

```bash
    ./gradlew bootRun
```

This will start the Spring Boot application. You can then access the application at `http://localhost:8080`.

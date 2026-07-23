# Employee Service REST API

A RESTful Employee Management API built with Spring Boot and PostgreSQL that demonstrates CRUD operations using a layered architecture.

## Features

- Create Employee
- Get Employee by ID
- Update Employee
- Delete Employee
- Global Exception Handling
- DTO Mapping using ModelMapper
- Spring Data JPA Integration

## Screenshots
<p align="center">
  <img src="/assets/get.png" width="300"/>
  <img src="/assets/put.png" width="300"/>
  <img src="/assets/post.png" width="300"/>
  <img src="/assets/delete.png" width="300"/>
</p>

## Tech Stack

- Java 21+
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate
- PostgreSQL
- Lombok
- ModelMapper

## Architecture

Client
↓
Controller
↓
Service
↓
Repository
↓
PostgreSQL

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /employees | Create Employee |
| GET | /employees/{id} | Get Employee |
| PUT | /employees/{id} | Update Employee |
| DELETE | /employees/{id} | Delete Employee |

## Getting Started

1. Clone the repository
2. Configure PostgreSQL
3. Update `application.properties`
4. Run the Spring Boot application
5. Test endpoints using Postman

<!-- ## Concepts Demonstrated

- RESTful APIs
- Layered Architecture
- DTO Pattern
- Repository Pattern
- Dependency Injection
- Exception Handling
- ModelMapper# Employee Service REST API -->

A RESTful Employee Management API built with Spring Boot and PostgreSQL that demonstrates CRUD operations using a layered architecture.

## Features

- Create Employee
- Get Employee by ID
- Update Employee
- Delete Employee
- Global Exception Handling
- DTO Mapping using ModelMapper
- Spring Data JPA Integration

## Tech Stack

- Java 21+
- Spring Boot
- Spring MVC
- Spring Data JPA
- Hibernate
- PostgreSQL
- Lombok
- ModelMapper

## Architecture

Client
↓
Controller
↓
Service
↓
Repository
↓
PostgreSQL

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /employees | Create Employee |
| GET | /employees/{id} | Get Employee |
| PUT | /employees/{id} | Update Employee |
| DELETE | /employees/{id} | Delete Employee |

## Getting Started

1. Clone the repository
2. Configure PostgreSQL
3. Update `application.properties`
4. Run the Spring Boot application
5. Test endpoints using Postman

<!-- ## Concepts Demonstrated

- RESTful APIs
- Layered Architecture
- DTO Pattern
- Repository Pattern
- Dependency Injection
- Exception Handling
- ModelMapper -->

# User Management System

## Description

A simple User Management System built with Spring Boot and MySQL, providing full CRUD operations for managing users.

## Technologies

- **Spring Boot**
- **Spring Data JPA**
- **MySQL**
- **Swagger** for API Documentation

## Features

- Full CRUD functionality for users
- API documentation via Swagger
- Error handling and validation

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/user-management-system.git
   Set up your MySQL database and update the application.properties file with your credentials.

Build and run the project:

```bash
mvn spring-boot:run
```

Access the API:

```bash
http://localhost:8080/api/users
```

## API Endpoints

- GET /api/users - List all users
- GET /api/users/{id} - Get a user by ID
- POST /api/users - Create a new user
- PUT /api/users/{id} - Update a user
- DELETE /api/users/{id} - Delete a user

## License

MIT License
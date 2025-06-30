# Task Management System

A Spring Boot application for managing tasks with JWT authentication.

## Features

- User authentication and authorization (JWT)
- CRUD operations for tasks
- Task search and filtering
- Email notifications for upcoming tasks
- Role-based access control

## Technologies

- Java 17
- Spring Boot 3.x
- Spring Security
- JPA/Hibernate
- H2 Database (can be configured for MySQL/PostgresSQL)
- Lombok
- ModelMapper
- JJWT

## Setup

1. Clone the repository
2. Configure database in `application.properties`
3. Build the project: `mvn clean install`
4. Run the application: `mvn spring-boot:run`

## API Documentation

Access Swagger UI at: http://localhost:8080/swagger-ui.html

## Default Users

- Admin: username=`admin`, password=`admin123`
- Regular user: username=`user`, password=`user123`

## Database Console

Access H2 console at: http://localhost:8080/h2-console

- JDBC URL: jdbc:h2:mem:task-db
- Username: sa
- Password: (leave empty)
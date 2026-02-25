This project is a RESTful CRUD API built using Spring Boot and MongoDB.
It allows users to create, read, update, and delete records through HTTP endpoints.
The application demonstrates backend development concepts including REST API design,
MongoDB integration, exception handling, and Postman testing.

## Technologies Used

- Java 17
- Spring Boot
- Spring Data MongoDB
- MongoDB
- Maven
- Postman (for API testing)

## Project Structure

- Controller Layer – Handles HTTP requests
- Service Layer – Contains business logic
- Repository Layer – Communicates with MongoDB
- Model – Defines the MongoDB document structure

## API Endpoints

| Method | Endpoint           | Description              |
|--------|-------------------|--------------------------|
| POST   | /api/users        | Create new user          |
| GET    | /api/users        | Get all users            |
| GET    | /api/users/{id}   | Get user by ID           |
| PUT    | /api/users/{id}   | Update user              |
| DELETE | /api/users/{id}   | Delete user              |

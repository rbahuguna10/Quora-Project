# Quora-Project

A Quora-style Q&A backend built with **Spring Boot 3** and **Java 17**. It exposes a RESTful API for users to post questions, answer them, and interact with content — backed by a MySQL database via Spring Data JPA.

This is a personal learning project focused on practicing Spring Boot fundamentals: layered architecture, JPA entity relationships, RESTful endpoint design, and database integration.

## Tech Stack

- **Language:** Java 17
- **Framework:** Spring Boot 3.4.3
- **Build Tool:** Gradle (wrapper included)
- **Database:** MySQL
- **Persistence:** Spring Data JPA, Jakarta Persistence API 3.1
- **Utilities:** Lombok, Spring Boot DevTools
- **Testing:** JUnit 5 (via `spring-boot-starter-test`)


## Prerequisites

- JDK 17 or higher
- MySQL 8.x running locally (or accessible remotely)
- Git

## API Endpoints

Below is the intended set of endpoints (adjust to match the actual controllers in `src/main/java`):

| Method | Endpoint | Description |
| ------ | -------- | ----------- |
| `POST` | `/api/users` | Register a new user |
| `GET` | `/api/users/{id}` | Get user details |
| `POST` | `/api/questions` | Post a new question |
| `GET` | `/api/questions` | List all questions |
| `GET` | `/api/questions/{id}` | Get a question by ID |
| `PUT` | `/api/questions/{id}` | Update a question |
| `DELETE` | `/api/questions/{id}` | Delete a question |
| `POST` | `/api/questions/{id}/answers` | Add an answer to a question |
| `GET` | `/api/questions/{id}/answers` | Get answers for a question |


## Roadmap

- [ ] Authentication and authorization (JWT)
- [ ] Pagination and sorting on question listings
- [ ] Upvote / downvote functionality
- [ ] Comments on answers
- [ ] Search by tags or keywords
- [ ] Swagger / OpenAPI documentation
- [ ] Dockerize the application

## Contributing

This is a personal project, but suggestions and pull requests are welcome. Feel free to open an issue if you spot a bug or have ideas for improvement.

## Author

**Rishabh Bahuguna** — [@rbahuguna10](https://github.com/rbahuguna10)


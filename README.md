# Employee-Management-System-Spring-Boot-Thymeleaf

## Introduction
This project is an Employee Management System built with Spring Boot and Thymeleaf. It provides a web-based interface for managing employees, departments, and user authentication.

## Features
- Employee CRUD operations
- Department management
- User authentication with Spring Security
- etc.

## Technologies Used
- Java 11
- Spring Boot 2.x
- Thymeleaf
- Spring Security
- Maven

## Installation
1. Clone the repository: `git clone https://github.com/yourusername/Employee-Management-System-Spring-Boot-Thymeleaf.git`
2. Install dependencies: `mvn install`
3. Configure database connection in `application.properties`.
4. Start the Spring Boot application: `mvn spring-boot:run`

## Usage
- Access the application at http://localhost:8080
- Log in using the default admin credentials (username: admin, password: admin) or create a new account.
- Manage employees, departments, and users through the web interface.

## Configuration
- Database connection settings: Update `spring.datasource.*` properties in `application.properties`.
- Security configurations: Modify `WebSecurityConfig.java`.

## Folder Structure
- /src
  - /main
    - /java
      - /com.example.ems
        - /controller
        - /model
        - /repository
        - /service
    - /resources
      - /static
      - /templates
      - application.properties
  - /test
    - ...

## Testing
Run tests using: `mvn test`

## Contact
For any questions or support, please contact us at shraddhassalunke2000@email.com.


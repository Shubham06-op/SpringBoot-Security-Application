# SpringBoot-Security-Application

This project is a **Security Application** built using **Spring Boot**. It demonstrates key security features such as user authentication, role-based authorization, and securing API access with **JWT (JSON Web Tokens)**. **PostgreSQL** is used for database management, storing user data and roles.

## Features
1. **User Authentication**: Secure login and session management.
2. **Role-Based Authorization**: Different API access levels based on user roles.
3. **JWT Security**: Protects RESTful APIs with JWT token validation.
4. **PostgreSQL Integration**: User credentials and roles are stored in a relational database.

## Project Structure
```plaintext
src/
 └── main/
     ├── java/
     │   └── com/
     │       └── securityapp/ (Java source files)
     ├── resources/
     │   ├── application.properties (DB configuration)
     │   └── static/ (if any static resources are included)
 └── test/
     └── java/

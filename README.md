## Endpoint API B-Connects-App
Backend API for B-connect-apps, providing secure authentication features such as user registration and login. Empowering the Indonesian Culture App with seamless and reliable user management

## Building from Scratch

To build the B-Connects-App API from scratch, we used the following technologies and tools:

1. **RESTFUL APIs**: Designing APIs with Express.
2. **ORM Prisma**: Database modeling and interaction.
3. **Google Cloud SQL (PostgreSQL)**: Database for storing application data.
4. **JSON Web Tokens (JWT)**: Providing secure authentication.
5. **Bcrypt**: Hashing passwords for user security.
6. **Google Cloud Run**: Deployment of the application.
7. **Unit Testing with Jest and Superbase**: Ensuring the reliability of the codebase.
8. **Documentation with Swagger & Postman**: Documenting API endpoints for easy integration.

## Table of Content

- [Features](#features)
- [Installation](#installation)
- [CRUD Operations](#crud-operations)

## Features

1. **User Management:**
   - Register new users.
   - Authenticate users through a login system.
   - Implement a forgot password mechanism for password recovery.
   - Allow users to reset their passwords securely.

## Installation
# Clone this repository
      git clone https://github.com/AldowadSimanjuntak/BConnect-Backend-API.git
# move to project :
      cd BConnect-Backend-API
# install dependencies
      npm install
# Run the program :
      npm start
And then Server running in :  http://localhost:4000

## Endpoints
The endpoint is `Url+user`

In this local host the endpoint is `http://localhost:4000/user`
## CRUD Operations

# User:

Create: Register a new user using /api/users/register.

Read: Authenticate a user using /api/users/login.

Update: Request a password reset using /api/users/id

Delete: Reset user password using /api/users/id

## Additional Notes
This project is an ongoing effort, and updates may be made regularly to showcase new projects and skills.
Feel free to explore the GitHub repository for the latest code and updates.
## Feedback and Contributions
Feedback and contributions are welcome! If you have suggestions, find issues, or want to contribute to the project, please open an issue or create a pull request on the GitHub repository.

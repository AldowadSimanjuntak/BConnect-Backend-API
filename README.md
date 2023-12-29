## Endpoint API B-Connects-App

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [CRUD Operations](#crud-operations)

## Features

1. **User Management:**
   - Register new users.
   - Authenticate users through a login system.
   - Implement a forgot password mechanism for password recovery.
   - Allow users to reset their passwords securely.

## Installation
# Clone this repository
      https://github.com/AldowadSimanjuntak/BConnect-Backend-API.git
# move to project :
      cd BConnect-Backend-API
# install dependencies
      npm install
# Run the program :
      npm start
And then Server running in :  http://localhost:4000

## Endpoints

## CRUD Operations

# User:

Create: Register a new user using /api/users/register.

Read: Authenticate a user using /api/users/login.

Update: Request a password reset using /api/users/forgot-password.

Delete: Reset user password using /api/users/reset-password.

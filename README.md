# User Management REST API with Flask

---

## Project Overview

This project is a simple RESTful API built using Python's Flask framework to manage user data. The API supports basic Create, Read, Update, and Delete (CRUD) operations on user records, which are stored in-memory while the app is running. It serves as an educational tool for understanding the fundamentals of REST API development with Flask.

The API demonstrates how to:

- Define HTTP endpoints for various operations
- Handle JSON data in requests and responses
- Use standard RESTful conventions for resource management
- Implement Flask routing and error handling
---
## Features

- **GET** `/users`: Retrieve a list of all users.
- **GET** `/users/<user_id>`: Retrieve details of a specific user by ID.
- **POST** `/users`: Add a new user by providing a JSON payload with `name` and `email`.
- **PUT** `/users/<user_id>`: Update an existing user's details using JSON payload.
- **DELETE** `/users/<user_id>`: Delete a user by their ID.
- Simple in-memory data storage (no database required).
- Returns proper HTTP status codes and error messages.
- Easy local setup for learning and testing.

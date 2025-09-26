User Management REST API with Flask
Project Overview
This project is a simple RESTful API built using Python's Flask framework to manage user data. The API performs basic Create, Read, Update, and Delete (CRUD) operations on user records, which are stored in memory while the app is running. It is an educational project designed to demonstrate the fundamentals of REST API development using Flask.

The API is useful for understanding how to:

Define HTTP endpoints to handle different operations

Send and process JSON data in requests and responses

Manage resources using standard RESTful conventions

Work with Flask routing and error handling

Features
GET /users: Retrieve a list of all users.

GET /users/<user_id>: Retrieve details of a specific user by ID.

POST /users: Add a new user by providing a JSON payload with name and email.

PUT /users/<user_id>: Update an existing user's information.

DELETE /users/<user_id>: Delete a user by their ID.

Simple in-memory data storage (no database required).

Clear error messages and HTTP status codes for invalid operations.

Easy to run locally on any machine with Python and Flask installed.

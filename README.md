This project is a practice implementation of the code examples from the book "API for Professionals" by William S. Vincent. The goal of this project is to learn and practice building RESTful APIs using Python and django.

Features
The API provides the following features:

CRUD operations for blog posts
Adding and deleting comments on posts
User authentication and authorization using JWT tokens

The API will be available at http://localhost:8000/api/.

Usage
Authentication
To access the API, users must first authenticate by sending a POST request to the /api/token/ endpoint with their username and password. This will return a JWT token that can be used to authenticate future requests.

CRUD Operations
The API provides the following endpoints for CRUD operations on blog posts:

GET /api/posts/: Get a list of all posts
POST /api/posts/: Create a new post
GET /api/posts/:id/: Get a specific post by ID
PUT /api/posts/:id/: Update a specific post by ID
DELETE /api/posts/:id/: Delete a specific post by ID
License
This project is licensed under the MIT License. See the LICENSE file for details.







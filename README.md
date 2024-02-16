# API for Professionals Book Project

This project is a practical implementation of the code examples from the book "API for Professionals" by William S. Vincent. 
## Features

The API provides the following features:

- CRUD operations for blog posts
- User authentication and authorization token

## CRUD Operations

The API exposes the following endpoints for CRUD operations on blog posts:

| Method | Endpoint                | Description                          |
| ------ | ----------------------- | ------------------------------------ |
| GET    | /api/v1/posts/          | Get a list of all posts              |
| POST   | /api/v1/posts/          | Create a new post                    |
| GET    | /api/v1/posts/:id/      | Get a specific post by ID            |
| PUT    | /api/v1/posts/:id/      | Update a specific post by ID         |
| DELETE | /api/v1/posts/:id/      | Delete a specific post by ID         |

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

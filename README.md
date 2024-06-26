# Take-Home Test: Senior Go Developer
Welcome to our Senior Go Developer take-home test! This test aims to assess your skills and experience with Go programming and related technologies. Please complete the following tasks and submit your solutions within the given timeframe.

## Task 1: Web Service Development
Develop a RESTful API service using Go that allows users to manage a collection of books. The service should support the following operations:

1. GET /books: Retrieve a list of all books.
2. GET /books/{id}: Retrieve a specific book by its ID.
3. POST /books: Create a new book.
4. PUT /books/{id}: Update an existing book.
5. DELETE /books/{id}: Delete a book by its ID.

Each book should have at least the following fields: ID, Title, Author, ISBN, and PublishedDate.

## Task 2: Authentication Middleware
Implement middleware for authentication and authorization in the API service. The middleware should require users to authenticate with an API key included in the request headers. Additionally, implement role-based access control (RBAC) to restrict certain operations (e.g., creating, updating, deleting books) to authorized users only.

## Task 3: Dockerization
Create a Dockerfile for the API service to containerize it. Ensure that the Docker image is optimized for production use and follows best practices. Include instructions in a README.md file on how to build and run the Docker container.

## Task 4: Unit Testing
Write comprehensive unit tests to cover the functionality of the API service and middleware components. Aim for high test coverage and ensure that both positive and negative test cases are considered.

## Task 5: Documentation
Provide clear and concise documentation for your code, including inline comments and a README.md file. Explain how to build, run, and test the API service and any other relevant information.

## Submission Guidelines:
- Fork this repository and work on your solutions there.
- Ensure your code is well-structured, follows best practices, and is adequately documented.
- Submit your solutions via email, including a link to your repository.

## Deadline
Please submit your solution within seven days of receiving this test.

Feel free to reach out if you have any questions or need clarification on any of the tasks. We're looking forward to reviewing your solutions!

# Go Blog API with SQLite and Simple Frontend

This project demonstrates a simple blog post management system using Go for the backend API, SQLite for data storage, and a basic HTML/JavaScript frontend. It's designed to showcase fundamental skills in full-stack development with Go.
## Features

- RESTful API built with Go's standard library
- CRUD operations for blog posts
- SQLite database for persistent storage
- Simple HTML/JavaScript frontend
- CORS support for local development

## Technologies Used

- Go (Golang)
- SQLite
- HTML/CSS/JavaScript (Vanilla)

## Project Structure

- `main.go`: Contains the Go backend code
- `index.html`: Frontend interface
- `blog.db`: SQLite database file (created on first run)

## Setup and Running

1. Ensure you have Go installed on your system.

2. Install the SQLite driver:
   ```
   go get github.com/mattn/go-sqlite3
   ```

3. Run the Go server:
   ```
   go run main.go
   ```

4. Open `index.html` in a web browser.

## API Endpoints

- `GET /posts`: Retrieve all blog posts
- `POST /posts`: Create a new blog post
- `GET /posts/{id}`: Retrieve a specific blog post
- `PUT /posts/{id}`: Update a specific blog post
- `DELETE /posts/{id}`: Delete a specific blog post

## What This Project Demonstrates

1. **Go Backend Development**:
   - Creating a RESTful API using standard library
   - Handling HTTP requests and responses
   - JSON encoding/decoding
   - Error handling and appropriate HTTP status codes

2. **Database Integration**:
   - Connecting to SQLite database
   - Performing CRUD operations with SQL
   - Basic database schema design

3. **Frontend Integration**:
   - Simple HTML/CSS for user interface
   - Vanilla JavaScript for API interactions
   - Asynchronous operations with Fetch API

4. **API Design**:
   - RESTful principles
   - CORS handling for cross-origin requests

5. **Code Organization**:
   - Structuring a Go application
   - Separating concerns (database, HTTP handling, etc.)

6. **Error Handling and Logging**:
   - Proper error responses
   - Basic logging for server operations

## Why This Project Was Created

This project serves as a portfolio piece, demonstrating:

1. Ability to create a full-stack application
2. Understanding of web development concepts
3. Basic database design and integration
4. RESTful API development
5. Frontend and backend communication
6. Code organization and best practices in Go

It's designed to be simple enough to understand quickly, yet comprehensive enough to showcase a range of Go skills.

## Future Improvements

- Add user authentication
- Implement pagination for blog posts
- Add categories or tags to blog posts
- Enhance error handling and input validation
- Implement unit and integration tests
- Use a more robust router for better URL handling

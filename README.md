# GraphQL Job Listing Database

## Project Description
A lightweight Go-based GraphQL API for managing job listings using MongoDB. This project provides a simple, efficient backend for creating, reading, updating, and deleting job postings.

## Features
- **MongoDB integration**
- **GraphQL API support**
- **CRUD operations** for job listings
- **Environment-based configuration**

---

## Setup

### Install dependencies
```bash
go mod tidy
```

### Create a `.env` file:
```env
MONGODB_URI=mongodb://localhost:27017
DATABASE_NAME=joblistings
COLLECTION_NAME=jobs
```

### Run the application
```bash
go run server.go
```

---

## Key Components

- **`database/database.go`**: MongoDB connection and job listing operations.
- **`graph/schema.graphqls`**: GraphQL schema definition.
- **`graph/model/models_gen.go`**: Generated model structures.

---

## Development

- **Requirements**:
  - Go 1.16+
  - MongoDB 4.0+
  - GraphQL knowledge recommended.

---

## Contributing

1. Fork the repository.
2. Create a feature branch.
3. Commit changes.
4. Push and create a pull request.

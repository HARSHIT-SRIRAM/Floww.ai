# Floww.ai Assignment

A RESTful API for managing personal financial records. Users can record their income and expenses, retrieve past transactions, and get summaries by category or time period.

## Technologies Used

- **Backend Framework**: Node.js with Express.js
- **Database**: SQLite
- **Authentication**: JSON Web Tokens (JWT)

## Features

- Record transactions (income and expenses)
- Retrieve all transactions
- Retrieve a single transaction by ID
- Update or delete transactions
- View a summary of transactions with filtering (by category and date)
- JWT-based user authentication

## Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/HARSHIT-SRIRAM/Floww.ai.git
cd Floww.ai
```

example path [How it will look]

C:filePathsWhereItIsStored\Floww.ai

### 2. Installing Dependencies

Make sure you have Node.js installed in your System, then run.

```bash
npm install
```

This will install the required dependencies which are needed to run the project.

### 3. Starting the Server

To start your server in development mode using nodemon, run the following command:

```bash
nodemon
```

### Postman Collection Link

https://www.postman.com/aerospace-participant-95845269/workspace/floww-ai

### Important Points

**Postman Authorization:** When using Postman, make sure to include the Bearer token in the Authorization header for endpoints that require authentication.

**Error Handling:** The API includes basic error handling. If you encounter issues, check the server logs for error messages that can help diagnose problems.

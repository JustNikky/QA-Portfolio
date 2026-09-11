# API Testing - JSONPlaceholder

## Overview

This project contains a collection of manual API tests performed using **Postman** against the JSONPlaceholder REST API.

The goal of the project was to practice API testing fundamentals, including HTTP methods, status codes, JSON request/response bodies, path and query parameters, positive and negative testing, and response validation.

## Tools

- Postman
- JSON
- REST API
- Git / GitHub

## API

**JSONPlaceholder**

Base URL:

`https://jsonplaceholder.typicode.com`

## Tested HTTP Methods

- GET
- POST
- PUT
- PATCH
- DELETE

## Test Scenarios

### GET

- Retrieve a user by ID
- Filter users using a query parameter
- Request a non-existing user and verify `404 Not Found`

### POST

- Create a user with valid data
- Attempt to create a user without a required field
- Attempt to create a user with an invalid data type

### PUT

- Replace/update a user's data

### PATCH

- Update only a specific field of a user

### DELETE

- Delete a user

## Testing Approach

The tests include both positive and negative scenarios.

For each request, I evaluated:

- HTTP status code
- Response body
- Expected vs. actual result
- JSON structure and data types
- API behavior with invalid input
- Whether the requested operation appeared to be performed successfully

## Key Findings

During negative testing, JSONPlaceholder returned successful responses even when:

- a required field was missing
- an incorrect data type was provided

For example, the API returned `201 Created` when creating a user without an email address or when providing an invalid value for an age field.

This demonstrates why a successful HTTP status code alone is not sufficient to determine whether a test has passed.

JSONPlaceholder also does not permanently persist changes made through POST, PUT, PATCH, and DELETE requests. Therefore, successful responses were not treated as proof of permanent data persistence.

In a real-world application, persistence could be verified with a subsequent GET request and, where appropriate, by checking the database.

## Test Results

| Test Case | Result |
|---|---|
| GET user by ID | PASS |
| GET users by website | PASS |
| GET non-existing user | PASS |
| POST user with valid data | PASS |
| POST user without email | FAIL |
| POST user with invalid age type | FAIL |
| PATCH user email | PASS |
| PUT user | PASS |
| DELETE user | PASS |

## Conclusion

This project demonstrates practical experience with manual REST API testing in Postman, including CRUD operations, positive and negative test scenarios, JSON validation, HTTP status code verification, and analysis of actual API behavior against expected results.

## Project Structure

```text
api-testing/
├── README.md
├── test-cases/
│   └── API_Test_Cases.md
├── test-results/
│   └── Test_Execution.md
└── postman/
    └── JSONPlaceholder.postman_collection.json

# Postman Simple Books API – QA Project

This project demonstrates end-to-end API testing using Postman on the Simple Books public API.

The project was implemented as part of a QA training assignment, focusing on practical API testing skills and common HTTP methods.

## API Reference
- API Base URL: https://simple-books-api.glitch.me
- API Documentation:  
  https://github.com/vdespa/introduction-to-postman-course/blob/main/simple-books-api.md

## Project Overview
The collection covers core API testing scenarios, including authentication, data creation, updates, and validations.

## Tested Scenarios
- API status validation
- Retrieve all books
- Filter books using query parameters
- Generate authentication token
- Place an order with authentication
- Negative test: place an order without authentication
- Retrieve all orders
- Update an existing order
- Verify updated order data

## Technologies & Tools
- Postman
- REST API
- JavaScript (Postman tests & assertions)
- Bearer Token Authentication

## Validation Types
- HTTP status code validation (200, 201, 204, 401)
- Response body assertions
- Data verification after update (GET after PATCH)

## How to Run the Project
1. Import the Postman collection file into Postman
2. Set the `BaseURL` variable
3. Generate an auth token
4. Run the requests in order (Q1–Q10)

## Notes
- The project follows a real API testing flow: Create → Read → Update → Verify
- PATCH requests return `204 No Content`, therefore updates are verified using a GET request





# API Security Testing Evidence

This folder contains screenshots collected during the read-only API security assessment performed for **Future Interns Cyber Security Task 3**.

## API Tested

**JSONPlaceholder**

https://jsonplaceholder.typicode.com/

The API was tested using **Postman** with safe, read-only requests.

## Evidence Files

### 3S1.png
Screenshot showing the response from the `/posts` endpoint.

### 3S2.png
Screenshot showing the HTTP response headers returned by the API.

### 3S3.png
Screenshot showing the response from the `/posts/1` endpoint.

### 3S4.png
Screenshot showing the response from the `/users` endpoint.

### 3S5.png
Screenshot showing the response from the `/users/1` endpoint.

## Purpose

These screenshots provide supporting evidence for the observations documented in the API Security Risk Analysis report.

## Testing Scope

The testing was limited to:

- Public test API endpoints
- Read-only GET requests
- Request and response inspection
- HTTP headers
- Response data exposure
- Authentication and authorization observations

No exploitation, bypass attempts, flooding, or attacks against private or production systems were performed.

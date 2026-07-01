# HTTP Fundamentals

## GET
Requests data from the server.

Examples:
- Opening a website
- Downloading a file
- Viewing a profile

---

## POST
Sends data to the server.

Examples:
- Login
- Registration
- Sending a comment
- Changing a password

---

## Common HTTP Status Codes

200 OK
Request completed successfully.

301 Moved Permanently
Resource has moved.

401 Unauthorized
Authentication required.

403 Forbidden
Access denied.

404 Not Found
Requested resource doesn't exist.

500 Internal Server Error
Server-side problem.

---

## HTTP Headers

Host
Specifies which website is requested.

User-Agent
Identifies the client application.

Accept
Specifies acceptable response formats.

Accept-Language
Preferred language.

Connection: keep-alive
Keeps TCP connection open for multiple requests.

---

## Cookies & Sessions

Cookie
Stored in the browser.
Usually contains Session ID.

Session
Stored on the server.
Contains information about the authenticated user.

Authentication Flow

Login
↓
POST
↓
Server validates credentials
↓
Creates Session
↓
Generates Session ID
↓
Stores Session ID inside Cookie
↓
Browser sends Cookie with every request

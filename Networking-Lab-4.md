
## HTTP Methods
- GET - Request data from a server.
- POST - Send data to a server.
Examples:
- Open website → GET
- Login → POST
- Register → POST
- Download file → GET
---
## Request Headers
Host
User-Agent
Accept
Accept-Language
Connection
---
## Response Headers

Content-Type
Content-Length
Server
Set-Cookie
---
## Cookies & Sessions
Cookie:
Stored inside the browser.
Usually contains a Session ID.

Session:
Stored on the server.
Contains information about the authenticated user.
Authentication Flow:

Login

POST

Server validates credentials

Creates Session

Generates Session ID

Sends Set-Cookie

Browser stores Cookie

Browser sends Cookie with every request

Laboratory Activity: Module 5 – Lesson 1

Building and Testing a Secure API with Laravel 13
Name: Escosura, Cheessy Gabriel C.
Section: BSICT - 3B
GitHub Repository: https://github.com/cescosura-pixel/laravel13-secure-api-lab

Screenshot Checklist
All eight Postman tests were successfully completed, with the expected HTTP status codes and response outputs.
- 01 – Public API (200 OK)
- 02 – Register User (201 Created)
- 03 – Login (200 OK)
- 04 – Profile Without Token (401 Unauthorized)
- 05 – Profile With Token (200 OK)
- 06 – Invalid Login (422 Unprocessable Content)
- 07 – Logout (200 OK)
- 08 – Revoked Token (401 Unauthorized)

REFLECTION:
A 401 Unauthorized response means that a request does not have a valid authentication token, while a successful authenticated profile request returns 200 OK and displays the user's information. After logout, the access token is revoked, preventing it from being used again to access protected endpoints.
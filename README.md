# API-Testing-of-ReqRes
1. API Name:
Reqres (https://reqres.in/)

2. Test Objective:
To evaluate the functionality, response structure, and reliability of the Reqres API for mock user data and testing purposes.

3. Test Scenarios & Findings:
- User Data Retrieval (GET /users) – Returns paginated user data with structured JSON responses.
- User Creation (POST /users) – Successfully accepts input but does not persist data.
- User Update (PUT /users/:id) – Simulates update; response structure remains consistent.
- User Deletion (DELETE /users/:id) – Returns success status, but user data remains unchanged.
- Authentication (POST /login, POST /register) – Returns mock tokens but does not verify real credentials.
- Error Handling – Proper HTTP status codes (404 for invalid users, 400 for bad requests).

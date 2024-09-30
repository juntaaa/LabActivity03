$ curl -X POST http://localhost:3000/register \
-H "Content-Type: application/json" \
-d '{"name": "John Doe", "email": "john.doe@example.com", "password": "123456"}'
{"message":"User registered successfully"}

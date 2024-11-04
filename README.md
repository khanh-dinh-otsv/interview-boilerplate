# Interview livecode
## Requirements:
### Backend (NestJS):
Create an authentication API:
 - POST `/api/auth/login`: Accepts username and password and returns a mock JWT token if credentials are correct.
 - Use hardcoded credentials (e.g., username: admin, password: password123).
 - Create a simple middleware to verify the JWT token for protected routes (can be a mock check). ( nice to have )
### Frontend (Next.js):
Create two pages:
 - Login Page (/login): Contains a form to accept username and password and sends a login request to the NestJS backend. Save the received JWT token in localStorage or state.
 - Protected Page (/dashboard): Displays a welcome message if the user is authenticated. Redirects to /login if the user is not authenticated.

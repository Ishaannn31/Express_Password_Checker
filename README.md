# Express_Password_Checker

Express Password Checker is a simple Node.js project that demonstrates the use of Express for handling HTTP requests and middleware for password authentication. This project serves as a basic example of setting up an Express server, using middleware for request processing, and serving static HTML files based on user authentication.
Features

    Middleware for checking passwords.
    Serving different HTML files based on authentication status.
    Simple form handling using body-parser.

Setup

    Clone the repository
    Install dependencies : npm i / npm install
    Run the application: node index.js
    Open your browser:
    Navigate to http://localhost:3000 to view the application.

Usage

    Landing Page

    Access the root route / to see the landing page (index.html).

    Password Check
        Enter a password in the form.
        The application checks if the password matches the hardcoded password (LordIshan).
        If the password is correct, the user is redirected to secret.html.
        If the password is incorrect, the user is redirected to reply.html.

Middleware

The password checking middleware function is defined to validate the password from the POST request body. If the password is correct, the userIsAuthorised flag is set to true, otherwise, it logs the password and proceeds to the next middleware or route handler.
    

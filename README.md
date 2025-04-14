🔐 Registration and Login System (MERN Stack)
A secure and fully functional registration and login system built using MongoDB, Express, and Node.js. This project implements robust JWT authentication, input validation, and password hashing to ensure user data is safely stored and managed.

🔒 Features
User registration with email and password

Secure login with JWT-based authentication

Password hashing using bcrypt

Input validation to prevent malformed data

Protected routes for authenticated users only

MongoDB integration for user data storage

🛠️ Tech Stack
Node.js

Express.js

MongoDB with Mongoose

JWT (JSON Web Tokens)

bcrypt for password hashing

Express Validator for input validation

📁 Getting Started
Clone the repository
git clone https://github.com/rhtmishra/Registration_and_login.git

Install dependencies
npm install

Set up environment variables
Create a .env file and add:

ini
Copy
Edit
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
Start the server
node app.js
or
npm start

📌 This project is backend-only. You can connect it with any front-end (React, Angular, etc.) to build a full-stack auth system.


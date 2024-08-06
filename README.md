This is a simple RESTful API for user authentication using Node.js, Express, and MongoDB. It allows users to register and login.

Installation -

Clone the repository:

git clone https://github.com/dhruv-agarwal-ids/Rest-API.git

cd user-auth-api

Install the dependencies:

npm install

Start MongoDB:

Ensure MongoDB is running on your system or update the MongoDB connection string in index.js to connect to your MongoDB instance.

Start the server:

node index.js

The server will start on http://localhost:3000.

API Endpoints -

Register a New User

URL: /api/users/register

Method: POST

Body:

{
  "username": "your-username",
  
  "password": "your-password"
}

Login a User

URL: /api/users/login

Method: POST

Body:

{
  "username": "your-username",
  
  "password": "your-password"
}


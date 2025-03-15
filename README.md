This API is a simple RESTful API built with Node.js and Express.js that handles user authentication using JWT (JSON Web Token). 
It allows users to register, log in, and access a protected route. When a user registers, their password is encrypted using bcrypt.js 
before being stored in memory. During login, the API checks the credentials and, if valid, generates a JWT token, which must be sent 
in the authorization header to access the protected route. The protected route verifies the token to ensure only authenticated users 
can enter. The API was tested using Postman, and it does not require a database, as it stores user data temporarily. This project 
follows RESTful principles and can be expanded with a database and additional features in the future.

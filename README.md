# movieApp_1
Project built as part of CareerFoundry's Full-Stack-Web-Development-Course to demonstrate the mastery of full-stack JavaScript develpoment with MERN stack.


This README contains technical and content-related details about the server-side and client-side component of a React application called "movieApp". The REST API for "movieApp" is hosted online on Heroku and provides logged in users with access to information about different movies, directors, and genres. For detailed information about all the provided features, see Features sector. The server-side of the application (server, business logic, business layers) consists of a REST API and architected database built using JavaScript, Node.js, Express, and MongoDB.

The REST API can be accessed via commonly used HTTP methods (GET, POST, PUT, DELETE). CRUD is used to retrieve data from the database and store that data in a non-relational way.

# Server-side
## Features
- Allows users to see a list of all movies in the database
- Allows users to get detailed information about a single movie by movie title
- Allows users to get detailed information about a genre by genre name
- Allows users to get detailed information about a director by name
- Allows new users to create an user account
- Allows existing users to update their user info or to delete their account
- Allows existing users to add or remove movies to/from their list of favorites
## Dependencies:
The server-side component of the application relies on the following dependencies:

- bcrypt: Used for password hashing and encryption.
- body-parser: Middleware for parsing incoming request bodies.
- cors: Middleware for enabling Cross-Origin Resource Sharing.
- express: Web application framework for Node.js.
- express-validator: Middleware for validating and sanitizing input data.
- jsonwebtoken: Used for generating and verifying JSON Web Tokens (JWT) for authentication.
- mongoose: Object-Data Mapping (ODM) library for MongoDB.
- morgan: HTTP request logger middleware.
- passport: Authentication middleware for Node.js.
- passport-jwt: Passport strategy for handling JWT-based authentication.
- passport-local: Passport strategy for handling local username/password authentication.
- uuid: Library for generating universally unique identifiers (UUIDs).



pleaes review my documentation at:

https://documenter.getpostman.com/view/22600836/2s847HPsk2 

heroku at:

https://my-movies-rushdi.herokuapp.com/


<img width="841" alt="Screen Shot 2022-10-18 at 5 51 11 PM" src="https://user-images.githubusercontent.com/103061146/196551809-d0eac5c7-f6ff-46dd-86d7-149ad27b8c34.png">

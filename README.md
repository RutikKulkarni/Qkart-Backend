# QKart Backend

- Live URL: [QKart Backend](https://qkart-backend-xxgz.onrender.com)
- Backend live URL: [QKart Backend - Vercel](https://qkart-backend-sand.vercel.app/)

QKart is an E-commerce application offering a variety of products for customers to choose from.

![Qkart-BAckend](https://github.com/RutikKulkarni/rutikkulkarni2001-ME_QKART_BACKEND/assets/86470947/d3d6dfad-55e4-4007-ada8-b7e22c2150bf)


## QKart Layered Architecture

![QKart Layered Architecture](https://github.com/RutikKulkarni/rutikkulkarni2001-ME_QKART_BACKEND/assets/86470947/12683dda-1d16-4a54-a2a6-7f21baf67bc4)



### Deploy the QKart backend server

#### Scope of Work

- Created a MongoDB instance on MongoDB Atlas cloud and uploaded products data to the cloud DB.
- Deployed the QKart Node.js app to Heroku.
- Deployed the QKart React frontend to Netlify after configuring it to use the deployed Node.js backend.

#### Skills used

MongoDB Atlas, Deployment, Heroku, Netlify

### Complete the checkout logic using TDD

#### Scope of Work

- Added Jest-based assertions to unit tests for checkout requirements provided.
- Implemented the checkout logic in a Test-driven development style.
- Utilized integration tests to find and resolve bugs on integrating checkout logic to the application.

#### Skills used

Test-driven development, Unit testing, Integration testing, Jest framework

### Implement APIs related to shopping cart

#### Scope of Work

- Implemented the GET/POST/PUT API endpoints for a user’s shopping cart.
- Improved the `GET /v1/users` endpoint by supporting filtering for user address via query parameters.

#### Skills used

REST APIs, Filtered API Queries

### Secure API endpoints and implement register/login APIs

#### Scope of Work

- Implemented logic to generate short-lived JWT tokens.
- Set token authentication strategy by using the Passport library.
- Secured `GET /v1/users` endpoint using token authentication.
- Created POST APIs for user registration and login.
- Implemented password authentication to facilitate register/login flow.

#### Skills used

REST APIs, Token authentication, JWT Token, Password authentication, Hashing

## JWT Token authentication flow for QKart APIs

![JWT Token authentication flow for QKart APIs](https://github.com/RutikKulkarni/rutikkulkarni2001-ME_QKART_BACKEND/assets/86470947/1b4451e1-700e-475d-b5ec-80a3066d083a)


### Set up application and implement the first API

#### Scope of Work

- Implemented `GET /v1/users` API endpoint to send user data to clients.
- Followed a layered approach to implement the request-response cycle for ease of maintenance.
- Used Mongoose (Node.js-MongoDB ODM) to fetch user data from MongoDB.
- Defined JOI schema to easily validate client requests.
- Utilized middlewares to reduce code duplication.

#### Skills used

Node.js, Express.js, MongoDB, Mongoose ODM, JOI validation

## Request-response cycle in QKart (Endpoint: /v1/users)

![Request-response cycle in QKart](https://github.com/RutikKulkarni/rutikkulkarni2001-ME_QKART_BACKEND/assets/86470947/9a2b1489-9755-4172-8db3-493ee232a703)


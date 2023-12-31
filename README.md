## Frontned Angular 14 application with Node.js + Express for REST APIs and connects with MongoDB database

In this example, I will create user information and list user information and perform CRUD operation.

The back-end server uses Node.js + Express for REST APIs and connects with MongoDB database, front-end side is an Angular14 App with HTTPClient.

## Prerequsite
1. Node latest version : 18.6
2. Mongo DB Server and Client
3. CROS disable Browser for local developement only.

## Project setup

### Node.js Server
```
cd node-js-server
node server.js
```
### Angular Client
```
cd angular-14-client
```
Run `ng serve --port 8081` for a dev server. Navigate to `http://localhost:8081/`.

---------------------------------------------------------------------------------------

Functional requirements:

Implement a simple website for managing users;
Site should contain from 2 screens: 
Users list - table / grid view with details about each user;
Create user - a form for creating a new user;
Input fields / data to collect about each user:
First name
Field should accept only alphabetical characters
Max length should be 100 characters
Last name
Field should accept only alphabetical characters
Max length should be 100 characters
E-mail address
Only valid e-mail addresses can be used
Technical requirements:

Use angular for frontend;
Use Express / NodeJS / NestJS for backend;
Use MongoDB for data persistency;
Solution should be Dockerized and there should be a Docker Compose file for running the solution (which includes Frontend, Backend and dependencies);
Docker containers should be “production optimized”
Solution can be implemented either as single monolith application or 2 separate applications (frontend and backend);
Inputs validation should be on the backend side, but it’s also nice to have some basic validation on frontend.
 

Bonus points for:

Unit tests using Mocha/Jest/Angular testing Library;
Functional end-to-end test using any automation framework (Selenium, Puppeteer, Cypress);
Typescript for both frontend and backend.
 

UI / UX requirements:

There are no specific requirements for a design / UX of the frontend but it should look sensible. Any popular UI framework like Bootstrap / Material UI is preferred.#   a s s i g n m e n t - m a s t e r 
 
 
# Partially taken from here:
[Angular 2, NodeJS, MongoDB Customers Service](https://github.com/DanWahlin/Angular-NodeJS-MongoDB-CustomersService)

- Refactoring into a MEAN Setup

# Running the App
`npm install`
open up mongodb using *mongod*
`gulp copy:libs`   -   to copy angular into lib folder
`npm start`  
-- runs nodemon on port 3000. 

// **** //

## Software Requirements To Run Locally (there's a Docker option below as well)

* Node.js 6.5.0 or higher
* MongoDB 3.2 or higher

## Running the Application with Docker

 Install Node.js (6.5 or higher) and Docker for Mac/Windows or Docker Toolbox - https://www.docker.com/products/overview

 Open `config/config.development.json` and change the host from `localhost` to `mongodb`

 Install Gulp: `npm install gulp -g`

 Run `npm install`

 Run `gulp copy:libs`

 Run `npm run tsc:w` to compile TypeScript to JavaScript locally (leave the window running). This is only needed when in "dev" mode.

 Open another command window and navigate to this application's root folder in the command window

 Run `docker-compose build` to build the images

 Run `docker-compose up` to run the containers

 Navigate to http://localhost:3000 if using Docker for Mac/Windows or http://192.168.99.100:3000 if using Docker Toolbox in a browser



#### Project
This project sets up a docker-compose environment for a full stack application that is using the following stack:
* Database: PostgreSQL
* API: Node.js application with a start script that runs on port 8080
* Frontend: Node.js application with a start script that runs on port 3000

#### Database
* The data will be created in the ./postgresql directory

#### API
* The api application should exist in the ./api directory
* It should be a spring-boot maven project that can be started using the following command:
```npm run start```
* It should listen on port 8080

#### App
* The frontend application should exist in the ./app directory
* It should be a Node.js application that can be started with the following command:
```npm run start```
* It should listen on port 3000

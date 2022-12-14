# ContactsIphoneApp
A simple iphone contacts app which helps to create, view, edit and delete the contacts. 


## Dependencies
- **npm** -- V 8.16.0
- **node** -- V 16.14.2

## Features
- Create, view, edit and delete a contact. 
- Sorting contacts by search value. 
- Validating input values.

## Tech Stack
- [**Angular**](https://angular.io/) - for Front-end Framework
- [**MongoDB**](https://www.mongodb.com/) - for Database
- [**Docker**](https://docs.docker.com/desktop/#download-and-install) - for production generation
- [**Docker-compose**](https://docs.docker.com/compose/install/) - for running the production app
- [**Express.js**](https://expressjs.com/) - for Nodejs
- 
## Steps to run the project
#### Classical Way

- Clone the project
 --`git clone <projectUrl>`
- Install the dependencies
 -- `cd ContactsIphoneApp`
 --`cd angularapp && npm i`
 --`cd api && npm i`
- Run the frontend
 --`cd angularapp`
 --`ng serve`
- Run the backend
  --`cd api`
 --`nodmeon server.js`
 
#### Easy Way

- Clone the project
 --`git clone <projectUrl>`

- Build the docker
 -- `cd ContactsIphoneApp`
 -- `docker-compose up --build`

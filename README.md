# LAB - 00

## Proof of Life Server

### Author: Jonathon Schwamman

### Links and Resources
* [submission PR](https://github.com/Schwamman-401-advanced-javascript/Lab-Deployment/pull/1)
* [travis](https://travis-ci.com/Schwamman-401-advanced-javascript/Lab-Deployment)
* [front-end](https://deployment-lab.herokuapp.com/)

#### Documentation
* [jsdoc](https://deployment-lab.herokuapp.com/docs)

### Modules
#### `pol.js`
##### Exported Values and Methods

###### `isAlive(dead) -> boolean`
The isAlive() method returns a true or false.

### Setup
#### `.env` requirements
* `PORT` - Port Number

#### Running the app
* `npm start`
* Endpoint: `/`
  * Returns a boolean
* Endpoint: `/docs`
  * Returns jsdoc documentation
  
#### Tests
* Unit Tests: `npm run test`
* Lint Tests: `npm run lint`


#### UML

![UML Diagram](whiteboard.jpg)

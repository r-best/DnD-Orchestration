# DnD-Orchestration

## Installation
* Make sure you have [angular](https://angularjs.org/) and (node)[https://nodejs.org/en/] installed on your machine
* Clone the repo
* Download the [oracle instant client](http://www.oracle.com/technetwork/database/features/instant-client/index-097480.html) BASIC and SDK and unzip them both into a folder named `instantclient`
* Place that folder into the cloned repo (the api will need it for installation)
* Run `npm install` in the repo, this will clone the api and frontend and set everything up for you
* Use `npm run api` (or cd into `DnD-API` and run `node index.js`) to start the api
* Use `npm run frontend` (or cd into `DnD-Frontend` and run `ng serve --open`) to start the frontend client

# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

## Steps for setting up the environment:

* Install docker in your local machine.
* Verify if docker is ready by running the folowing commands in your terminal: "docker -v" and "docker-compose -v" .
* Then run "docker-compose up" from the project root directory to load Anythink's backend and frontend. If the docker is 
  working properly, the backend should be running and able to connect to your database.  
* Test the database by accessing  http://localhost:3000/api/ping .
* Now to test the frontend and make sure it's connected to the backend, go to http://localhost:3001/register .
* Signup/Register in the Anythink Marketplace.

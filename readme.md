# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

To setup the project:

1. Ensure Docker is installed and running on your machine (you can check this in your terminal with `docker-v`) and `docker-compose -v`.
2. From the project root directory, run docker-compose up to load the front and backend.
3. Test the backend by pointing your broswer to http://localhost:3000/api/ping
4. Test the frontend and ensure it's connected the backend and database by registering as a user here http://localhost:3001/register
 

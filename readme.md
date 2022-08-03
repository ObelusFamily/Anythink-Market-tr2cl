# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Ensure docker is installed and running `docker -v && docker-compose -v`
- Navigate to the project directory in a terminal window and run `docker-compose up`
- Wait for everything to spin up
- Once everything is running, try hitting the backend `http://localhost:3000/api/ping`
- Then the frontend `http://localhost:3001/register`
- If all's going well you should be able to create a user profile

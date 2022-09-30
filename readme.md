# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1 - Download and install docker from https://www.docker.com/
2 - Open a terminal and run "docker-compose up" from the project root directory
3 -  Check if everything works by going to http://localhost:3000/api/ping
4 -  Check if the frontend is connected to the backend and everything works perfectly go to http://localhost:3001/register and create a new user.
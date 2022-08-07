# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install [Docker](https://docs.docker.com/get-docker/)
2. You can verify if docker is ready by running the following commands
```
docker -v
```
and 
```
docker-compose up
```
3. If Docker is working correctly then the backend should be running and be able to connect to the local database. You can test this by pointing your browser to http://localhost:3000/api/ping
4. Now, you also need to check if the frontend is connected to the backend. You can do this by creating a new user on http://localhost:3001/register

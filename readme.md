# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including
all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file
([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull
request against `main` from a feature/bug branch and add `@vanessa-cooper` as
reviewer.

## First setup

1. Install docker on your machine [here](https://docs.docker.com/get-docker)
2. Test docker installation with this command - `docker -v` or
   `docker-compose -v`
3. Start local app with this command - `docker-compose up`
4. Test API by pointing your browser to `http://localhost:3000/api/ping`
5. Open frontend app at `http://localhost:3001`

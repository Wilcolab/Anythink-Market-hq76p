# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone github repository
2. [install Docker](https://docs.docker.com/get-docker/)
3. Check docker `docker -v`
4. Create front and backend container `docker-compose up`
5. Access api [http://localhost:3000/api/ping](http://localhost:3000/api/ping)
6. Access front [http://localhost:3001/register](http://localhost:3001/register) and Create account

# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Download and install Docker on your local machine, get [docker](https://docs.docker.com/get-docker/) here.

- Check if docker successfully installed by running

```bash
docker -v
docker-compose -v
```

- Run the following in the root of the project to load the Anythink FrontEnd and Backend.

```bash
docker-compose up
```

- Check if the frontend is running by going to [http://localhost:3001/register](http://localhost:3001/register) in your browser, and you can do same for the backend by going to [http://localhost:3000/api/ping](http://localhost:3000/api/ping) in your browser.

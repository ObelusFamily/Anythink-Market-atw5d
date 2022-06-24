# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Step 1: - install docker [Availble in https://docs.docker.com/get-docker/].</br>
Step 2: - check it installed by ``docker -v`` and ```docker-compose -v```. </br>
Step 3: - Then, run ``docker-compose up`` from the project root directory to load Anythink's backend and frontend.
Step 4: Test this by pointing your browser to http://localhost:3000/api/ping.

Make sure that you run all scripts from nnow on one of the containers created by ``docker-compose up``.  Also, you can use ``docker exec`` to run commands on a running container.


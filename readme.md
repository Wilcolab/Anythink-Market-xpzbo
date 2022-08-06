# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Clone this repository

Make sure docker is installed. If you haven't install it from here https://docs.docker.com/get-docker/

Once installed open up your terminal and check whether docker is installed.
  
if done right then we can see the version number after running this command

```
docker version
```
or
```
docker -v
```

Install `docker-compose` if you haven't

```
sudo apt-get install docker-compose
```

Check the version

```
docker-compose -v
```

Once that's done, go inside the root of the cloned respository folder and run the following command

```
sudo docker-compose up
```

This will start your backend and your connection will be established. You can check the same if you navigate to http://localhost:3000/api/ping


Check whether the frontend is connected to the backend by creating a user here:http://localhost:3001/register


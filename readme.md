# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_

### Start the docker container

```
docker-compose up
```

This will sipn up the backend, frontend and the database.

Once everything loads, test the backend by visiting [/api/ping](https://obelusfamily-anythink-market-qdm9d-5x79wr7rxjxc49v4-3000.githubpreview.dev/api/ping)

If everything is working properly, you’ll be able to create a new user on [/register](https://obelusfamily-anythink-market-qdm9d-5x79wr7rxjxc49v4-3001.githubpreview.dev/register)

You can also run commands on docker images using `docker exec`

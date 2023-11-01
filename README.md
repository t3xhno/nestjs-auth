## Description

My NestJS implementation of a basic JWT authentication/authorization REST api, with user sign up / sign in, and a dockerized postgres database

## Installation

```bash
$ npm install
```

## Running the app

The Postgres database is dockerized, and the image must be installed:

```bash
docker compose up dev-db -d
```

Once the docker container with the database is runnig, the database can be removed, brought up again and migrated in a single command:

```bash
npm run prisma:dev:restart
```

The nestjs backend itself is run using the following commands:

```bash
# development
$ npm run start

# watch mode
$ npm run start:dev

# production mode
$ npm run start:prod
```

## Test

TBD

## License

Nest is [MIT licensed](LICENSE).

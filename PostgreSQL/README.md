PostgreSQL Example Project

## Setup

### Manual setup

To run this example, a postgreSQL database is required and the initial sql `customers_sample` script must be imported. See `PostgreSQL` doc to import the sql to your existing database.

### Bootstrap with docker

A `docker-compose` file is prepared in the project to help you bootstrap the database. From PostgreSQL project folder, simply run:

```
docker-compose up -d
```

And you will have an initialized postgreSQL database up and running for the example

> the default db user is `postgres`, and the password is `postgres-password`. You can change it in `docker-compose.yml` >	`POSTGRES_PASSWORD`

## Run Example

Import PostgreSQL example from Ananas Desktop. Fill the corresponding database password (`postgres-password` by default) and database host (`localhost`). Enjoy analyzing!


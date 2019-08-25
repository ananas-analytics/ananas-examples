MySQL Example Project

> This example works on Ananas Desktop 0.8.0+

## Setup

### Manual setup

To run this example, a mysql database is required and the initial sql `customers_sample` script must be imported. See `MySQL` doc to import the sql to your existing database.

### Boostrap with docker

A `docker-compose` file is prepared in the project to help you bootstrap the mysql database. Simply run:

```
docker-compose up -d
```

And you will have an initialized mysql database up and running for the example

> the default mysql user is `root`, and the password is `mysql-password`. You can change it in `docker-compose.yml` >	`MYSQL_ROOT_PASSWORD`

## Run Example

Import MySQL example from Ananas Desktop. Fill the corresponding database password (`mysql-password` by default) and database host (`localhost`). Enjoy analyzing!


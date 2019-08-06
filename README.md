# docker-compose-postgres

## Requirements

* docker >= 17.12.0+
* docker-compose

## Usage

* Run `docker-compose up`

## Environment

This Compose file contains the following environment variables:

| name                     | default              |
|--------------------------|----------------------|
| POSTGRES_USER            | postgres             |
| POSTGRES_PASSWORD        | postgres             |
| PGADMIN_PORT             | 5050                 |
| PGADMIN_DEFAULT_EMAIL    | admin@pgadmin.local  |
| PGADMIN_DEFAULT_PASSWORD | admin                |

## Services

| name     | url                   | username          | username |
|----------|-----------------------|-------------------|----------|
| postgres | localhost:5432        | postgres          | postgres |
| PgAdmin  | http://localhost:5050 | admin@pgadmin.org | admin    |

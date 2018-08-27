localhost-pgsql-postgis
============================

## Setup

example

```sh
git clone https://github.com/shohei-ot/localhost-pgsql-postgis
cd localhost-pgsql-postgis
cp .env.example .env
```

## Start

```sh
docker-compose up
```

## Stop

```sh
docker-compose down
```

## Access

example

```sh
psql -U postgres -h localhost -p 5432
```

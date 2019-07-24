# Redash

## How to set up

1. edit .env

```
$ cp .env.template .env
```

see [getredash/redash/setup/setup.sh](https://github.com/getredash/redash/blob/master/setup/setup.sh)

2. start docker

```
$ docker-compose up -d postgres
$ docker-compose run --rm server create_db
$ docker-compose up -d
```

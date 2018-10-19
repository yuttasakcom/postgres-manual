# Postgres Manual

## Setup

```bash
$ docker-compose up -d
```

## Create Database

```psql
$ CREATE DATABASE dvdrental;
```

## Restore Data

```bash
$ docker cp dvdrental.tar pgadmin:/tmp
```

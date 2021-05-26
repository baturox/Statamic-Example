# Statamic V2 Blog Example
### With Docker


[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

## Installation


Requires [Docker](https://www.docker.com/)  to run.

Install the containers and start the server.

```sh
git clone https://github.com/baturox/Statamic-Example
cd Statamic-Example
docker-compose up -d

Go To: http://localhost:8000/installer.php
```
App URL

```sh
http://localhost:8000/
```


For please commands...

```sh
docker-compose exec fpm bash
```


## Docker

Rebuild command


```sh
docker-compose build
```
This will rebuild all application and clear all caches.

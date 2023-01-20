## Overview
Simple API Server using Node.js and MongoDB

## Setup
Define environment variables for MongoDB.
```
touch .env
echo "ROOT_USERNAME=[e.g. root]" >> .env
echo "ROOT_PASSWORD=[e.g. password]" >> .env
```

## Start application
```
docker-compose up -d
```

## Run server
```
docker-compose exec app node server.js
```

## How to access
- `curl 127.0.0.1`
- `curl localhost`
- By using browser


## Stop server
`Ctrl` + `C`

## Stop application
```
docker-compose down
```

## How to Use Linter
If you'd like to use linter, execute the following command.
```
docker-compose exec app npm install --save-dev
```
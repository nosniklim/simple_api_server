## Overview
Simple API Server using Node.js and MongoDB

## Setup
Define environment variables for MongoDB.
```
touch .env
echo "ROOT_USERNAME=[e.g. root]" >> .env
echo "ROOT_PASSWORD=[e.g. password]" >> .env
```

## Start Application
```
docker-compose up -d
```

## Run Server
```
docker-compose exec app node server.js
```

## How to Access
- `curl 127.0.0.1`
- `curl localhost`
- By using browser


## Stop Server
`Ctrl` + `C`

## Stop Application
```
docker-compose down
```

## How to Use Linter
If you'd like to use linter, execute the following command.
```
docker-compose exec app npm install --save-dev
```
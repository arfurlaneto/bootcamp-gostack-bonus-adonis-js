# bootcamp-gostack-bonus-adonis-js

Simple project/tasks crud back-end with migrations, login and async emailing.

## back-end
- `docker run --name postgresadonis -e POSTGRES_DB=adonis -e POSTGRES_PASSWORD=docker -p 5432:5432 -d -t postgres:11`
- `docker run --name redisadonis -p 6379:6379 -d redis:alpine`
- criar arquivo .env
- `adonis migration:run`
- `npm install`  to install dependencies
- `adonis serve --dev`
- `adonis kue:listen`

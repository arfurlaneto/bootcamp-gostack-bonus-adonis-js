# bootcamp-gostack-bonus-adonis-js

docker run --name postgresadonis -e POSTGRES_DB=adonis -e POSTGRES_PASSWORD=docker -p 5432:5432 -d -t postgres:11
docker run --name redisadonis -p 6379:6379 -d redis:alpine
npm install
adonis serve --dev
adonis kue:listen

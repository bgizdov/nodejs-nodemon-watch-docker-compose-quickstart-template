# Node.js App with Docker Compose and Nodemon or Node --watch

This is a simple Express Node.js application running in Docker and using Nodemon or Node --watch, which allows you to easily develop and monitor code changes.

## Starting the Application

To start the application, use the following commands:

```
npm install
docker-compose up
```

## To use node --watch
Change command in docker-compose.yml
```
command: npm run dev:nodewatch
```

## To use nodemon
Change command in docker-compose.yml
```
command: npm run dev:nodemon
```

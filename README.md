# Service Poller
Spring boot app which polls configured service and keeps a track of their health. 
Written in a layered architecture.
Uses flyway for database migrations.
The service comes with an extremely basic UI to present the status of each service.

### Getting started

```
mvn clean install
docker-compose up --build --force-recreate
```
This will start the application on port 8080 and a postgres docker container to save the service data.

### Testing
Service code has been tested with Junit 5. And API tests have been written in groovy using spock.

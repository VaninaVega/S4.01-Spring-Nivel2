# S4.01-Spring-Nivel2

This is a Spring Boot project built with Gradle as the dependency manager.

## Requirements

- Java JDK (minimum version 11)
- Gradle installed
- Postman (or a similar HTTP client) for testing the API endpoints

## How to run the application

- Navigate to the root directory of the project in your terminal.
- Run the Gradle command to start the application:
- gradle bootRun
- The application will be accessible at http://localhost:9001.

## API Endpoints

This API has been tested using Postman.

- GET /HelloWorld: Returns a greeting with an optional "name" parameter (default is "UNKNOWN").
Example (Postman): Send a GET request to http://localhost:9001/HelloWorld or http://localhost:9001/HelloWorld?name=YourName.
- GET /HelloWorld2/{nombre}: Returns a greeting with an optional "name" parameter in the path.
Example (Postman): Send a GET request to http://localhost:9001/HelloWorld2 or http://localhost:9001/HelloWorld2/YourName.

## Gradle Commands

- gradle build: Compiles the project.
- gradle assemble: Packages the project.
- gradle clean: Cleans the build directory.
- gradle bootRun: Runs the Spring Boot application.

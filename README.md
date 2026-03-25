# Hello World Application

A simple Spring Boot Hello World application for Cloud Foundry deployment.

## Build

```bash
mvn clean package
```

## Run Locally

```bash
java -jar target/hello-world-1.0.0.jar
```

## Deploy to Cloud Foundry

```bash
cf push
```

## Endpoints

- `/` - Returns "Hello World from Cloud Foundry!"
- `/health` - Health check endpoint

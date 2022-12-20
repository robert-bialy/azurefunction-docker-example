# Azure function example for .NET 6.0
An example project created to show how to dockerize .NET 6.0 function.
The project is using v4 functions.

## Build project
```
docker build -t azure-function-example-net6.0 .
```

## Run project locally
```
docker run -p 8080:80 -d azure-function-example-net6.0:latest
```

## Test the endpoint
```
http://localhost:8080/api/HttpTriggerExample
```
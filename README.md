# training-health-metrics
Demo project for health and metrics with spring boot

## Build & Run
Too build and run the project you need Maven and JDK(>=1.8) on your PATH.
```
mvn spring-boot:run
```

Please keep in mind that the endpoints might change in case the application is ran *remote* from within a github codespace.

## Hello World Endpoints
- http://localhost:8080/api/hello

## Actuator Endpoints
- http://localhost:8080/actuator
- http://localhost:8080/actuator/health
- http://localhost:8080/actuator/metrics


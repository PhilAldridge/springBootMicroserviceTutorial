# SpringBoot Microservices Tutorial
![image](https://github.com/PhilAldridge/springBootMicroserviceTutorial/assets/105776682/0915e5a7-023b-4a35-aaa5-eafb3d95b2a3)


This code is the result of following the tutorial found (here)[https://www.youtube.com/watch?v=mPPhcU7oWDU]. In the process of working on this project, I learned about:
- Spring Boot, how to configure and initialize a Spring Boot project.
- Creating a mongoDB and mySQL server using Spring Boot.
- How to get servers to communicate with each other (both synchronous and asynchronous.
- Service discovery using Netflix Eureka
- Using Spring Cloud Gateway to implement an API Gateway
- How to secure services using Keycloak
- How to implement a circuit breaker (Resilience4j) to improve service resilience
- Use distributed tracing (with Zipkin) so that failed requests are easier to identify and diagnose.
- Event driven architecture using Kafka
- How to use Jib to dockerize the whole microservices project and how to compose these docker images together.
- Using Prometheus and Grafana to monitor the microservices.

## How to run the application using Docker

1. Run `mvn clean package -DskipTests` to build the applications and create the docker image locally.
2. Run `docker-compose up -d` to start the applications.
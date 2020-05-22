### Microservices Architecture for handling Big Data using Java and SpringCloud
_Spring Cloud and Netflix OSS (Eureka, Zuul, Hystrix) based Architecture to create REST services that are highly scalable, performant and secured with Spring Security_

- ### [Bigdata File Import Microservice](https://github.com/vjpal3/bigdata-import-microservice)
  - A Spring Boot service that imports data from a CSV file (about 6 million records) to a PostgreSQL database using Spring Batch, Spring Data JPA-Hibernate and uses Java Multi-threading techniques for optimized  performance.   

- ### [Auth Microservice](https://github.com/vjpal3/spring-security-microservice)
  - A Spring Boot service with REST API that leverages Spring Security using JWT web tokens
  - Provides exception handling for invalid username/password and duplicate username

- ### [Zuul API Gateway](https://github.com/vjpal3/bigdata-zuul-gateway)
  - A gateway API using Netflix Zuul that provides a well-known entry point for all other microservices
  - Customized Zuul filter that communicates with the Auth Microservice to authenticate JWT token, before forwarding the request to a secured microservice

- ### [Eureka Discovery Server](https://github.com/vjpal3/bigdata-eureka-server)
  - Discovery Server using Netflix Eureka that allows microservices to register themselves at runtime as they appear in the system landscape. 

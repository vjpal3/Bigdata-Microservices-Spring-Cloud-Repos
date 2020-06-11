### Microservices Architecture to handle Big Data and fraud-detection using Java, Python and SpringCloud
_Spring Boot, Spring Cloud, Python and Netflix OSS (Eureka, Zuul, Ribbon, Hystrix, Sidecar) based Architecture to create REST services that are highly scalable, performant and secured with Spring Security_

- ### [Bigdata File Import Microservice](https://github.com/vjpal3/bigdata-import-microservice)
  - A Spring Boot service that imports data from a CSV file (about 6 million records) to a PostgreSQL database using Spring Batch, Spring Data JPA-Hibernate and uses Java Multi-threading techniques as well as asynchronous operations for optimized  performance.   

- ### [Auth Microservice](https://github.com/vjpal3/spring-security-microservice)
  - A Spring Boot service with REST API that leverages Spring Security using JWT web tokens
  - Provides exception handling for invalid username/password and duplicate username

- ### [Fraud-detection Python Microservice](https://github.com/vjpal3/Fraud-Detection-PythonML-Service)
  - This Python microservice builds a fraud detection model using Logistic Regression machine learning algorithm to predict fradulent and non-fradulent transactions 
  - Works on a financial data set having over 6 million data points
  - Calculates statistics such as Accuracy, Precision and Recall  

- ### [Sidecar Python App](https://github.com/vjpal3/sidecar-pythonML-service)
  - A fraud detection model using Python microservice, plugged into Spring Cloud Architecture using Netflix Sidecar App  

- ### [Zuul API Gateway](https://github.com/vjpal3/bigdata-zuul-gateway)
  - A gateway API using Netflix Zuul that provides a well-known entry point for all other microservices
  - Customized Zuul filter that communicates with the Auth Microservice to authenticate JWT token, before forwarding the request to a secured microservice

- ### [Eureka Discovery Server](https://github.com/vjpal3/bigdata-eureka-server)
  - Discovery Server using Netflix Eureka that allows microservices to register themselves at runtime as they appear in the system landscape. 

 ### Built with:
  - Java
  - Spring Cloud
  - Spring Boot
  - Spring Security with JSON Web Token
  - Spring Batch with MultiResourcePartitioner to process multiple files concurrently
  - Spring Data JPA-Hibernate
  - PostgreSQL
  - Netflix OSS (Eureka, Zuul, Ribbon, Hystrix, Sidecar)
  - Spring cloud OpenFeign
  - JasperReports
  - Python (Pandas, Numpy, SciKit-Learn) and Flask
  - REST API
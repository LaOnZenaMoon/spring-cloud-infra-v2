## spring-cloud-infra-v2
* Deal with Spring Cloud infrastructure
* Will be used with other projects[spring-cloud-config-server, ecommerce-backend]

## Project structure

### discovery-service
* A service for registering and discovering microservices

### gateway-service
* The gateway server for other microservices to pass through 

### config-service 
* A service for managing the properties of microservices 

## Skills
* Java 11
* Spring Boot 2.6x
* Spring Boot Actuator
* Spring Cloud
  * Spring Cloud Netflix Eureka
  * Spring Cloud Gateway
  * Spring Cloud Config
  * HTTP Request 
    * Feign Client
  * Circuit Breaker
    * Resilience4j
  * Distributed Transaction
    * Spring Cloud Zipkin
    * Spring Cloud Sleuth
* Messaging service
  * [Kafka](https://github.com/wurstmeister/kafka-docker)
* Docker

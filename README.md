# product-microservice
demonstration of microservice communication and management

> The microservice is a software architectural style that structures an application as a collection of small,
> independent services, each of which is designed to perform a specific business function. These services are loosely
> coupled, independently deployable, and communicate with each other through well-defined APIs.
> The microservices architecture is an alternative to the monolithic architecture, where an application is built as a
> single, tightly integrated unit.

## Topics covered in this demo

1. Distributed Tracing using **Zipkin**
2. Global Error/Exception Handling using **Controller Advice**
3. Generic DTO Validation(Fluent Validation)
4. Request/Response header validation using **Gateway Filter**
5. Resilience/Retry Policy using **Resilience4J**
6. Service Discovery using **Spring Cloud**
7. Health Check using **Actuator**
8. Inter-service communication using **RestTemplate**

### The following are services included in this microservice demo

1. [api-gateway](https://github.com/Amit-Chavda/api-gateway)
2. [service-registry](https://github.com/Amit-Chavda/service-registry)
3. [user-service](https://github.com/Amit-Chavda/user-service)
4. [product-service](https://github.com/Amit-Chavda/product-service)

5. [order-service](https://github.com/Amit-Chavda/order-service)

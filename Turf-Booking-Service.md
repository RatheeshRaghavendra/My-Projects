# Turf Booking Service

## Description
An integration service, developed using Spring Boot, that allows users to effortlessly book football turf facilities

## 🖧 Architecture
![Turf booking Architecture v2](https://github.com/user-attachments/assets/fe63cb34-967d-4ec0-80e3-edbbabcef65f)

## Repositories

- [turf-booking-service-registry](https://github.com/RatheeshRaghavendra/turf-booking-service-registry)
- [turf-booking-api-gateway](https://github.com/RatheeshRaghavendra/turf-booking-api-gateway)
- [turf-booking-bookings-papi](https://github.com/RatheeshRaghavendra/turf-booking-bookings-papi)
- [turf-booking-booking-sapi](https://github.com/RatheeshRaghavendra/turf-booking-booking-sapi)
- [turf-booking-turf-sapi](https://github.com/RatheeshRaghavendra/turf-booking-turf-sapi)
- [turf-booking-user-sapi](https://github.com/RatheeshRaghavendra/turf-booking-user-sapi)

## Microservices Concepts Implemented

### Spring Web
  OpenFeign Framework is used to make REST calls among the different APIs
### Distributed Tracing
  Zipkin and Micrometer is used to trace logs across the APIs
### Logging
  Log4J2 is used for logging
### Gateway
  Spring Cloud Gateway is used to route the incoming requests to the respective APIs
### Service Discovery
  Netflix Eureka Server is used to register and discover services 
### Aspect-Oriented Programming
  AOP is implemented to write cross cutting loggers

# SFG Beer Works - Brewery Microservice

Source code in this repository is to support my on line courses:
* [Spring Boot Microservices with Spring Cloud](https://www.udemy.com/spring-boot-microservices-with-spring-cloud-beginner-to-guru/?couponCode=GIT_HUB2)

----
## go branches
### go-assignment-50
* BreweryClient.java - add Customer (get, set, update, delete) methods
* BreweryClientTest.java - add tests for Customer get, set, update, delete methods

### go-assignment-66 - Validation, Error Handling
* Add validation to name in CustomerDto.java
  1. Non blank
  2. Size minimum 3 characters, and maximum 100 characters
* Add Error Handling to CustomerController.java

### go-assignment-79 - MapStruct
* Add dependency for MapStruct to pom
* Create Customer class.  there is already a CustomerDto.
* Implement MapStruct i/f to
  1. Convert Customer to CustomerDto
  2. Convert CustomerDto to Customer
* Inspect generated code


# Spring Boot + Spring data JPA + PostgreSQL example

## Technologies used:
Technologies used:
* Spring Boot 3.1.2
* Spring Data JPA (Hibernate 6  is the default JPA implementation)
* PostgreSQL 15
* Maven
* Java 17
* JUnit 5
* [REST Assured](https://rest-assured.io/) and [Testcontainers](https://testcontainers.com/) (for Spring integration tests using a container)

## How to run it
```

$ git clone https://github.com/tiwarisanjay/spring-boot-jpa-postgresql.git

$ cd spring-boot-jpa-postgresql

$ ./mvnw clean package -Dmaven.test.skip=true

$ ./mvnw spring-boot:run

```
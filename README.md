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

## Setup Postgress ( I am using Mac M1)
- Download post gress from https://postgresapp.com/downloads.html 
- Run following command mentioned in doucmentation to setup psql path 
```
sudo mkdir -p /etc/paths.d &&
echo /Applications/Postgres.app/Contents/Versions/latest/bin | sudo tee /etc/paths.d/postgresapp
```
- Now postgress is installed and you can set it up as https://www.youtube.com/watch?v=wTqosS71Dc4 
- connect to poastgress and setup passwrod as 
```
ALTER USER sanjaytiwari PASSWORD 'sanjaytiwari';
```
## How to run it
```
$ git clone https://github.com/tiwarisanjay/spring-boot-jpa-postgresql.git

$ cd spring-boot-jpa-postgresql

$ ./mvnw clean package -Dmaven.test.skip=true

$ ./mvnw spring-boot:run

```
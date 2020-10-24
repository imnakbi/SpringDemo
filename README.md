# Gitlab Microservice

## Downloadable Bundles

A wrapper for the [SPRINGBOOT DATA JPA ENTITY](https://github.com/atteif/SpringDemo.git) written in Java.

Mysql Docker image 
[![Docker Hub](https://img.shields.io/docker/pulls/centurylink/mysql?label=docker%20pull%20mysql)](https://hub.docker.com/r/centurylink/mysql/)

## Requirements

* Apache Maven 3.3.3+
* Java 8
* Mysql
* Docker

## Building

To build the project and generate the template assembly use the included Maven wrapper:

    ./mvnw clean install
    
## Running

To run SpringBootDataJpaEntity application, after building, unzip the assembly and start the server:

    1-docker pull centurylink/mysql
    2-docker network create $Network_Name$
    3-docker run -d -p 3306:3306 --net $Network_Name$ --name mysql -e MYSQL_ROOT_PASSWORD=root centurylink/mysql
    4-java -jar spring-boot-data-jpa-entity-0.0.1-SNAPSHOT.jar
## wrapper 

A wrapper for the [Api Documentation](http://localhost:8082/swagger-ui.html#/) available in http://localhost:8082/swagger-ui.html#/
        

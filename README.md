# wavefront
A sample of Spring Cloud Sleuth:

Spring Boot 2.3.M4, R2DBC, PostgreSQL, Reactive Web, Spring Cloud Sleuth and Lombok.

Getting started:

On the application root run the command:

- sudo docker-compose -f docker/docker-compose.yml up -d

After that, running the spring boot application with maven plugin:

- mvn spring-boot:run

So, You'll see that a table called reservation was created and so you can see also a token and a Spring Cloud Sleuth link that was provided. 
Go ahead and started to trace you app.

Use the folows endpoits:

- http://localhost:8080/reservations
- http://localhost:8080/hello






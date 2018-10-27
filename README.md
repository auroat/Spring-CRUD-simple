# Spring-CRUD-simple
[Back-end Java Project] A Spring application which is bound to a MySQL database.

A very simple Spring app which supports all the CRUD operations, like magic.

This app creates an executable JAR, but you can run the application using ./mvnw spring-boot:run. Or you can build the JAR file with ./mvnw clean package. Then you can run the JAR file: $ java -jar target/gs-accessing-data-mysql-0.1.0.jar

Keep in mind that when freshly running the app and all you have is the local DB schema (no tables), then check the manual for:
spring.jpa.hibernate.ddl-auto=none - instead of "none" should be "create".

Reference:
https://spring.io/guides/gs/accessing-data-mysql/#initial

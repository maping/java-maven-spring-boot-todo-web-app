# A Java Maven To Do List Web App using Spring Boot and MySQL

A simple Todo list application using Spring Boot with the following options:
- Spring JPA and MySQL for data persistence
- Thymeleaf templae for the rendering.

To build and run the sample from a fresh clone of this repo:
## Configure MySQL
1. Create a database in your MySQL instance.
2. Update the application.properties file in the `src/main/resources` folder with the URL, username and password for your MySQL instance. The table schema for the Todo objects will be created for you in the database.
## Build and run the sample
```shell
mvn clean package
mvnw spring-boot:run
```
Open a web browser to http://localhost:8080

As you add and update tasks in the app you can verify the changes in the database through the MySQL console using simple statements like 
`select * from todo_item`.

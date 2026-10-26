# Student Registration System

A Spring Boot CRUD web application built for COSC 32133/BECS 32263 Full-Stack Software Development (Lab Sheet 04, University of Kelaniya). Staff can register students (full name, email, phone, course and age) through a validated HTML form. Records appear in a table below the form, where each one can be edited or deleted. The app uses Spring MVC, Spring Data JPA, Thymeleaf and Bean Validation, and stores its data in an in-memory H2 database, so records are cleared when the application stops.

To run it, you need JDK 21. From the project folder, run `./mvnw spring-boot:run` (or `mvnw.cmd spring-boot:run` on Windows), then open http://localhost:8080 in your browser. To browse the database, open http://localhost:8080/h2-console and log in with JDBC URL `jdbc:h2:mem:studentdb`, user name `sa` and an empty password.

# CRUD Operations Project

This project demonstrates the implementation of CRUD (Create, Read, Update, Delete) operations using Java and Spring Boot. It is designed to show how backend applications interact with a database through RESTful APIs.

## Technologies Used
- Java
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven
- IntelliJ IDEA

## Features
- Create new records in the database
- Read or retrieve existing records
- Update existing data
- Delete records from the database
- RESTful API endpoints for each operation

## Project Structure
- Controller Layer – Handles HTTP requests
- Service Layer – Contains business logic
- Repository Layer – Interacts with the database
- Model Layer – Entity/POJO classes

## API Endpoints Example
POST /students      -> Create student  
GET /students       -> Get all students  
GET /students/{id}  -> Get student by ID  
PUT /students/{id}  -> Update student  
DELETE /students/{id} -> Delete student  

## Purpose
This project is created for learning and demonstrating backend development concepts such as REST APIs, database connectivity, and CRUD operations using Spring Boot.

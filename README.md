# Virtual Queue Management System

Java backend application for managing hospital patient queues using token-based system.

## Tech Stack

* Java
* Spring Boot
* Spring Data JPA
* MySQL
* RESTful API

## Features

* Token generation for patients
* Queue tracking and management
* REST APIs for handling requests
* CRUD operations for queue data
* Database integration using JPA

## API Endpoints

* GET /tokens → Retrieve queue data
* POST /tokens → Generate new token
* PUT /tokens/{id} → Update token status
* DELETE /tokens/{id} → Remove token

## Project Structure

* Controller → Handles API requests
* Service → Business logic
* Repository → Database operations
* Entity → Data models

## How to Run

1. Clone the repository
2. Open project in Eclipse or IntelliJ
3. Configure MySQL database in application.properties
4. Run the main Spring Boot application
5. Test APIs using Postman

## Author

Mithun K
Java Backend Developer

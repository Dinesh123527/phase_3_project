# Sporty Shoes an E-Commerce Application
## Project Details
This Project aim's to develop an E-Commerce Application where we sell the shoes and keep a track on purchase reports of all the customers using Spring Boot.

## Technologies and tools Used
Spring Boot: To create a E-commerce project for Sporty Shoes.
Postman: To the API request and response.
H2 Database: To create and manage the database.
JPA: To manage the operations for the application.
Lombok: It is the tool of the java library that was used to generate code for minimizing the unused code.
Rest-API: To create the API methods and to check the response of the object entities.
Spring Tool Suite: To write and execute the code.
Tomcat: To deploy  application.

## Core Concepts Used in the Project
• Object-Oriented: used to create and model objects for users and their credentials.

• Databases: used to store and retrieve data.

• Data Sources: used to define a set of properties required to identify and access the database.

• Collections: used some collections such array-list to store collection of data.

• Collections: used Java8 Streams to filter and fetch collection of data.

• Custom Exception Handling: used to catch problems that arises in the code especially in I/O blocks.

• MVC: Micro Service is an architecture that allows the developers to develop and deploy services independently.

• Micro Services(Spring Boot): Micro Service is an architecture that allows the developers to develop and deploy services independently.

• API: API stands for application programming interface, which is a set of definitions and protocols for building and integrating application software.

## File Structure

```
src
├── main
│   ├── java
│   │   └── com
│   │       └── api
│   │           └── ecommerce
|   |              └── shoes 
│   │                  ├── SportyShoes.java
│   │               ├── config
│   │               │   ├── SpringSecurityConfig.java
│   │               │   └── SwaggerConfig.java
│   │               ├── controller
│   │               │   ├── CRUDController.java
│   │               │   └── SearchController.java
│   │               ├── exceptionHandler
│   │               │   └── BusinessException.java
│   │               ├── model
│   │               │   ├── PurchaseReport.java
│   │               │   └── Shoe.java
│   │               ├── repository
│   │               │   ├── PurchaseReportRepository.java
│   │               │   └── ShoesRepository.java
│   │               └── service
│   │                   ├── SportyShoesService.java
│   │                   └── impl
│   │                       └── SportyShoesServiceImpl.java
│   └── resources
│       └── application.properties
└── test
    ├── java
    └── resources

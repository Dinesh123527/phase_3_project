Sporty Shoes - SimpliLearn Phase 3 Assessment
Technologies Used
Java	1.8
Spring Boot	3.3.0
Lombok	---
Swagger-ui	3.0.0
H2	---
JPA	---
Spring Security Starter	---

File Structure
src
├── main
│   ├── java
│   │   └── com
│   │       └── api
│   │           └── ecommerce
|   |                   └── shoes
│   │                      ├── SportyShoesApllication.java
│   │                      ├── config
│   │                      │   └── SwaggerConfig.java
│   │                      ├── controller
│   │                      │   ├── AdminController.java
|   |                      |   └── ProductController.java
│   │                      │   └── PurchaseReportController.java
|   |                      |   └── UserController.java
│   │                      ├── exceptions
│   │                      │   └── AdminException.java
|   |                      |   └── AdminUserNotFoundException.java
|   |                      |   └── ExceptionController.java
|   |                      |   └── LoginExceptio.java
|   |                      |   └── NoUserFoundException.java
|   |                      |   └── ProductException.java
|   |                      |   └── ProductNotFoundException.java
|   |                      |   └── PurchaseReportException.java
|   |                      |   └── PurchaseReportNotFoundException.java
|   |                      |   └── UserException.java
│   │                      ├── model
│   │                      │   ├── Admin.java
│   │                      │   └── Product.java
|   |                      |   └── PurchaseReport.java
|   |                      |   └── User.java
│   │                      ├── repository
│   │                      │   ├── AdminRepository.java
│   │                      │   └── ProductRepository.java
|   |                      |   └── PurchaseReportRepository.java
|   |                      |   └── UserRepository.java
│   │                      ├── service
│   │                      |    ├── AdminService.java
|   |                      |    └── AdminServiceImpl.java
|   |                      |    ├── ProductService.java
|   |                      |    └── ProductServiceImpl.java
|   |                      |    ├── PurchaseReportService.java
|   |                      |    └── PurchaseReportServiceImpl.java
|   |                      |    ├── UserService.java
|   |                      |    └── UserServiceImpl.java
│   └── resources
│       └── application.properties
└── test
    ├── java
    └── resources

16 directories, 31 files

Project Structure
This project uses Spring Boot for Model and Controller Implementation Availaible apis are -

/adminUsers 
/adminUsers/{adminUserName}
/login
/products/CRUD
/products/{id}
/products/{price}
/admin/purchaseReport/CRUD
/admin/purchaseReports/{id}
/admin/purchaseReports/{category}
/users
/users/{emailId}
/loginUser

Current Implementation relies simply on String for storing order list.

It can be extended to utilize many-to-many relationship b/w Shoe and PurchaseReport Entities.

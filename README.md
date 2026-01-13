Billing and Product_Management_JavaBackend
Project Overview:
This project is a Billing and Invoice Backend Application developed using Java and Spring Boot. It follows a layered architecture to keep the code organized and easy to maintain. The application provides REST APIs to manage products, customers, and generate invoices based on customer orders with GST calculations. All APIs are tested using Postman.

Architecture:
Controller → Service → Repository → Database

Tech Stack:
Java
Spring Boot
Spring Web
Maven
JDBC
MySQL
Swagger (API Documentation)
Postman (API Testing)
Git & GitHub

Project Structure:
billing-backend
│
├── controller
│   ├── ProductController.java
│   ├── CustomerController.java
│   └── InvoiceController.java
│
├── service
│   ├── ProductService.java
│   ├── CustomerService.java
│   └── InvoiceService.java
│
├── repository
│   ├── ProductRepository.java
│   ├── CustomerRepository.java
│   └── InvoiceRepository.java
│
├── model
│   ├── Product.java
│   ├── Customer.java
│   └── Invoice.java
│
└── BillingApplication.java

Features Implemented:
Product Management:
Add and view products
Store product price, GST percentage, and stock details

Customer Management:
Add and manage customer information

Invoice Management:
Generate invoices based on customer orders
Automatically calculate GST
Display total billing amount

API Testing:
All REST APIs are tested using Postman, including:
Product APIs
Customer APIs
Invoice generation APIs

How to Run the Project:
Clone the repository
Open the project in IntelliJ IDEA or Eclipse
Configure MySQL database connection
Run the main Spring Boot application class
Test the APIs using Postman or Swagger

Author:
Srushti Mohadikar


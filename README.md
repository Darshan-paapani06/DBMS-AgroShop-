🌾 AgroShop — DBMS-Driven E-Commerce Platform   
Overview

AgroShop is a database-centric e-commerce web application designed to connect farmers, suppliers, and consumers through a structured and efficient digital marketplace. The primary objective of this project is to demonstrate core DBMS concepts such as relational modeling, normalization, constraints, queries, and transaction handling in a real-world business scenario.

The platform enables users to browse agricultural products, place orders, and manage inventory while ensuring data consistency, integrity, and scalability.

Project Objective

This project is developed as part of a DBMS academic requirement to:

Apply database design principles to a real-world e-commerce use case

Implement relational schemas with proper normalization

Execute CRUD operations using SQL

Demonstrate role-based access and transactional workflows

Functional Requirements
User Module

User registration and authentication

Browse agricultural products by category

View product details and pricing

Place orders and view order history

Admin Module

Manage products (Add / Update / Delete)

Manage categories and stock levels

View all user orders

Maintain supplier information

Database Operations

Insert, update, delete, and retrieve records

Maintain referential integrity using foreign keys

Execute complex SQL queries for reporting

Ensure ACID compliance for transactions

Tech Stack

Frontend: HTML5, CSS3, JavaScript

Backend: PHP / Python (Flask) / Java (JSP) (as per implementation)

Database: MySQL / PostgreSQL

Server: Apache / XAMPP / Localhost

Version Control: Git & GitHub

Database Design
Key Entities

Users

Products

Categories

Orders

Order_Details

Suppliers

Payments

Relationships

One user → Many orders

One order → Many products

One category → Many products

One supplier → Many products

Normalization

Database normalized up to 3NF

Eliminated data redundancy

Ensured functional dependency consistency

ER Diagram (Conceptual)

(ER diagram can be added here as an image or PDF for academic submission.)

Database Schema (Sample)
Users(user_id, name, email, password, role)
Products(product_id, name, price, stock, category_id, supplier_id)
Orders(order_id, user_id, order_date, total_amount)
Order_Details(order_id, product_id, quantity)
Categories(category_id, category_name)
Suppliers(supplier_id, supplier_name, contact)

Project Structure
AgroShop/
│
├── frontend/
│   ├── index.html
│   ├── products.html
│   └── cart.html
│
├── backend/
│   ├── connect_db.*
│   ├── user_module.*
│   ├── product_module.*
│   └── order_module.*
│
├── database/
│   ├── schema.sql
│   └── sample_data.sql
│
└── README.md

Installation & Setup

Clone the repository:

git clone https://github.com/<your-username>/AgroShop.git


Import the database:

Open phpMyAdmin / DB tool

Import schema.sql and sample_data.sql

Configure database credentials in backend files

Run the project on localhost server

Sample SQL Queries

Retrieve all products in a category

Fetch user order history

Calculate total sales per day

Identify low-stock products

Security Considerations

Input validation to prevent SQL injection

Role-based access control

Secure password storage (hashing)

Transaction rollback on failure

Academic Outcomes

This project demonstrates:

Practical application of DBMS concepts

Real-world relational database modeling

Efficient SQL query execution

Integration of database with web interface

Future Enhancements

Online payment integration

Farmer-to-consumer direct selling

Advanced analytics dashboard

Cloud database deployment

Mobile application support

License

This project is intended for educational purposes under the MIT License.

Developer

Darshan Gowda T S
E-mail- darshanpaapani@gmail.com
Student | DBMS | Web Development
GitHub: https://github.com/
darshangowdats

# Costumer_Relational_Management
The CRM System is a lightweight Java (JSP/Servlets) and MySQL web app for managing customer data via a secure dashboard. Users can add, view, update, and delete customer info like name, email, and phone. Ideal for small businesses or teams needing efficient client data management.
# 💼 Customer Relationship Management (CRM) System

A lightweight, web-based CRM system built using Java (JSP/Servlets), MySQL, and styled with modern UI components. This application allows users to manage customer data through a secure, session-based dashboard—ideal for small businesses, startups, and internal teams.

## 🚀 Features

- User authentication (login/logout)
- Add new customers with name, email, and phone
- Update customer details
- Delete customers
- View all customer records in a table
- Responsive and styled dashboard UI

## 🛠 Technologies Used

- Java (JSP/Servlets)
- MySQL Database
- Apache Tomcat Server
- HTML/CSS/JavaScript
- NetBeans (for development)

Here is the Database schema:

## 🗃️ Database Schema (MySQL)

```sql
CREATE TABLE tasks (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100),
    phone VARCHAR(20)
);

CREATE TABLE users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(50) UNIQUE,
    password VARCHAR(100)
); 


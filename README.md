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

  # Here is the Overview of my project:
<img width="1470" alt="Screenshot 2025-04-09 at 11 05 59 AM" src="https://github.com/user-attachments/assets/ebb4d873-9e9b-462b-ad0d-67cd3ea3d61b" />

<img width="1470" alt="Screenshot 2025-04-09 at 11 06 10 AM" src="https://github.com/user-attachments/assets/0db10aff-69b5-4722-9af6-ffafafc2b19f" />

<img width="1470" alt="Screenshot 2025-04-09 at 11 06 27 AM"
src="https://github.com/user-attachments/assets/cb866701-4f26-4c7a-8a7d-96c5367945b4" />

<img width="1470" alt="Screenshot 2025-04-09 at 11 06 39 AM" src="https://github.com/user-attachments/assets/d3db4d0b-ff88-4fbb-8f94-a76088a48628" />

<img width="1470" alt="Screenshot 2025-04-09 at 11 06 50 AM" src="https://github.com/user-attachments/assets/1c11f932-9eaa-4543-b908-15bdab003dc2" />

Here is the Database schema:

## 🗃️ Database Schema (MySQL)

```sql
CREATE DATABASE TaskManager;

USE TaskManager;

CREATE TABLE Tasks (
    id INT AUTO_INCREMENT PRIMARY KEY,
    title VARCHAR(255) NOT NULL,
    description TEXT,
    category VARCHAR(100)
);

CREATE TABLE Users (
    id INT AUTO_INCREMENT PRIMARY KEY,
    username VARCHAR(100) NOT NULL UNIQUE,
    password VARCHAR(255) NOT NULL
);

INSERT INTO Tasks (title, description, category) VALUES
('Complete Project Report', 'Finalize and submit the final report for the AI project.', 'Work'),
('Grocery Shopping', 'Buy vegetables, fruits, milk, and other essentials.', 'Personal')




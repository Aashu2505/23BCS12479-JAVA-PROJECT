# 🚗 Vehicle Registration System

A simple *web-based Java Servlet project* for registering and managing vehicle details.  
This project demonstrates how front-end web forms can interact with a backend server and a database using *HTML, CSS, Java Servlets, and MySQL*.

---

## 📖 Project Overview

The *Vehicle Registration System* allows users to register new vehicles and store owner details in a MySQL database.  
It helps manage vehicle data digitally instead of manual paper records.

### ✨ Key Features
- Vehicle Registration through a web form
- Data validation using Java Servlets
- Storage of vehicle details in MySQL database
- Prevention of duplicate vehicle entries
- User-friendly interface using HTML & CSS

---

## 🧩 Tech Stack

| Layer | Technology |
|--------|-------------|
| Frontend | HTML, CSS |
| Backend | Java Servlets |
| Database | MySQL |
| Server | Apache Tomcat |
| IDE | Visual Studio Code |

---

## ⚙ How It Works

1. User opens the **register.html** form and enters vehicle details (Owner Name, Email, Phone, Vehicle Number, Type, Model).
2. When submitted, the form sends data to the **RegisterVehicleServlet**.
3. The servlet processes the request:
   - Connects to MySQL using JDBC
   - Inserts new record (if vehicle number is not duplicate)
4. A response message (like “Vehicle Registered Successfully!”) is displayed to the user.

---

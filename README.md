## **Overview**

This project implements a localized Airline Reservation and Management System based on real-world Pakistani aviation data. The system streamlines the complete lifecycle of airline operations, from flight scheduling and ticket booking to boarding pass generation.

The primary focus of this project is to ensure a robust relational database design with proper normalization and strict data integrity enforcement. The system is designed to handle operational efficiency, secure access control, and financial transaction management within an airline environment.

---

## **Database Architecture**

### **ER Modeling**

A structured Entity-Relationship (ER) model was designed to represent the complete airline management workflow. The main entities include:

* Flights
* Passengers
* Staff
* Bookings
* Baggage
* Payments

Relationships between these entities were established using well-defined Primary Keys and Foreign Keys to ensure accurate data linkage and consistency.

---

###**Screenshots**###
<img width="242" height="400" alt="airlineSystem_databaseView" src="https://github.com/user-attachments/assets/14906212-2517-4b7d-a471-427abbbbb6b8" />
<img width="975" height="580" alt="adminForm" src="https://github.com/user-attachments/assets/0d4e0e22-c74b-4a2c-8b16-2d74e79d1d3f" />
<img width="975" height="510" alt="userForm" src="https://github.com/user-attachments/assets/42ddb1ae-2966-4ba7-9932-0373b3681587" />
<img width="975" height="486" alt="employeeForm" src="https://github.com/user-attachments/assets/9a755967-67c5-45b7-9bb4-3def78f683bb" />
<img width="719" height="521" alt="airlineTable" src="https://github.com/user-attachments/assets/74b5d3dc-8011-4fcc-8e42-8546ab7389b6" />
<img width="975" height="576" alt="boardinPass_table" src="https://github.com/user-attachments/assets/d31b2a4f-ed02-4be5-bbff-1d27b37bcc01" />
<img width="575" height="816" alt="SQL_query" src="https://github.com/user-attachments/assets/5ca4039b-4d5f-4786-b198-616c01f63138" />


### **Normalization**

Normalization techniques were applied up to Third Normal Form (3NF) to:

* Eliminate data redundancy
* Improve data consistency
* Maintain a scalable and maintainable database structure
* Ensure logical data organization across related tables

---

### **Referential Integrity**

To enforce data accuracy and maintain consistency across the system, the following constraints were implemented:

* Primary Key Constraints
* Foreign Key Constraints
* Cascading Update and Delete Rules

These constraints ensure that relationships between tables remain valid and prevent orphan records or inconsistent data entries.

---

## **Key Features**

### Role-Based Access Control (RBAC)

The system implements role-based access control with separate permissions and interfaces for:

* **Admin** – Full system control, database management, and staff oversight
* **Employees** – Operational management including flight handling and passenger services
* **Passengers** – Flight booking, profile management, and ticket access

---

### ✈️ Operational Management

* Real-time flight searching
* Automated seat allocation management
* Baggage tracking system
* Booking confirmation and boarding pass generation

---

### Financial Integration

* Automated payment recording
* Billing and invoice generation
* Secure transaction management
* Payment history tracking

---

## **Tech Stack**

* **SQL** (DDL, DML, Constraints, Joins, Triggers where applicable)
* **Relational Database Management System** (SQL Server / MySQL)
* **Frontend**: C++ / C# / Python (based on implementation)
* **UML Modeling**: draw.io

---

This system demonstrates strong database design principles, structured development practices, and real-world applicability in airline operations management.

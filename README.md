# Hospital Management System – ER Diagram & SQL

## 📌 Project Overview
This project focuses on the **database design and implementation** of a **Hospital Management System** using an **Entity–Relationship (ER) model** and **MySQL**. The system organizes hospital data efficiently and supports core operations such as patient management, doctor consultations, room allocation, billing, and medical records.

---

## 🧩 ER Diagram
The ER diagram was created using **MySQL Workbench** and models the relationships between key hospital entities.

### Main Entities
- Patient
- Doctor
- Employee
- Nurse
- Receptionist
- Rooms
- Bills
- Test Report
- Records

### Key Relationships
- Patients consult doctors (many-to-many)
- Patients are assigned rooms
- Nurses govern rooms
- Receptionists maintain records
- Patients pay bills and receive test reports
- Employees are specialized into nurses and receptionists using **ISA (inheritance)**

The ER model ensures **data normalization**, minimizes redundancy, and provides a clear structure for database implementation.

---

## 🗄️ SQL Implementation
Based on the ER diagram, the database schema was implemented using **MySQL**.  
The implementation includes:
- Primary and foreign key constraints
- One-to-many and many-to-many relationships
- Junction tables for complex relationships
- Sample data insertion
- Triggers for data validation
- Analytical SQL queries for reporting



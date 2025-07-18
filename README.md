# 🩺 ORGAN TRANSPLANTATION DATABASE SYSTEM

This project presents a robust **Organ Transplantation Database System** developed using **Java (Swing GUI)** and **MySQL**, aimed at improving the efficiency, transparency, and reliability of the organ transplantation process.

The system is designed to manage and monitor data related to donors, recipients, hospitals, staff, and NGOs. It also incorporates important database concepts such as normalization, triggers, cursors, concurrency control, and recovery mechanisms.

---

## 🎯 Objective

To streamline and centralize the management of donor and recipient information using a secure and scalable database-backed system that facilitates:
- Efficient donor-recipient matching
- Real-time organ tracking
- Automated data entry and reporting
- Seamless collaboration among hospitals, NGOs, and medical staff

---

## 🧠 Key Features

- ✅ Java GUI built with **Swing**
- ✅ Backend database in **MySQL**
- ✅ Data operations: insert, view, and manage Donors, Recipients, Hospitals, and Staff
- ✅ Use of **ER Diagrams**, **Relational Schemas**, **SQL Triggers**, **Cursors**, and **Joins**
- ✅ Concurrency control with **transactions**
- ✅ Recovery mechanisms using **logging and exception handling**

---

## 🛠️ Tech Stack

| Component       | Technology         |
|----------------|--------------------|
| Frontend        | Java (Swing GUI)   |
| Backend         | MySQL              |
| Connectivity    | JDBC               |
| DBMS Concepts   | Normal Forms, Triggers, Cursors, Views, ERD |
| Dev Tools       | IntelliJ / Eclipse, MySQL Workbench |

---

## 🚀 Getting Started

### 🔧 Prerequisites
- Java JDK 8+
- MySQL Server
- Any Java IDE (Eclipse, IntelliJ, NetBeans)

### 📥 Clone the Repository
```bash
git clone https://github.com/krishnamuttevi/Organ-Transplantation-Database-System.git
cd Organ-Transplantation-Database-System
```
⚙️ Set Up MySQL Tables
Import the SQL schema and table definitions from the provided script or manually execute table creation commands in schema.sql.

▶️ Run the Application
Compile and run the OrganTransplantationDatabase.java file. GUI will appear with buttons for each table. Use the form to add/view records.
📷 Screenshots (Optional)
📌 Insert screenshots of UI like:

Main window

Donor entry form

Recipient insertion

Display window showing live DB data

📁 Project Structure
```
Organ-Transplantation-Database-System/
├── OrganTransplantationDatabase.java     # Main Java GUI code
├── schema.sql                            # MySQL table creation script
├── README.md                             # Project documentation
└── (Other Java class files per form)     # DonorWindow, RecipientWindow, etc.

```
🧪 DBMS Concepts Used
Entity-Relationship Diagram (ERD)

Relational Schemas & Normalization (1NF → 5NF)

Triggers (before insert/update)

Cursors for multiple table iteration

Joins across Hospital, NGO, Donor, Recipient

Transaction management (BEGIN, COMMIT, ROLLBACK)

Recovery mechanisms via logging and exception handling

🧾 Project Report
A detailed academic report is included in the repository PDF (Organ Transplantation Database System.pdf), covering:

Problem Statement

ER Model

Normalization

SQL Queries

Code Implementation

Results & UI Screenshots

👨‍💻 Submitted By
Shreeman M (RA2211028010166)

M. Krishna Chaitanya (RA2211028010165)

S. Charith (RA2211028010197)

🎓 Guide
Dr. Rajaram V
Assistant Professor
Department of Networking & Communications
SRM Institute of Science and Technology


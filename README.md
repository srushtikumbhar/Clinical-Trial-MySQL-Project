# Clinical Trial Management & Analytics System (MySQL)

## 📌 Project Overview
This project implements a relational MySQL database to manage and analyze clinical trial data.
It models real-world entities such as clinical trials, research sites, investigators, patient
enrollments, adverse eventsband trial outcomes, following industry and regulatory standards.

The system supports operational reporting, safety monitoring and analytical insights using
industry-grade SQL queries, views and stored procedures.

---

## 🎯 Objectives
- Design a normalized relational database for clinical trial management
- Store real-world style clinical trial data aligned with ClinicalTrials.gov concepts
- Perform analytical queries for enrollment, safety and outcomes
- Implement views for reporting and stored procedures for operational workflows
- Demonstrate MySQL best practices used in pharma and healthcare analytics

---

## 🛠️ Technologies Used
- **Database:** MySQL 8.x
- **Client Tool:** MySQL Workbench
- **Domain:** Pharma / Healthcare / Clinical Research

---

## 🗂️ Database Schema Overview
The database includes the following core entities:

- **Trials:** Clinical study details (phase, indication, status)
- **Sites:** Hospitals and research centers
- **Investigators:** Principal investigators linked to sites
- **Patients:** Anonymized participant data
- **Enrollments:** Patient-to-trial mapping
- **Adverse Events:** Pharmacovigilance and safety data
- **Trial Results:** Outcome and success metrics

All relationships are enforced using primary and foreign key constraints to maintain data integrity.

---

## 🔑 MySQL Concepts Demonstrated
- Database and table creation
- Primary keys and foreign keys
- Data types and constraints
- One-to-many and many-to-many relationships
- Joins and subqueries
- Aggregation and analytical queries
- Views for reporting
- Stored procedures for business logic
- Indexes for performance optimization

---

## 📊 Key Analytical Queries
- Patient enrollment per clinical trial
- Trial phase-wise distribution
- Adverse event frequency and severity analysis
- Investigator and site mapping
- Trial outcome success rate analysis
- Disease indication-wise enrollment trends

---

## ⚙️ How to Run the Project
1. Open MySQL Workbench and connect to your MySQL server
2. Execute SQL files in the following order:
   - `01_database_setup.sql`
   - `02_schema.sql`
   - `03_sample_data.sql`
   - `04_queries.sql`
   - `05_views.sql`
   - `06_procedures.sql`
   - `07_indexes.sql`

---

## 📌 Use Cases
- Clinical trial data management
- Pharma analytics and reporting
- Pharmacovigilance and safety monitoring
- Academic and placement portfolio demonstration

---

## 👤 Author
**Srushti Kumbhar**  
M. Tech. Pharmaceutical Technology (Biotechnology)  
National Institute of Pharmaceutical Education and Research (NIPER), S.A.S. Nagar

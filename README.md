
🚲 Bicycle Rental Database System

A relational database project designed and implemented for a Bicycle Rental Company, developed as part of the Introduction to Databases course at Marmara University.

The system manages all core operations of a bike rental business — customer registration, bicycle tracking, reservations, payments, insurance policies, penalties, and maintenance operations — through a well-structured relational database built in Microsoft SQL Server (MSSQL).

📌 Project Overview

In modern cities, bicycle rental services play an important role in sustainable urban transportation. Managing these operations manually often leads to data redundancy, inconsistent records, and inefficient tracking of maintenance or insurance dates.

This project automates the following key operations:

Registering customers and bicycles
Handling reservation and payment processes
Calculating rental costs based on bicycle class and duration
Recording maintenance activities performed by staff members
Ensuring every bicycle is covered by a valid insurance policy
Tracking penalties for late returns or damaged bicycles

🗂️ Entities

Entity	Description
Customer	Individuals who rent bicycles
Bicycle	Physical bicycles identified by a unique QR code
Bicycle_Model	Technical specs and brand info of bicycles
Bicycle_Class	Pricing structure and category (mountain, city, electric, etc.)
Bicycle_Type	Bicycle type classification
Insurance	Insurance policies covering bicycles
Reservation	Rental transactions between customers and bicycles
Penalty	Additional charges for rule violations
Maintain	Maintenance and repair records
Maintain_Personal	Staff members performing maintenance

🛠️ Database Operations Covered

30 SELECT queries — including JOIN, GROUP BY, HAVING, TOP, EXISTS, IN, LIKE, subqueries, UNION, INTERSECT, EXCEPT, and date functions
5 INSERT statements — adding new records
5 UPDATE statements — modifying existing data
5 DELETE statements — removing records
5 ALTER TABLE statements — modifying table structure
5 DROP TABLE statements — removing temporary tables
10 CREATE INDEX statements — optimizing query performance
10 CREATE VIEW statements — active rentals, VIP customers, daily income analysis, expiring insurances, and more

📁 Repository Structure

bicycle-rental-database-system/
├── README.md
├── Phase1_Project_Report.pdf   # System description, requirements, ER diagram, data dictionary
└── Phase2_SQL_Queries.pdf      # SQL queries, DML/DDL operations, indexes, views (with query results)

🧩 Entity Relationship Diagram

The full ER diagram, including entity relationships and cardinalities (1-1, 1-*), is available in Phase1_Project_Report.pdf.

👥 Team Members

Name	Student 
Sevinç ÇAKAR	
Eylül ÇİMEN	
Nehir KARASAKAL	
Yasin SÜLEYMANOĞLU	
Instructor: Assoc. Prof. Selçuk KIRAN

🎓 Course

Introduction to Databases — Marmara University

⚙️ Technology

Microsoft SQL Server (MSSQL / SSMS)


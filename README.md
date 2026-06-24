# Pharmacy-Management-System
A full-featured Pharmacy Management System built with C# Windows Forms and MySQL 8.0 — featuring POS sales, inventory management, purchase orders, PDF reports, and role-based access control
CureWell Pharmacy Management System:
A comprehensive desktop-based Pharmacy Management System developed as a 
Semester Final Project for the Database Systems (DBS) course at UET Lahore.
 Built With:
- **Frontend:** C# Windows Forms (.NET Framework 4.7.2)
- **Backend:** MySQL 8.0
- **PDF Reports:** iTextSharp 5.5.13
- **IDE:** Visual Studio 2022
  Features:
-  Secure login with SHA-256 password hashing and role-based access
-  Medicine inventory management with low stock alerts
-  Point-of-Sale (POS) interface with cart and receipt generation
-  Purchase order management with approval workflow
-  Customer and supplier management
- 11 PDF business reports (sales, inventory, expiry, performance)
-  Transaction-safe operations with automatic stock updates
-  Error logging to file system and database
  Database Highlights:
- 16 tables, 6 views, 4 stored procedures, 3 triggers, 15+ constraints
- Full audit trail and error logging tables
- Normalized to Third Normal Form (3NF)
Default Login:
| Username | Password | Role |
|---|---|---|
| admin | Admin@123 | Admin |
 Setup:
1. Run `SQL/pharmacy_db.sql` in MySQL Workbench
2. Update `Pwd=` in `App.config` with your MySQL password
3. Install NuGet packages: `MySql.Data` and `iTextSharp`
4. Build and run in Visual Studio — press F5

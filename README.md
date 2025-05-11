# Campus Library Management System

## 📖 Project Description
A comprehensive database system for managing library operations including:
- Book inventory tracking
- Borrower management
- Department affiliations
- Book loan transactions with penalty calculations

This system provides the foundation for a fully functional library management application with proper relational database structure.

## 🛠️ Technical Specifications
- **Database Type**: Relational (SQL)
- **Tables**: 4 (books, departments, borrowers, loaned_books)
- **Relationships**: 
  - One-to-Many (Departments → Borrowers)
  - Many-to-Many (Books ↔ Borrowers via loaned_books)

## 🚀 Setup Instructions

🛠️ Setup Instructions (MySQL Workbench)
Method 1: Manual Table Creation
Connect to your MySQL server in Workbench

Create the database:

Click the Create Schema button (lightbulb icon)

Name: campus_library_system

Build tables manually:

Right-click the new schema → Table → Create Table

For each table (books, departments, borrowers, loaned_books):

Define columns exactly as shown in the SQL schema

Set primary/foreign keys via the "Indexes" tab

Apply constraints (NOT NULL, etc.)

Insert sample data:

Right-click each table → Select Rows

Click the "Insert row" button (table icon with +)

Enter data row-by-row matching your records

Commit changes (disk icon)

Method 2: SQL Script Execution
Open a new SQL tab (File → New Query Tab)

Write your table creation commands manually:

sql
CREATE TABLE books(...);
CREATE TABLE departments(...);
-- etc.
Execute with Ctrl+Shift+Enter

Verify via:

sql
SHOW TABLES;
SELECT * FROM books LIMIT 1;
Schema Verification
Confirm proper setup by checking:

Table counts (4 tables total)

Books table has 9 records

Foreign key relationships appear in "Foreign Keys" 


   📊 Database Schema (ERD)
   
![ERD](https://github.com/user-attachments/assets/4a51f7b8-8602-44db-b11c-cf1378fd573c)




   

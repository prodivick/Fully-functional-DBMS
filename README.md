# Student Records Management System (MySQL)

## Description

This project implements a full-featured **Student Records Management System** using only **MySQL**. It allows administrators and educators to store, manage, and query student information including personal details, enrollments, departments, courses, and grades.

Key features:
- Store student data and assign them to departments
- Manage course offerings by department
- Track student enrollments in courses
- Record grades for enrolled students
- Optional user login system for admin and teacher roles

---

## How to Set Up the Project

### 1. Requirements
- **MySQL Server 8.0+**
- A MySQL client like:
  - MySQL Workbench
  - phpMyAdmin
  - Command-line MySQL client

### 2. Setup Instructions

1. Open your MySQL client and connect to your server.
2. Run the SQL file or paste the SQL commands provided in the `schema.sql` section.
3. (Optional) Insert sample data to test.

You can also import the schema using:
```bash
mysql -u your_username -p < student_records.sql
# Fully-functional-DBMS

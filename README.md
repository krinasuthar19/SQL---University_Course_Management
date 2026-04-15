
# University Course Management System

## Overview

The University Course Management System is a SQL-based database project that simulates a real-world academic environment. It manages students, courses, instructors, and departments while demonstrating essential and advanced SQL concepts.

The project covers database design, data manipulation, and analytical queries to extract meaningful insights.

---

## Project Objective

The objective of this project is to:

- Design a structured relational database  
- Implement CRUD operations  
- Apply SQL joins, subqueries, and aggregations  
- Demonstrate advanced SQL concepts like window functions and CASE expressions  
- Analyze academic data efficiently  

---

## Database Structure

The system consists of five main entities:

### Departments
Stores department details  
- DepartmentID (Primary Key)

### Students
Contains student information  
- StudentID (Primary Key)

### Courses
Stores course details and department mapping  
- CourseID (Primary Key)  
- DepartmentID (Foreign Key)

### Instructors
Contains faculty information  
- InstructorID (Primary Key)  
- DepartmentID (Foreign Key)

### Enrollments
Maps students to courses  
- EnrollmentID (Primary Key)  
- StudentID (Foreign Key)  
- CourseID (Foreign Key)

---

## Key Features

### Basic SQL Operations

- Database creation  
- Table creation with constraints  
- Insert, update, delete operations  
- SELECT queries  

---

### Intermediate SQL

- INNER JOIN, LEFT JOIN, RIGHT JOIN  
- GROUP BY and HAVING  
- Sorting and filtering  
- Subqueries (IN, EXISTS)  

---

### Advanced SQL

- Window functions  
- CASE expressions  
- Aggregate analytics  
- Derived columns  
- Date and string functions  

---

## Tech Stack

- MySQL  
- SQL  

---

## Project Files

- university_course_management.sql – Complete SQL script  
- README.md – Project documentation  
- ER Diagram (optional)  

---

## How to Run

1. Open MySQL Workbench, phpMyAdmin, or any SQL tool  
2. Copy the SQL script  

```sql
CREATE DATABASE university_db;
USE university_db;
````

3. Run the full script to:

   * Create tables
   * Insert data
   * Execute queries

---

## Sample Queries

* List all students
* Update instructor salary
* Find students enrolled in multiple courses
* Count students per department
* Join students with enrolled courses
* Compute running totals using window functions
* Categorize students using CASE statements

---

## Use Cases

* Academic database management
* Student-course tracking systems
* Learning SQL concepts
* Portfolio and academic projects

---

## Limitations

* Static dataset
* No frontend interface
* Limited scalability

---

## Future Improvements

* Add triggers and stored procedures
* Integrate with web applications
* Build dashboards using BI tools
* Expand dataset for real-world scenarios

---

## Conclusion

This project demonstrates the application of SQL in managing academic data and performing advanced queries. It provides a strong foundation in relational database design and data analysis.


# University Relational Database Management System

A Java-based University Database Management System developed as an academic project. The application provides a graphical user interface (GUI) for managing university records and demonstrates the implementation of a relational database using Java and SQL.

## Overview

This project was developed to demonstrate the concepts of:

- Relational Database Design
- Database Connectivity using Java
- CRUD (Create, Read, Update, Delete) Operations
- Entity-Relationship (ER) Modeling
- Java Swing GUI Development
- SQL Database Management

The system allows users to manage and maintain information related to students, teachers, departments, courses, and classes through an interactive desktop application.

## Features

### Authentication
- User login interface
- Username and password validation
- Reset functionality

### Student Management
- View student records
- Insert new student information
- Update existing records
- Delete student records

### Teacher Management
- Store and manage teacher information
- Perform database operations through GUI

### Department Management
- Manage department details
- Store department locations and budgets

### Course Management
- Track course information
- Assign courses to departments
- Associate teachers with courses

### Class Management
- Monitor student enrollment
- Track course participation
- Maintain department associations

## Database Design

The project follows a relational database architecture consisting of the following primary tables:

| Table Name | Description |
|------------|-------------|
| STD_INFO | Student information |
| TEACHER | Teacher information |
| DEPARTMENT | Department details |
| COURSE | Course information |
| CLASS | Class and enrollment records |

### Relationships

- One Department can have many Students.
- One Department can offer many Courses.
- One Teacher can teach multiple Courses.
- Each Course belongs to a single Department.
- Class records connect students with courses and departments.

## Technologies Used

- **Programming Language:** Java
- **GUI Framework:** Java Swing
- **Database:** SQL
- **IDE:** NetBeans
- **Database Design:** ER Modeling

## Project Structure

```
src/
├── conn/
│   └── DatabaseConnection.java
│
└── databaseproject/
    ├── logincheck.java
    ├── Department.java
    ├── Teacher.java
    ├── Course.java
    ├── Room.java
    └── Succes.java
```

## Learning Outcomes

Through this project, I gained practical experience in:

- Designing relational databases
- Implementing CRUD operations
- Connecting Java applications with databases
- Building desktop applications using Java Swing
- Creating and understanding ER diagrams
- Managing database relationships and constraints

## Screenshots

The project report contains screenshots demonstrating:

- Login Window
- Student Management Interface
- Insert Operation
- Update Operation
- Delete Operation
- Teacher Table
- Department Table
- Course Table
- Class Table
- Entity Relationship (ER) Diagram

## Future Improvements

- Enhanced user authentication
- Search and filtering functionality
- Improved UI/UX design
- Reporting and analytics features
- Role-based access control
- Migration to a modern database system

## Author

**Fariha Nusrat**

Bachelor's Academic Project

---

*This project was developed as part of an undergraduate university database course to demonstrate the practical implementation of relational database concepts using Java and SQL.*

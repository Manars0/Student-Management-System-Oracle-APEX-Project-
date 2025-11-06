## Student Management System (Oracle APEX Project)

A simple web-based student management system built using Oracle APEX and PL/SQL.
> This project was developed as part of the Forms Development (CT1453) course at King Saud University.
It allows users to manage student records through a user-friendly interface with forms, reports, and charts.

## Project Overview
This project aims to build a student information management application that enables data entry, modification, and analysis using Oracle APEX.
The application is connected to a local database where users can:
- Add new students
- View and edit student details
- Delete existing records
- Visualize student data through charts
- The system uses SQL tables and PL/SQL processes to handle all CRUD operations (Create, Read, Update, Delete).

## Database Structure
The project includes a single main table:
**project_student**	Stores all student information (ID, Name, GPA, University, Department).
The database automatically validates primary key constraints to prevent duplicate IDs.

## Application Pages
The Oracle APEX application consists of the following interactive pages:
- **Home Page**	Provides navigation buttons to access other pages easily.
- **Report Page**	Displays a list of all students with search and filter options.
- **Form Page**	Used for adding or editing student information.
- **Chart Page**	Displays a pie chart showing student distribution by university.

## Features
- Built with Oracle APEX using PL/SQL logic.
- CRUD functionality (Add, Edit, Delete, View).
- Interactive and responsive report page.
- Dynamic chart visualization based on query results.
- User-friendly web interface with automatic validation.

## How It Works
- When the application runs, it connects to the project_student table in the Oracle database.
- The system checks whether the table exists — if not, it is automatically created.
- The Report Page retrieves and displays all existing student records.
- The Form Page allows users to add or modify data through an APEX form.
- The Chart Page visualizes the data distribution using a dynamic SQL query.
- All PL/SQL logic (insert, update, delete) is handled by APEX process blocks.

## Technologies Used
- Oracle APEX
- PL/SQL
- SQL Developer
- Interactive Reports & Charts

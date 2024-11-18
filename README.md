Employee Management System
Description
This project is a Java-based Employee Management System that allows users to manage employee data using JDBC for database interaction.
The system supports the following CRUD operations:

-Create: Add new employees to the database.
-Read: Retrieve employee details by ID and view all employees.
-Update: Modify employee details in the database.
-Delete: Remove an employee from the database using their ID.
The project uses a relational database PostgreSQL to store employee records, and the EmployeeData class handles the database operations.
The Employee class represents an employee's data.

Database Schema: pined in files

Project Structure
Employee.java: Defines the Employee entity with fields for id, name, position, salary, and hireDate, along with getters, setters, and toString() method.
EmployeeData.java: Handles CRUD operations with the database using JDBC. It connects to the PostgreSQL database and performs database operations.
Main.java: Tests the CRUD operations by creating, reading, updating, and deleting employee records.




# SQL-DATABASE
 created a database to manage student information, including names, ages, grades, and courses enrolled.
Skills demonstrated:
Data modeling and table design
SQL queries for data retrieval, filtering, and sorting
Use of primary keys and foreign keys for data integrity
Creation of views to simplify complex queries

CREATE DATABASE StudentDB;

-- Use the database
USE StudentDB;

-- Create a table to store student information
CREATE TABLE Students(
    StudentID INT AUTO_INCREMENT PRIMARY KEY,
    Name VARCHAR(50) NOT NULL,
    Age INT,
    Grade VARCHAR(2),
    CourseEnrolled VARCHAR(100)
);

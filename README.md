# SQL-DATABASE
This projects demonstrate my ability to handle database management.
CREATE DATABASE StudentDB;

-- Use the database
USE StudentDB;

-- Create a table to store student information
CREATE TABLE Students (
    StudentID INT AUTO_INCREMENT PRIMARY KEY,
    Name VARCHAR(50) NOT NULL,
    Age INT,
    Grade VARCHAR(2),
    CourseEnrolled VARCHAR(100)
);

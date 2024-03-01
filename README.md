# Learn-SQL-by-building-a-Students-Database-Part-1--FreeCodeCamp-
This repository contains the SQL scripts and instructions for creating a student database as part of the freeCodeCamp.org course "Learn SQL by Building a Student Database: Part 1."

Course Overview
------------------
In this course, you will learn SQL by building a student database from scratch. The course covers the following topics:

Creating a PostgreSQL database
-------------------------------------
->Designing tables for students, majors, courses, and their relationships

->Loading data from CSV files into the database

->Writing scripts to automate data insertion tasks

Getting Started
To begin the course, follow these steps:

Start the Terminal: Open the terminal by clicking the "hamburger" menu at the top left of the screen, navigating to the "terminal" section, and selecting "new terminal."

Echo Hello SQL: In the terminal, type echo hello SQL and press enter to ensure the terminal is functioning correctly.

Log into PostgreSQL: Use the command psql --username=freecodecamp --dbname=postgres to log into the PostgreSQL interactive terminal.

View Existing Databases: Use the \l command to view existing databases and ensure no conflicts exist.

Create the Students Database: Create a new database named "students" using the SQL command CREATE DATABASE students;.

Connect to the New Database: Connect to the newly created "students" database using the command \c students.

Database Structure
----------------------
The database will consist of the following tables:
----------------------------------------------------

Students: Information about each student.

Majors: Details of different majors.

Courses: Information about various courses.

Majors_Courses: Junction table linking majors and courses.

Scripting Tasks
------------------
The course guides you through various scripting tasks to:
-----------------------------------------------------------
->Create tables for students, majors, courses, and majors-courses relationships.

->Insert data from provided CSV files into the respective tables.

->Automate data insertion tasks using bash scripts.

->Dumping the Database

At the end of the course, you will use the pg_dump command to create a dump of the database into a SQL file (students.sql). This file will contain all the commands needed to rebuild the database.

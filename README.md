# University Database Project

## Overview

This project consists of designing and implementing a database for a university system. The database is designed to manage information about students, courses, professors, departments, classrooms, and academic advisors.

## Database Schema

The schema for the database includes several tables with various relationships between them. The main tables include:

- `Student`: Contains student personal information and references to their degree.
- `Degree`: Stores information about different academic degrees offered, related departments, and majors/minors.
- `Department`: Holds information about university departments.
- `Course`: Lists courses, including which department offers them, the professor teaching, and other course details.
- `Classroom`: Maintains classroom details where courses are held.
- `Professor`: Includes data about professors, their departments, and contact information.
- `Assistant_Professor`: Records assistant professors and their details.
- `Advisor`: Keeps track of academic advisors and their student advisees.

## Features

- Insert statements to populate the database with initial data for all tables.
- Queries to retrieve and manipulate the data, such as finding all courses in a particular department or listing all students advised by a specific advisor.

## How to Use

1. Set up your SQL environment (MySQL, PostgreSQL, etc.).
2. Run the provided SQL scripts to create tables and insert data.
3. Use the select statements to query the database.

## SQL Scripts

Included in the project are SQL scripts for:

- Creating tables: Defines the structure of each table including primary keys and data types.
- Altering tables: Adds foreign key constraints to establish relationships between tables.
- Inserting data: Populates tables with initial data for testing and usage.

## Contributing

Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

## Authors

- Your Name - *Initial work*

## Acknowledgments

- Hat tip to anyone whose code was used
- Inspiration
- etc

## Contact Information

For any inquiries or issues related to the database project, please contact [Youssef Abdelhady](yabdelhady905@gmail.com).


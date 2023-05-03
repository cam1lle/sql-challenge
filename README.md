# Pewlett Hackard Employee Database Analysis
This repository contains my solution to the Pewlett Hackard employee database project. The project is divided into three parts: data modeling, data engineering, and data analysis.

Background

As a new data engineer at Pewlett Hackard, my task is to analyze the employee database from the 1980s and 1990s. There are six CSV files available for analysis. The objective of this project is to design a database schema to store the data, import the CSV files into a SQL database, and answer various questions about the data using SQL queries.

Repository Structure

data/: This folder contains the six CSV files for the project.
Results/: This folder contains the SQL queries for creating tables, importing data, and performing analysis.
images/: This folder contains the ERD diagram generated using QuickDBD.

Data Modeling

I started by inspecting the CSV files and sketching an Entity Relationship Diagram (ERD) of the tables using a tool like QuickDBD. The ERD diagram can be found in the images/ folder. It shows the relationships between the tables and their attributes.

Data Engineering

Using the information obtained from the ERD diagram, I created a table schema for each of the six CSV files. I made sure to specify the data types, primary keys, foreign keys, and other constraints. I also verified that each primary key column was unique, and created a composite key where necessary. I then created the tables in the correct order to handle the foreign keys. Finally, I imported each CSV file into its corresponding SQL table.

Data Analysis

Using the SQL database created in the previous step, I wrote several SQL queries to answer the following questions:

List the employee number, last name, first name, sex, and salary of each employee.

List the first name, last name, and hire date for the employees who were hired in 1986.

List the manager of each department along with their department number, department name, employee number, last name, and first name.

List the department number for each employee along with that employee's employee number, last name, first name, and department name.

List first name, last name, and sex of each employee whose first name is Hercules and whose last name begins with the letter B.

List each employee in the Sales department, including their employee number, last name, and first name.

List each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.

List the frequency counts, in descending order, of all the employee last names (that is, how many employees share each last name).

The SQL queries can be found in the EmployeeSQL/queries.sql file.

Conclusion

This project required me to create a database schema to store the Pewlett Hackard employee database from the 1980s and 1990s. I also had to import the data into a SQL database and answer various questions about the data using SQL queries. This project helped me to enhance my data modeling, data engineering, and data analysis skills.

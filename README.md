# Pewlett Hackard Employee Database Analysis

## Background
As a newly hired data engineer at Pewlett Hackard, my first major task was to conduct a research project on the employees employed during the 1980s and 1990s. The company provided six CSV files containing the employee database from that period. My objective was to design tables, import the CSV files into a SQL database, and analyze the data.

## Repository Setup
To set up the project repository, I followed these steps:

1. Created a new repository named "sql-challenge" specifically for this project.
2. Cloned the repository to my local machine.
3. Inside the local Git repository, created a directory named "EmployeeSQL" for this challenge.

## Data Modeling
Before proceeding with data engineering and analysis, I inspected the CSV files and sketched an Entity Relationship Diagram (ERD) to visualize the table relationships. I used QuickDBD, an external tool, to create the ERD.

## Data Engineering
In the data engineering phase, I created a table schema for each of the six CSV files provided. Here are the key points to note:

* Specified appropriate data types, primary keys, foreign keys, and other constraints.
* Ensured that primary keys were unique and created composite keys when necessary.
* Created tables in the correct order to handle foreign keys.
* Imported each CSV file into its corresponding SQL table.

## Data Analysis
After completing the data engineering phase, I conducted data analysis to answer specific questions about the employee data. Here are the queries I executed:

1. Listed the employee number, last name, first name, sex, and salary of each employee.
2. Listed the first name, last name, and hire date for the employees hired in 1986.
3. Listed the manager of each department along with their department number, department name, employee number, last name, and first name.
4. Listed the department number for each employee along with their employee number, last name, first name, and department name.
5. Listed the first name, last name, and sex of each employee whose first name is Hercules and last name begins with the letter B.
6. Listed each employee in the Sales department, including their employee number, last name, and first name.
7. Listed each employee in the Sales and Development departments, including their employee number, last name, first name, and department name.
8. Listed the frequency counts, in descending order, of all employee last names to determine how many employees share each last name.

The data analysis provided insights into employee details and facilitated further exploration of the dataset.

# SQL-Challenge-

## Background

It’s a beautiful spring day, and it’s been two weeks since you were hired as a new data engineer at Pewlett Hackard. Your first major task is a research project on employees of the corporation from the 1980s and 1990s. All that remains of the database of employees from that period are six CSV files.

In this assignment, I will design the tables to hold data in the CSVs, import the CSVs into a SQL database, and answer questions about the data. In other words, I will perform **data modeling**, **data engineering**, and **data analysis**.

#### Data Modeling

Inspect the CSVs and sketch out an ERD of the tables

#### Data Engineering

* I used the provided information to create a table schema for each of the six CSV files. I specified the data types, primary keys, foreign keys, and other constraints.

  * For the primary keys, I verified that the column is unique. 

  * I created tables in the correct order to handle foreign keys.

* I imported each CSV file into the corresponding SQL table. 

#### Data Analysis

-- I performed the following queries:

1. Listed the following details of each employee: employee number, last name, first name, sex, and salary.

2. Listed the first name, last name, and hire date for employees who were hired in 1986.

3. Listed the the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.

4. Listed the department of each employee with the following information: employee number, last name, first name, and department name.

5. Listed first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."

6. Listed all employees in the Sales department, including their employee number, last name, first name, and department name.

7. Listed all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.

8. Listed the frequency count of employee last names (i.e., how many employees share each last name) in descending order.


As you examine the data, you begin to suspect that the dataset is fake. Maybe your boss gave you spurious data in order to test the data engineering skills of a new employee? To confirm your hunch, you decide to create a visualization of the data to present to your boss. Follow these steps: 

1. I imported the SQL database into Pandas. I made sure to make any necessary modifications for your username, password, host and database name:

2. I created a histogram to visualize the most common salary ranges for employees.

3. I created a bar chart of average salary by title.



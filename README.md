# sql-challenge
# Work in SQL

## Pewlett Hackard Employee Database

### Project Overview
This project focuses on developing a database from historical employee data of Pewlett Hackard, a fictional company, from the 1980s and 1990s. The data is organized in six CSV files, containing information about employees, departments, titles, and salaries. The primary goals are to design the database schema, import the data, and utilize SQL queries to extract meaningful insights regarding the organizational structure and compensation of employees.

### Files Description
- employees.csv: Contains employee details such as employee number, name, sex, and hire date.
- departments.csv: Lists departments with department number and name.
- dept_emp.csv: Maps employees to departments.
- dept_manager.csv: Identifies managerial relationships across departments.
- salaries.csv: Records salaries for each employee.
- titles.csv: Details employee titles.

### Usage
Once the database is set up and all data is imported, you can perform various SQL queries to explore and analyze the employee data. Here are some specific analyses you can perform:

- Employee Overview: Retrieve a complete list of employees including their employee number, last name, first name, sex, and salary. This can help in understanding the compensation structure across the company.

- Employment History: Analyze employment trends by listing all employees hired in a specific year, such as 1986, which can be useful for tracking hiring trends over time.

- Management Structure: Identify the managers for each department, providing insights into the leadership structure of the company. This includes department numbers, names, and manager details.

- Departmental Roster: Generate a list of all employees in each department, which is crucial for understanding departmental staffing.

- Specific Searches: For instance, find all employees named 'Hercules' whose last name begins with 'B'. This can be useful for specific personnel queries or audits.

- Department-Specific Queries: List all employees in critical departments such as 'Sales' or 'Development'. This helps in evaluating the roles and headcount in key business areas.

- Name Frequency Analysis: Perform an analysis to see how many employees share each last name, which can be interesting for demographic studies or designing communication strategies that consider name frequencies.
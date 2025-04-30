# Employee Salary Query Project

This project demonstrates how to create an SQLite database, insert sample employee data, and perform a query to find employees who earn more than the average salary in their respective departments.

## Project Setup

### Prerequisites
- Python 3.x
- `sqlite3` library (comes pre-installed with Python)

### Files Included
- `my_database.db`: SQLite database file created and populated with employee data.
- `employee_salary_query.py`: Python script to create the database, insert data, and perform the query.

## Steps to Run the Code

1. **Create and Setup the Database**: 
    The script creates an SQLite database named `my_database.db` (if it doesn't exist) and a table called `employees` with the following columns:
    - `employee_id`: Unique identifier for each employee.
    - `first_name`: Employee's first name.
    - `last_name`: Employee's last name.
    - `salary`: Employee's salary.
    - `department_id`: ID of the department the employee belongs to.

2. **Insert Sample Data**:
    Sample employee records are inserted into the `employees` table.

3. **Execute Query**:
    The script runs a query to find employees whose salary is greater than the average salary of their department. The result is printed with the employee's ID, first name, last name, salary, and department ID.

4. **Close the Connection**:
    After executing the query, the database connection is closed.

## How to Run

1. Ensure you

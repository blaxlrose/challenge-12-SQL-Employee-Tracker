# Challenge-12-SQL-Employee-Tracker


## Description

The goal of this application is to track the employees, their departmnets, and their roles in a fictional company.

## My Task

My task was to creat a command-line application that would manage a company's employee database, using Node.js, Inquirer, and MySQL.

## User Story

```md
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business
```

## Acceptance Criteria

```md
GIVEN a command-line application that accepts user input
WHEN the user starts the application
THEN the user is presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN the user chooses to view all departments
THEN the user is presented with a formatted table showing department names and department ids
WHEN the user chooses to view all roles
THEN the user is presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN the user chooses to view all employees
THEN the user is presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN the user chooses to add a department
THEN the user is prompted to enter the name of the department and that department is added to the database
WHEN the user chooses to add a role
THEN the user is prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN the user chooses to add an employee
THEN the user is prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN the user chooses to update an employee role
THEN the user is prompted to select an employee to update and their new role and this information is updated in the database
WHEN the user chooses to remove an employee
THEN the user is prompted to select an employee to remove and the employee is removed and this information is updated in the database
WHEN the user chooses to remove a department
THEN the user is prompted to select a department to remove and the department is removed and this information is updated in the database
WHEN the user chooses to remove an employee role
THEN the user is prompted to select an employee to remove and the role is removed and this information is updated in the database
```

## Links to deployed application

[Link to Github] https://github.com/blaxlrose/challenge-12-SQL-Employee-Tracker

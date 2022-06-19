# Employee Tracker

## Table of contents

> - [Title / Employee_Tracker](#title--Employee_Tracker)
>   - [Table of contents](#table-of-contents)
>   - [About / Synopsis](#about--synopsis)
>   - [Features](#features)
>   - [Intallation](#installation)
>   - [Usage](#usage)
>   - [User Story](#user-story)
>   - [Technology](#technology)
>   - [Credits](#credits)
>   - [How to Contribute](#How--to--Contribute)
>   - [Questions](#questions)

## About / Synopsis

Welcome to the Employee Tracker!  Use this command-prompt tool to manage a database for your employees.  You can add, remove, edit or change employees, departments, etc. using the command prompts.

## Features

Your answers to the various command prompts will auto-populate data in the company database.

## Installation

In the command line, type the following to install the relevant tools:

    - npm i node express inquirer mysql2
    - npm start

To Run this file from the MySQL command line, type:
- source db/db.sql
- source db/schema.sql

You can load default data to view an example of the use of these databases using the below seed data:
- source db/seeds.sql

## Usage
Use this command-prompt tool to manage a database for your employees.  You can accomplish all of the below through this tool.  Start the prompts by typing "npm start" in the commmand line.

- View All Departments
- View All Employees
- View All Roles
- Create New Departments
- Create New Employees (to include salaries, departments, and salaries)
- Create New roles
- Remove Departments
- Remove Employees
- Review Total Salaries by Department




Description of this App:
AS A business owner
I WANT to be able to view and manage the departments, roles, and employees in my company
SO THAT I can organize and plan my business

GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database

## Technology

## Questions

If you have additional questions, please contact the developer at scarlinj@gmail.com.
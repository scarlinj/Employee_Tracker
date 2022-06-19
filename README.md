# Employee Tracker

## Table of contents

> - [Title / Employee_Tracker](#title--Employee_Tracker)
>   - [Table of contents](#table-of-contents)
>   - [About / Synopsis](#about--synopsis)
>   - [Features](#features)
>   - [Intallation](#installation)
>   - [Usage](#usage)
>   - [Technology](#technology)
>   - [Credits](#credits)
>   - [How to Contribute](#How--to--Contribute)
>   - [Questions](#questions)

## About / Synopsis

Welcome to the Employee Tracker!  Use this command-prompt tool to manage a database for your employees.  You can add, remove, edit or change employees, departments, etc. using the command prompts in the terminal.

## Features

Your answers to the various command prompts will auto-populate data in the company database.  You can look up the data input, edit the data input, or delete the data input into the database.

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

You can view a video walkthrough demonstration at:

https://drive.google.com/file/d/1jYGeq7VoyeBPDjWYkW8IoalrA_EeDB1t/view

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



## Technology

This application was created with the following technologies:
- MySQL2
- Node.js
- Inquirer.js
- dotenv

## Credits

I worked on this program with assistance from fellow Github users hestokes, 786-go, and Jeongholee21.

## Questions

If you have additional questions, please contact the developer at scarlinj@gmail.com.
12-mysql-employee-tracker
Developers are often tasked with creating interfaces that make it easy for non-developers to view and interact with information stored in databases. Often these interfaces are known as Content Management Systems. In this homework assignment, your challenge is to architect and build a solution for managing a company's employees using node, inquirer, and MySQL.

Live Link to Demo
https://user-images.githubusercontent.com/88864267/141654533-76869e80-7608-4ddc-a9f1-437f8420331d.mp4

Description
Functional application.

GitHub repository with a unique name and a README describing the project.

The command-line application should allow users to:

Add departments, roles, employees

View departments, roles, employees

Update employee roles

User Story
As a business owner
I want to be able to view and manage the departments, roles, and employees in my company
So that I can organize and plan my business
Tech Used
inquirer
mySQL
console.table
Javascript
Node.js
Installation
Clone from GitHub
Open project directory, then npm install to install all required dependencies
Usage
install npm init -y to create a new .json file
npm i
npm i inquirer
npm i mysql
npm i console.table
make sure to run .sql file in mySQL workbench before running server.js so that tables are able to render correctly
run node server.js
make sure server.js is connected to SQL before continuing
run through prompts as required
Repository
Project Repo
Contributions
GitHub license
No front end files required.
use seed.sql to create an existing table to pull sample information from to make it easier to run through the app.

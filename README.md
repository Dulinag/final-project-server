# Campus Management System - Server Side

## Contributors
- **Dulina Gunasekara** - *Full-Stack Dev* - [Dulinag](https://github.com/Dulinag)
- **Ian Clarke** - *Full-Stack Dev* - [ianclarke03 ](https://github.com/ianclarke03 )

## Overview
This repository contains the server-side code for the Campus Management System, a full-stack CRUD application developed using Node.js, Express, PostgreSQL, and Sequelize ORM. It manages all backend functionalities including database operations and API routing for managing campuses and students.

# Demo Video For Client and Server (Click Either Link or Picture for the two Video Demos)

## [![Watch the video](https://img.youtube.com/vi/INSERT_VIDEO_ID_HERE/maxresdefault.jpg)](https://vimeo.com/945863884)

[![Watch the Server Side Demo](https://github.com/Dulinag/final-project-server/assets/83606238/631372f3-6f50-4bdb-9af4-1a64d0f48417)](https://vimeo.com/945863884)

## [![Watch the video](https://img.youtube.com/vi/INSERT_VIDEO_ID_HERE/maxresdefault.jpg)](https://vimeo.com/945860567)

[![Watch the Client Side Demo](https://github.com/Dulinag/final-project-server/assets/83606238/ccc1fb8b-9bcd-4f42-b63f-b942267a2ceb)](https://vimeo.com/945860567)



## Features
- CRUD operations for campuses and students
- RESTful API architecture
- Integrated Sequelize ORM for database management
- Validation and error handling


## API Endpoints
Below are the API endpoints available in this application:

### Campuses
- **GET /campuses** - Retrieve all campuses
- **POST /campuses** - Create a new campus
- **PUT /campuses/:id** - Update an existing campus
- **DELETE /campuses/:id** - Delete a campus

### Students
- **GET /students** - Retrieve all students
- **POST /students** - Create a new student
- **PUT /students/:id** - Update an existing student
- **DELETE /students/:id** - Delete a student



## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites
- Install PostgreSQL (Postgres) [[link](https://www.postgresql.org/download/)] - required to run the database
- Install Postman [[link](https://www.postman.com/downloads/)] - optional tool for API testing 

----------
### 1. Use the following process to ***import*** the Final Project server starter code repository to your GitHub account as the starter codebase
1.	Log on to GitHub
2.	Click on the + sign in the top right corner (next to the user icon)
3.	In the dropdown menu, select "Import repository"
4.	A new page will open
5.	In "Your old repository’s clone URL" field, enter: `https://github.com/johnnylaicode/server-starter-code`
6.	In "Your new repository details" field, enter your own repository name (e.g., "final-project-server")
7.	Click on the "Begin import" button to start the process
8.	After the process completed, your new "final-project-server" repository is created – as a completely independent codebase
9.	From this point on, you can clone your new repository, make changes, create feature branches, and create/merge pull requests

----------
### 2. Use the information below to ***clone*** the starter codebase to your local machine
After creating the starter codebase "final-project-server" repository on GitHub (see above), you can clone it to your local machine. The instructions on how to clone a GitHub repository are available at this [link](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).

----------
### 3. Set up and run the server (back-end) application on your local machine
1.	Start a terminal (e.g., Git Bash) on your local machine.
2.  Go to the "final-project-server" folder, enter the command to install dependencies: `npm install` 
3.	Start the server application by entering the command: `npm start` 
4.	After the server application is successfully started, its access address is at: `http://localhost:5001` 

<br/>

## Common Errors You May Encounter
### Error: password authentication failed for user "postgres"
This error is related to the user password you set for your own local Postgres database. 
#### Solution:
In the `server-starter-code/database/utils/configDB.js` file, replace the `dBpwd` value with your password for Postgres database.

```
  const dbName = 'starter-server';
  const dbUser = 'postgres';
  const dbPwd = '<your password>';
```


### Installing
A step-by-step series of examples that tell you how to get a development environment running:
1. Clone the repository:

2. Install NPM packages:

4. Start the server:



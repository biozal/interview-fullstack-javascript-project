# Javascript Full Stack Project/Task Manager 

## Introduction
In software development we use Agile concepts to work on features of a given software project we are on.  Tasks are assigned to a developer to work on and when all the tasks associated with the feature are complete, the feature is said to be complete and can ship to production.

The goal of this exercise is to create a backend service that will return a list of projects and associated tasks with the project.  Projects must have a title, description, due date and listing of tasks.  The task should have a title, description, due date, priority, and point size (using fibonacci scale).

The backend service must be built using Node.js and Javascript 6.  You are free to use any packages/frameworks you like to implement this backend service.  

The second part is to build a User Interface based on ReactJS for the backend service.  The first "page" should have a list of projects with the ability to add, update, or delete a project.  If you click on a project, you should get a listing of tasks associated to this project.  You can add, update, or delete tasks from the second page.  You are free to use any packages/frameworks you like to implement this UI.  If you are stuck for ideas, [Ant-d](https://ant.design/components/overview/), [Material Design](https://mui.com/core/), [Fluent UI](https://developer.microsoft.com/en-us/fluentui) are all great UI component libraries.

## Requirements
A user should be able to fully interact with either the Backend via tools like Postman or the Front End using Google Chrome or Firefox.

### Backend API

* The backend service must be written in Javascript 6 using NodeJS.
* The backend service can host the projects and tasks in any way the developer sees fit (in memory, file system, database, etc.)
* The backend service API can be implemented using the REST API standard or GraphQL
* The backend service must define the ability to do full CRUD (Create, Read, Update, Delete) operations for projects and tasks
* The backend service must be able to return a list of projects and associated tasks
* The backend service must have tests associated with the API calls built
* The backend service should use JSLint 

### Frontend
* The frontend must be written in Javascript 6 using ReactJS
* The frontend must have the first page list all projects and allow the user to add, update, or delete a project
* The frontend must give the option for the user to select a project to go to a page that lists all the tasks associated with that project.
* The frontend must have the second page list all tasks associated with a project and allow the user to add, update, or delete a task

All Javascript code must use the recommended best practices for JS 6 syntax listed on [Free Code Camp](https://www.freecodecamp.org/news/make-your-code-cleaner-shorter-and-easier-to-read-es6-tips-and-tricks-afd4ce25977c/).

## Submission
The code must be hosted in a GitHub repo with a readme fill that explains how to run the API and UI associated with it.




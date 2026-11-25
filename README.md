# cli-todo-list

## Project Overview
A command-line task management application built incrementally with Python.

## MVP Features
Add tasks with name
View tasks
Exit application

## Future Features
Add tasks with name and due date
Mark tasks as complete
Delete tasks 
Edit tasks, name, due date and completion status
View tasks sorted by due date, if same sort by completed last
Store tasks in persistent storage

## Technologies
Python

## User Stories

001 - I as a standard user want to be able to add tasks by name
002 - I as a standard user want to be able to view the list of tasks
003 - I as a standard user want to be able to exit the application
004 - I as a standard user want to be corrected when I enter invalid input

## Acceptance Criteria

001 
Selecting 1 prompts for a task name.
Valid tasks are stored in memory.
Empty task names are rejected.
A confirmation message is displayed.
The user returns to the main menu.

002
Selecting 2 displays stored tasks.
If no tasks exist, display an appropriate message.
Provide an option to return to the main menu.

003
Selecting 3 displays a goodbye message.
The program terminates.

004
Invalid menu choices display an error message.
The user is prompted to enter a valid option.
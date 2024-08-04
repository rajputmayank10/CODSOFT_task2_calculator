# CODSOFT_task2_calculator
# Overview
This is a command-line To-Do List application written in Python. The program allows users to manage tasks by adding new ones, viewing all tasks, and marking tasks as completed. The application runs in a loop, providing a simple menu to interact with.

# Features
Add Task: Add one or more tasks to the list.
Show Tasks: Display all tasks along with their status (Done or Not Done).
Mark Task as Done: Update the status of a specific task to Done.
Exit: Exit the application.
# Requirements
Python 3.x
# How to Use
Run the Program

Save the script as todo_list.py and run it using Python:
Interact with the Menu

The program will display a menu with the following options:

1. Add Task: Add new tasks. You will be prompted to enter the number of tasks you want to add, followed by the details of each task.
2. Show Tasks: View all tasks. The list will show each task with its current status (Done or Not Done).
3. Mark Task as Done: Mark a specific task as completed by entering its number.
4. Exit: Exit the application.
# Code Overview
Main Loop: The program runs in a loop, displaying the menu and processing user choices.
Add Task: Prompts the user to enter the number of tasks and details of each task, which are then added to the list.
Show Tasks: Iterates through the list of tasks and prints each task with its status.
Mark Task as Done: Updates the status of the selected task to Done based on its number.
Exit: Ends the loop and exits the program.
# Error Handling
Invalid Input: If the user enters non-numeric values where numbers are expected, the program handles these cases with appropriate messages.
Task Number Out of Range: If the user enters an invalid task number when marking a task as done, the program displays an error message.
# Contributing
Contributions to enhance or extend the functionality of this application are welcome. Feel free to submit issues, suggestions, or pull requests.

# License
This project is licensed under the MIT License. See the LICENSE file for details.

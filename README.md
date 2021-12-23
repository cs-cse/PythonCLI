# PythonCLI
Command line program made using Python to keep track of day to day tasks with several functionalities.

 Todo Command Line Application
Create a virtual environment (optional)

Python 3:

$ pip3 install virtualenv
$ virtualenv -p python3 venv

# Activate the environment:

source venv/bin/activate

Use cases

    Create a todo list
    Add, Edit and Delete todo items in a todo list
    Mark todo items as complete and incomplete
    Show all todo items in a todo list

# Commands

1. ./task add          => add a todo item to the selected list
2. ./task ls           => show all the todo items in the chosen list
3. ./task del INDEX    => remove a todo item
4. ./task done INDEX   => mark a todo item as completed
5. ./task help         => prints usage
6. ./task quit         => exit the application

JSON Files
lists.json

    stores a list of todo lists
    a todo list is a dict having title and created_at field

 OR

    stores a dict of todo lists having title as key and file name and time of creation as nested dict

list.json

    list refers to the todo list name
    stores a list of todo item
    each todo item is a dict having title, created_at, and completed field.


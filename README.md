EADME.mdlone Project

This project is an implementation of a simplified version of the AirBnB platform, focusing on the backend functionality. It includes models for managing users, properties, bookings, and more, along with a command-line interface for interacting with these models.
Command Interpreter
How to Start

To start the command interpreter, follow these steps:

    Clone the repository to your local machine:

bash

git clone https://github.com/yourusername/AirBnB_clone.git

    Navigate to the project directory:

bash

cd AirBnB_clone

    Run the console.py file:

bash

./console.py

How to Use

Once the command interpreter is running, you can use the following commands to interact with the models:

    create: Create a new instance of a class.
    show: Show the string representation of an instance.
    destroy: Delete an instance based on the class name and id.
    all: Print all string representations of all instances.
    update: Update an instance based on the class name and id.
    quit or EOF: Exit the command interpreter.

Examples
Creating an Instance

(hbnb) create BaseModel

Showing an Instance

(hbnb) show BaseModel 1234-1234-1234

Deleting an Instance

(hbnb) destroy BaseModel 1234-1234-1234

Listing All Instances

(hbnb) all

Updating an Instance

(hbnb) update BaseModel 1234-1234-1234 name "New Name"

Contributors
Simon Kariuki



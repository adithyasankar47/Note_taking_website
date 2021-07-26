# Todo List App with User Authentication

A website in which user can **login** using *email id* and *password* to create, delete and update **Todos**

The todo website has been succesfully **deployed** using **Heroku**.
It is accessible via the following link

[Todo-app-using-flask] (https://todo-app-using-flask.herokuapp.com/)

## Steps to deploy
1. Install the packages mentioned in Requirements
2. Run the command python .\main.py to deploy the  application
3. Use of virtual environment is advised

## Requirements
- Flask==2.0.1
- Flask-Login==0.5.0
- Flask-SQLAlchemy==2.5.1
- Jinja2==3.0.1
- python-dateutil==2.8.1
- SQLAlchemy==1.4.20
- virtualenv==20.6.0
- Werkzeug==2.0.1

## Basic Structure

- The login system is created using **flask-login** module.

- The login system will check for the strength of the password, validity of the username etc.

- The passwords are **hashed** before being stored in the database.


- **SQLAlchemy** is used as to create the database and to define database schema.

- All the user notes, email, password etc are stored in a database.

- **Bootstrap** is used to make the Navbar, buttons, and to make the page aesthetically pleasing

- Each element of the Todo list can be updated and deleted.

- Each user has access to only his respective Todo list after signing up and then logging in
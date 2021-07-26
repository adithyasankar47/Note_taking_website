# Todo List App with User Authentication

A website in which user can **login** using *email id* and *password* to create, delete and update **Todos**

The todo website has been succesfully **deployed** using **Heroku**.
It is accessible via the following link

[Todo-app-using-flask](https://todo-app-using-flask.herokuapp.com/)

## Steps to deploy
1. Install the packages mentioned in Requirements
2. Run the command python .\app.py to deploy the  application
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

### 1. Authentication System
    - The login system is created using flask-login module.

    - The login system will check for the strength of the password, validity of the username etc.

    - The passwords are hashed using sha256 before being stored in the database.

### 2. Database System 

    - SQLAlchemy is used as to create the database and to define database schema.

    - All the user notes, email, password etc are stored in a database.

### 3. UI Elements

    - Bootstrap is used to make the Navbar, buttons, and to make the page aesthetically pleasing
    - Javascript has been used to make the page more interactive.
    - Alerts have been provided to guide the user through the UI.
### 4. Functionality
    1. The user can access the webpage via the URL provided above.
    2. Then first time users can go to the signUp page using the navbar.
    3. They can signUp using an email, username and password.
    4. The passwords, username, email etc are checked before being accepted for security.
    5. After signUp the user will be redirected to the Login page and  asked to Login again redirected to the Login page. 
    6. On successful submission of Login details and authentication, the user will be directed to the page where they can add, delete or update Todos.
    7. They user can Logout using the option in the navbar after adding, modifying Todos.
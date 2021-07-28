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
- backports.entry-points-selectable==1.1.0
- click==8.0.1
- colorama==0.4.4
- distlib==0.3.2
- filelock==3.0.12
- Flask==2.0.1
- Flask-Login==0.5.0
- Flask-SQLAlchemy==2.5.1
- greenlet==1.1.0
- gunicorn==20.1.0
- itsdangerous==2.0.1
- Jinja2==3.0.1
- MarkupSafe==2.0.1
- numpy==1.20.3
- pandas==1.2.4
- platformdirs==2.0.2
- python-dateutil==2.8.1
- pytz==2021.1
- six==1.16.0
- SQLAlchemy==1.4.20
- virtualenv==20.6.0
- Werkzeug==2.0.1


## Basic Structure

#### 1. Authentication System
    - The login system is created using flask-login module.

    - The login system will check for the strength of the password, validity of the username etc.

    - The passwords are hashed using sha256 before being stored in the database.

#### 2. Database System 

    - SQLAlchemy is used as to create the database and to define database schema.

    - All the user notes, email, password etc are stored in a database.

#### 3. UI Elements

    - Bootstrap is used to make the Navbar, buttons, and to make the page aesthetically pleasing

    - Javascript has been used to make the page more interactive.

    - Alerts have been provided to guide the user through the UI.
#### 4. Functionality
    1. The user can access the webpage via the URL provided above.

    2. Then first time users can go to the signUp page using the navbar.

    3. They can signUp using an email, username and password.

    4. The passwords, username, email etc are checked before being accepted for security.

    5. After signUp the user will be directed to login again in the login page. 

    6. After verifying the login details, the user will be directed to the add, delete or update Todos page.
    
    7. They user can Logout using the option in the navbar after adding, modifying Todos.

## The screenshots of the website are attached below

### Signup page



![signup](https://user-images.githubusercontent.com/71591921/127265925-4d4befcc-f79b-46bb-a763-ae6379755ce6.JPG)


![signup2](https://user-images.githubusercontent.com/71591921/127265926-9c51b818-3175-454e-b7f3-bdd13a77c847.JPG)


![flash_messages_after_signup](https://user-images.githubusercontent.com/71591921/127265922-e367fae5-fd33-43cb-96c0-021737d519a3.JPG)

### Login page



![login](https://user-images.githubusercontent.com/71591921/127265924-cf8cb9b9-78bc-492f-800d-c31f16e9eb21.JPG)


![afterlogin](https://user-images.githubusercontent.com/71591921/127265921-2597855f-77db-4a99-8119-25219560ec88.JPG)

### After updating a todo

![todo_page](https://user-images.githubusercontent.com/71591921/127265928-82018aee-8536-45d7-b5a9-105cd7b5fba2.JPG)


![updating](https://user-images.githubusercontent.com/71591921/127265929-df4f85aa-8228-4fbe-8c0c-fb9d9316bd27.JPG)


![after_updating](https://user-images.githubusercontent.com/71591921/127265912-259dca67-5d74-4e2a-b2ad-9691a5d796c0.JPG)





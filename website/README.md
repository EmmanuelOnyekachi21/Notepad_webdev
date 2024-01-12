# Notepad Web App with Flask Authentication

This is a simple notepad web application with user authentication built using Python Flask. The project follows the tutorial provided by Tech with Tim on YouTube.

## Overview

This web app allows users to create, edit, and delete notes after authentication. Users can sign up for an account, log in, and securely manage their notes.

## Features

- User authentication (signup, login, logout)
- Create, edit, and delete notes
- Responsive web design for a seamless experience across devices

## Requirements

- Python 3.x
- Flask
- Flask-WTF
- Flask-Bcrypt
- Flask-Login
- SQLite (or any other database of your choice)

## Installation

1. Clone the repository:
```git clone https://github.com/yourusername/notepad-flask.git```


2. Navigate to the project directory:

```cd notepad-flask```


3. Install the required dependencies:


4. Set up the database:

```flask db init```
```flask db migrate```
```flask db upgrade```


5. Run the application:

flask run


6. Visit http://localhost:5000 in your browser to access the notepad web app.

## Configuration

Modify the config.py file to customize the application settings, such as the secret key, database URI, etc.

## Acknowledgments

Special thanks to Tech with Tim for the fantastic tutorial on building this notepad web app.

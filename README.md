# Flask Todo App

A simple Todo List web application built using **Flask**, **SQLAlchemy**, **SQLite**, and **Jinja2**. Users can create, view, update, and delete tasks through a clean web interface.

## Features

* Add new tasks
* View all tasks
* Update existing tasks
* Delete tasks
* SQLite database integration
* Jinja2 template inheritance
* Deployed on Render

## Technologies Used

* Python 3
* Flask
* Flask-SQLAlchemy
* SQLite
* HTML
* CSS
* Jinja2
* Gunicorn
* Render

## Project Structure

```text
ToDo-App/
│
├── app.py
├── requirements.txt
├── static/
│   └── css/
│       └── main.css
│
├── templates/
│   ├── base.html
│   ├── index.html
│   └── update.html
│
├── instance/
│   └── test.db
│
└── README.md
```

## Installation

### Clone the Repository

```bash
git clone https://github.com/A1lwin/ToDo-App.git
cd ToDo-App
```

### Create a Virtual Environment

```bash
python -m venv env
```

### Activate Virtual Environment

Windows:

```bash
env\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Application

```bash
python app.py
```

The application will be available at:

```text
http://127.0.0.1:5000
```

## Database Model

The Todo model contains:

| Field        | Type     | Description        |
| ------------ | -------- | ------------------ |
| id           | Integer  | Primary Key        |
| content      | String   | Task Description   |
| completed    | Integer  | Completion Status  |
| date_created | DateTime | Creation Timestamp |

## CRUD Operations

### Create

Add new tasks using the form on the home page.

### Read

Display all tasks stored in the database.

### Update

Modify an existing task using the update page.

### Delete

Remove tasks from the database.

## Deployment

The application is deployed on Render using Gunicorn.

Live URL:

```text
https://todo-app-t3xq.onrender.com
```

## Future Improvements

* Task completion status
* User authentication
* Responsive UI
* Search and filter tasks
* Due dates and reminders
* Dark mode support

## Author

**Allwin P**

Built as a learning project to understand Flask, SQLAlchemy, Jinja2, SQLite, Git, GitHub, and web deployment.

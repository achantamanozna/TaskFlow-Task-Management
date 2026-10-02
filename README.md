# TaskFlow - Task Management Application

A full-stack task management web application built using Python Flask, SQLite, HTML, CSS, and JavaScript.

TaskFlow helps users organize their daily activities by creating, updating, tracking, and completing tasks through a simple dashboard.

## Features

- User registration and login
- Secure password hashing
- User-specific task management
- Create, read, update, and delete tasks (CRUD)
- Mark tasks as completed or pending
- Task priorities (High, Medium, Low)
- Due dates
- Dashboard with task statistics
- Task search and filtering
- Responsive user interface
- SQLite database

## Technologies Used

- Python
- Flask
- SQLite
- HTML5
- CSS3
- JavaScript
- Jinja2

## Project Structure

```text
task_management_app/
│
├── app.py
├── tasks.db
├── requirements.txt
├── README.md
├── .gitignore
│
├── static/
│   ├── style.css
│   └── script.js
│
└── templates/
    ├── base.html
    ├── dashboard.html
    ├── edit_task.html
    ├── login.html
    └── register.html
```

## Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the project folder

```bash
cd task_management_app
```

### 3. Create a virtual environment

```bash
python -m venv venv
```

### 4. Activate the virtual environment

Windows:

```bash
venv\Scripts\activate
```

### 5. Install dependencies

```bash
pip install -r requirements.txt
```

### 6. Run the application

```bash
python app.py
```

### 7. Open in your browser

```text
http://127.0.0.1:5000
```

## Application Workflow

1. Register a new user account.
2. Log in to the application.
3. Create tasks with descriptions, priorities, and due dates.
4. Edit or delete tasks when required.
5. Mark tasks as completed or pending.
6. Track task statistics through the dashboard.

## Database

The application uses SQLite to store user accounts and task information.

## Future Improvements

- Email notifications
- Calendar integration
- Task reminders
- Deployment to a cloud hosting platform

## Author

Manzana Achantia

## License

This project is created for educational and internship purposes.
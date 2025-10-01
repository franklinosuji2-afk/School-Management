🎓 School Institute – Django Project

This is a Django-based web application for managing Teachers and Students.
It demonstrates how to build and structure a Django project with multiple apps, templates, models, and admin support.

📂 Project Structure

project2/
│── db.sqlite3                # SQLite database (local)
│── manage.py                  # Django project management script
│── README.md                  # Project documentation
│
├── school_institute/          # Main Django project
│   ├── settings.py            # Project settings
│   ├── urls.py                # Root URL routing
│   ├── views.py               # Project-level views
│   ├── wsgi.py / asgi.py      # Deployment entry points
│
├── students/                  # Students app
│   ├── models.py              # Student models
│   ├── views.py               # Student views
│   ├── urls.py                # Routes for students
│   ├── templates/students/    # Student templates
│   └── admin.py               # Student admin config
│
├── teachers/                  # Teachers app
│   ├── models.py              # Teacher models
│   ├── views.py               # Teacher views
│   ├── urls.py                # Routes for teachers
│   ├── templates/teachers/    # Teacher templates
│   └── admin.py               # Teacher admin config
│
└── templates/                 # Shared templates
    ├── welcome.html
    ├── bye.html
    └── school_institute/

✨ Features

Separate apps for Teachers and Students

Add, update, and view teachers and students

Django Admin Panel to manage data easily

Templates for displaying student/teacher details

SQLite database (lightweight for development)


Access the app

Home: http://127.0.0.1:8000/

Students: http://127.0.0.1:8000/students/

Teachers: http://127.0.0.1:8000/teachers/

Admin Panel: http://127.0.0.1:8000/admin/


📌 .gitignore

This project ignores files that shouldn’t be tracked in Git, such as:

__pycache__/, *.pyc → Python cache files

db.sqlite3 → Local database

venv/ → Virtual environment

.vscode/, .idea/ → Editor settings

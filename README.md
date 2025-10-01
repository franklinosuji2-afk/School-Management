🎓 School Institute – Django Project

A Django-based web application for managing Teachers and Students.
This project demonstrates how to structure a Django project with multiple apps, templates, models, and admin support.

📂 Project Structure
project2/
│── db.sqlite3                # SQLite database (local development)
│── manage.py                 # Django management script
│── README.md                 # Project documentation
│
├── school_institute/         # Main Django project
│   ├── settings.py           # Project settings
│   ├── urls.py               # Root URL routing
│   ├── views.py              # Project-level views
│   ├── wsgi.py / asgi.py     # Deployment entry points
│
├── students/                 # Students app
│   ├── models.py             # Student models
│   ├── views.py              # Student views
│   ├── urls.py               # Student routes
│   ├── templates/students/   # Student templates
│   └── admin.py              # Student admin config
│
├── teachers/                 # Teachers app
│   ├── models.py             # Teacher models
│   ├── views.py              # Teacher views
│   ├── urls.py               # Teacher routes
│   ├── templates/teachers/   # Teacher templates
│   └── admin.py              # Teacher admin config
│
└── templates/                # Shared templates
    ├── welcome.html
    ├── bye.html
    └── school_institute/

✨ Features

✅ Separate apps for Teachers and Students

✅ Add, update, and view teacher/student records

✅ Integrated Django Admin Panel for easy management

✅ Template-based UI for displaying data

✅ Lightweight SQLite database (ideal for development)

🖼️ Screenshots

Home Page
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/86a7bb74-c62b-43dd-a150-b45a7f1ca1b7" />


Students Page
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/e0b430ed-185b-491b-8f64-c6d9c8bfdf3b" />



Teachers Page
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/22158e0b-e6c2-436a-9e40-884791fe14c0" />



Details Panel
<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/89135288-6908-4640-9fcc-3b697de884f0" />

<img width="1920" height="1032" alt="Screenshot 2025-10-01 205648" src="https://github.com/user-attachments/assets/86216408-3ea4-487d-9a88-7ac5afc79986" />

<img width="1920" height="1032" alt="Screenshot 2025-10-01 205800" src="https://github.com/user-attachments/assets/4fb92d5a-df89-4706-82e0-ce4c87d86c8c" />

<img width="1920" height="1032" alt="image" src="https://github.com/user-attachments/assets/142c1b23-7c40-46e3-9d4f-0e1e0dcfa8e3" />



🚀 Getting Started

1. Clone the repository
git clone https://github.com/franklinosuji2-afk/School-Management.git
cd School-Management

2. Create & activate virtual environment
python -m venv venv
# Windows
venv\Scripts\activate

3. Install dependencies
pip install -r requirements.txt

4. Run migrations
python manage.py migrate

5. Start the development server
python manage.py runserver

🌐 Access the App

🏠 Home: http://127.0.0.1:8000/

👩‍🎓 Students: http://127.0.0.1:8000/students/

👨‍🏫 Teachers: http://127.0.0.1:8000/teachers/

🔑 Admin Panel: http://127.0.0.1:8000/admin/

⚠️ Links work only when the development server is running locally.

📌 .gitignore

__pycache__/, *.pyc → Python cache files

db.sqlite3 → Local database

venv/ → Virtual environment

.vscode/, .idea/ → Editor configs

🛠️ Tech Stack

Backend: Django (Python)

Database: SQLite (development)

Frontend: Django Templates (HTML, CSS, Bootstrap-ready)

🔮 Future Enhancements

Add user authentication & permissions

Deploy the app publicly (Heroku, PythonAnywhere, AWS)

Integrate Docker & Docker Compose

Add REST API endpoints for mobile integration

Implement search, filtering, pagination

Add unit and integration tests


👤 Author

Name: Chinonso Franklin Osuji

Email: franklin.osuji2@gmail.com

GitHub: https://github.com/franklinosuji2-afk

LinkedIn: www.linkedin.com/in/franklin-osuji-a96003321

📄 License

This project is licensed under the MIT License – see the LICENSE
file for details.


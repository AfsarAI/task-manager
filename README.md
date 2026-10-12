# Task Manager (Django + React Learning Project)

A full-stack task manager application built for learning Django REST Framework and React.

## 🚀 Project Overview
- **Backend:** Django & Django REST Framework
- **Frontend:** React (Coming soon)
- **Database:** SQLite (Development)

## 📁 Project Structure
```text
task-manager/
├── config/             # Django project settings & URL configuration
├── tasks/              # Django app for task management API
├── manage.py           # Django management script
├── requirements.txt    # Python dependencies
└── README.md
```

## 🛠️ Getting Started (Backend)

### 1. Set Up Virtual Environment
```bash
python3 -m venv .venv
source .venv/bin/activate
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run Migrations
```bash
python manage.py migrate
```

### 4. Start Development Server
```bash
python manage.py runserver
```
The API server will run at `http://127.0.0.1:8000/`.

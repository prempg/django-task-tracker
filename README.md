# Full-Stack Task Tracker Web Application (Django)
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/dddd53e4-c7f4-40c7-a81e-f29cb3891cec" />

A lightweight, robust web application built using Python, Django, and Bootstrap 5. The application implements complete CRUD operations backed by an SQLite relational database and integrates with the Django Admin portal for administrative monitoring.

---

## Features
- **CRUD Operations**: Create, view, mark complete/incomplete (toggle), and delete tasks.
- **Priority Categorization**: Color-coded badges for High, Medium, and Low priority workflows.
- **Django Admin Dashboard**: Role-based administration with custom list views, search fields, and filtering.
- **MVT Architecture**: Strict separation of concerns across Models, Views, and Templates.
- **Responsive UI**: Clean Bootstrap 5 styling with CSRF-protected forms.

---

## Architecture Overview
- **Framework**: Django 
- **Language**: Python 
- **Database**: SQLite3
- **Frontend**: HTML5, Bootstrap 5, Django Template Engine

---

## Setup & Local Installation

1. **Activate Virtual Environment**:
   ```powershell
   .\myevnv\Scripts\Activate.ps1

Navigate to the Project:
cd premapp

Apply Database Migrations:
python manage.py migrate

Start Development Server:
python manage.py runserver

Access Application:
Web App UI: http://127.0.0.1:8000/
Admin Panel: http://127.0.0.1:8000/admin/

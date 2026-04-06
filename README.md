# Finance Backend API (Django)

## 🚀 Overview
This project is a backend system for managing financial records with role-based access control.

## 🧠 Features
- User management with roles (Admin, Analyst, Viewer)
- Financial record CRUD operations
- Summary API (income, expenses, net balance)
- Role-based access control
- SQLite database

## 🔗 API Endpoints

### Users
POST /users/

### Records
POST /records/ (Admin only)  
GET /records/all/  
DELETE /records/<id>/

### Summary
GET /summary/

## 🛠 Tech Stack
- Django
- Django REST Framework
- SQLite

## ▶️ Run Locally
```bash
python manage.py runserver
# Job Application Tracker

A simple and practical full-stack web application built using **React (Frontend)** and **Django REST Framework (Backend)** to help users track their job applications.

This project was developed as part of a **Full-Stack Developer Internship Assignment** to demonstrate core full-stack concepts such as CRUD operations, REST APIs, and frontend-backend integration.

---

## 🚀 Features

- Add a job application (Company Name & Job Title)
- View all job applications in a list
- Edit an existing job application
- Delete a job application
- Persistent data storage using SQLite
- RESTful backend API
- Simple and clean user interface

---

## 🛠 Tech Stack

### Frontend
- React (Vite)
- JavaScript
- Axios

### Backend
- Python
- Django
- Django REST Framework
- SQLite
- django-cors-headers

### Tools
- VS Code
- Git & GitHub
- Postman

---

## 📁 Project Structure

job-application-tracker/
│
├── backend/
│ ├── manage.py
│ ├── backend/
│ │ ├── settings.py
│ │ ├── urls.py
│ │ └── init.py
│ │
│ ├── applications/
│ │ ├── models.py
│ │ ├── serializers.py
│ │ ├── views.py
│ │ ├── urls.py
│ │ └── migrations/
│ │
│ └── requirements.txt
│
├── frontend/
│ ├── package.json
│ └── src/
│ ├── api.js
│ ├── App.jsx
│ ├── main.jsx
│ └── components/
│ ├── ApplicationForm.jsx
│ └── ApplicationList.jsx
│
└── README.md

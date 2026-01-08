# Job Application Tracker

A full-stack web application built using **React (Frontend)** and **Django REST Framework (Backend)** that helps users track and manage their job applications efficiently.

This project was developed as part of a **Full-Stack Developer Internship Assignment** to demonstrate practical skills in frontend-backend integration, REST APIs, and CRUD operations.

---

## 🚀 Features

- Add new job applications
- View all saved applications
- Update application status (Applied / Interview / Offer / Rejected)
- Delete job applications
- Persistent data storage using SQLite
- RESTful API architecture
- Clean separation between frontend and backend

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
│ │ ├── init.py
│ │ ├── settings.py
│ │ ├── urls.py
│ │ └── wsgi.py
│ │
│ ├── applications/
│ │ ├── init.py
│ │ ├── admin.py
│ │ ├── apps.py
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
│ ├── vite.config.js
│ └── src/
│ ├── api.js
│ ├── App.jsx
│ ├── main.jsx
│ └── components/
│ ├── ApplicationForm.jsx
│ └── ApplicationList.jsx
│
└── README.md

# ✅ Task Manager API

A beginner-friendly RESTful API for managing personal tasks, built with **Django** and **Django REST Framework**. This project is ideal for learning CRUD operations, JWT authentication, and API development fundamentals.

---

## 🚀 Features

- **User Authentication**: Register and log in using JWT tokens.
- **Task Management**: Create, read, update, and delete tasks.
- **User-Specific Tasks**: Each user can manage their own tasks.
- **Task Filtering**: Filter tasks based on completion status.
- **API Documentation**: Interactive API docs with Swagger or Postman.

---

## 🛠️ Tech Stack

- **Backend**: Django, Django REST Framework
- **Database**: SQLite (default) or PostgreSQL
- **Authentication**: JWT via `djangorestframework-simplejwt`
- **API Documentation**: Swagger or Postman

---

## 🔐 API Endpoints

### Authentication

- `POST /api/register/` – Register a new user
- `POST /api/token/` – Obtain JWT access and refresh tokens
- `POST /api/token/refresh/` – Refresh JWT access token

### Tasks

- `GET /api/tasks/` – List all tasks for the authenticated user
- `POST /api/tasks/` – Create a new task
- `GET /api/tasks/<id>/` – Retrieve a specific task
- `PUT /api/tasks/<id>/` – Update a specific task
- `DELETE /api/tasks/<id>/` – Delete a specific task

---

## 🧪 Installation & Setup

1. **Clone the repository**:

   ```bash
   git clone https://github.com/yourusername/task-manager-api.git
   cd task-manager-api

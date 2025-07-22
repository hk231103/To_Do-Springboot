# 📝 To-Do List REST API

A simple Spring Boot-based To-Do List application that provides a RESTful API for creating, retrieving, updating, and deleting tasks.

---

## 🚀 Features

- Add new tasks
- Get all tasks
- Update task details
- Delete tasks
- Bulk task insertion (optional endpoint)
- Tested with Postman
- In-memory H2 Database

---

## 🛠️ Tech Stack

- **Java**
- **Spring Boot**
- **Spring Data JPA**
- **H2 Database**
- **RESTful API**
- **Postman** for API testing

---


yaml


---

## 📦 API Endpoints

| Method | Endpoint                 | Description              |
|--------|--------------------------|--------------------------|
| GET    | `/api/tasks`             | Get all tasks            |
| POST   | `/api/tasks`             | Create a new task        |
| PUT    | `/api/tasks/{id}`        | Update an existing task  |
| DELETE | `/api/tasks/{id}`        | Delete a task by ID      |
| POST   | `/api/tasks/bulk`        | Add multiple tasks (bulk)|

---

## 🔄 Sample JSON (POST Request)

### Add a Single Task
```json
{
  "title": "Learn Spring Boot"
}


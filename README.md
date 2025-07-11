# 📚 Book Management System

A RESTful backend service built in **Golang** for managing books with full CRUD functionality. This project demonstrates clean architecture, routing using Gin, and database integration using GORM.

---

## 🚀 Features

- 📘 Create, Read, Update, Delete (CRUD) operations on books  
- 🛡️ Input validation and error handling  
- ⚙️ Modular code structure with separation of concerns  
- 🗂️ Uses `.env` for environment-based config  
- Built with **Gin**, **GORM**, and **Go modules**

---

## 🛠️ Tech Stack

| Layer         | Technology     |
|---------------|----------------|
| Language      | Golang         |
| Web Framework | Gin            |
| ORM           | GORM           |
| Database      | PostgreSQL     |
| Config        | `.env` file    |

---

## 📂 Project Structure

```bash
book_management_system/
├── cmd/                 # Main entry point
├── config/              # Database configuration
├── controllers/         # Request handlers (controllers)
├── models/              # GORM models for DB
├── routes/              # API route definitions
├── services/            # Business logic
├── go.mod / go.sum      # Dependencies
└── README.md            # Project documentation

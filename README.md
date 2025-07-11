# 📚 Book Management System

[![Go Version](https://img.shields.io/badge/Go-1.20-blue.svg)](https://golang.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/Anajoshi14/book_management_system/pulls)
[![Made with Go](https://img.shields.io/badge/Made%20with-Go-00ADD8?logo=go)](https://golang.org/)

> A RESTful Golang backend to manage books using Gin and PostgreSQL.

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

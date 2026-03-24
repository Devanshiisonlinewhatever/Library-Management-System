# Library-Management-System
Library Management System using Python and MySQL
# 📚 Library Management System (Python + MySQL)

## 🚀 Project Overview

The Library Management System is a Python-based application integrated with MySQL that helps manage library operations efficiently.
It allows users to add, issue, return, and track books while maintaining a structured database.

---

## 🛠️ Tech Stack

* 🐍 Python
* 🗄️ MySQL
* 🔌 MySQL Connector (mysql-connector-python)

---

## 🎯 Features

* 📖 Add new books to the library
* 🔍 Search books by title/author
* 📤 Issue books to users
* 📥 Return books
* 📊 Track available and issued books
* 🗑️ Delete book records
* 🔐 Database-driven storage for reliability

---

## 🧱 Database Schema

### 📘 Books Table

* book_id (Primary Key)
* title
* author
* quantity

### 👤 Users Table

* user_id (Primary Key)
* name

### 🔄 Transactions Table

* transaction_id (Primary Key)
* user_id (Foreign Key)
* book_id (Foreign Key)
* issue_date
* return_date

---

## 🧮 Key Functionalities

* Establish connection between Python and MySQL
* Perform CRUD operations using SQL queries
* Maintain relational integrity using foreign keys
* Handle real-time updates for book availability

---

## ▶️ How to Run

1. Install dependencies

```bash id="a1b2c3"
pip install mysql-connector-python
```

2. Set up MySQL database

```sql id="d4e5f6"
CREATE DATABASE library_db;
```

3. Update database credentials in Python file

4. Run the application

```bash id="g7h8i9"
python main.py
```

---

## 📂 Project Structure

* `main.py` → Main application logic
* `db_config.py` → Database connection setup
* `queries.sql` → SQL queries
* `README.md` → Project documentation

---

## 💡 Key Learnings

* Integrated Python with MySQL database
* Implemented CRUD operations
* Designed relational database schema
* Improved problem-solving and backend logic

---

## 🚀 Future Enhancements

* 🌐 Add GUI (Tkinter / Web App)
* 🔐 User authentication system
* 📊 Dashboard for analytics
* 📱 Convert to web-based system using Flask/Django

---

## 📌 Conclusion

This project demonstrates how Python and MySQL can be combined to build a functional and scalable database-driven application.


---

⭐ If you like this project, don’t forget to star the repo!

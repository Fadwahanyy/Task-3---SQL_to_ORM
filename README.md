# Task-3---SQL_to_ORM
# LMS ORM Project

## Overview
This project implements an **Object-Relational Mapping (ORM)** system for a Learning Management System (LMS) using **Python** and **SQLAlchemy**.  
It includes database models, CRUD operations, and seed data scripts for students, instructors, courses, and enrollments.

---

## Features
- **SQLAlchemy ORM models** for Students, Instructors, Courses, Enrollments, and Grades.
- **CRUD functions** in a dedicated `crud.py` module:
  - Add a new student
  - Enroll a student in a course
  - Assign a grade
  - Get all students in a course
  - Get all courses for an instructor
- **Database connection management** in `db.py` using environment variables.
- **Idempotent seeding** in `insert_data.py` to prevent duplicate test data.
- `.env` file support for storing DB credentials securely.
- Example usage in `main.py`.

```
Lms_Orm/
│── crud.py          # CRUD functions
│── db.py            # Database connection setup
│── insert_data.py   # Script to seed data into the database
│── main.py          # Main script to demonstrate ORM usage
│── models.py        # SQLAlchemy models
│── .env             # Environment variables (not uploaded to GitHub)
│── __pycache__/     # Compiled Python files
```

Technologies Used
Python 3

SQLAlchemy ORM

PostgreSQL

Psycopg2

python-dotenv


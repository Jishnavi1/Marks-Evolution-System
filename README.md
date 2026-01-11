# Student Result Management System

A desktop-based application developed using Python, Tkinter, and MySQL to store and retrieve student semester results.

---

# 📌 Overview

This system consists of two modules:

- Student Database Module – Used by admin/faculty to enter student marks and store results in a MySQL database.

- Student Result Viewer Module – Used by students to view their semester results using their Hall Ticket Number (HTNO).

- The application automates result calculation, grading, and result retrieval.

---

# 🛠 Technologies Used

- Python 3

- Tkinter (GUI)

- MySQL

- mysql-connector-python

---

# 🚀 Features

- GUI-based student result system

- Stores student marks in MySQL database

- Automatic calculation of total, average, and grade

- Result classification (Distinction, First Class, Pass, Fail)

- Fetch and display results using HTNO

- Simple and user-friendly interface

---

# 📂 Project Structure
student_result_system/
├── studentdatabase.py     # Admin module (insert student results)
├── studentresult.py       # Student module (view results)
└── README.md

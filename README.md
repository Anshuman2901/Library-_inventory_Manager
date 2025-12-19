📚 Library Inventory Manager

Mini Project Assignment – Programming for Problem Solving using Python
Assignment Title: Object-Oriented Design and Robust Programming in a Library Management System
Assignment Type: Individual
Duration: 12–15 hours
Weightage: 5 Marks



---

📘 Project Overview

Campus libraries often manage hundreds or thousands of books. This project aims to build a command-line based Library Inventory Manager using Object-Oriented Programming (OOP) and robust file handling.
The application allows library staff to:

Add books

Issue books

Return books

Search inventory

View all books

Persist data in JSON format

Maintain logs and handle errors gracefully


This project demonstrates modular design, OOP, JSON file persistence, logging, and a menu-driven CLI.


---

🎯 Learning Objectives

By completing this project, you will:

Understand class-based design with attributes and methods

Apply OOP concepts like encapsulation, magic methods, and structured classes

Use JSON + pathlib for file persistence

Write modular, reusable Python code

Implement robust exception handling and logging

Create a clean project structure with packages and CLI

(Bonus) Write unit tests



---

📂 Folder Structure (as required)

library-inventory-manager-yourname/
│
├── README.md
├── requirements.txt
├── .gitignore
│
├── catalog.json               # Auto-created at runtime
│
├── library_manager/
│   ├── __init__.py
│   ├── book.py
│   ├── inventory.py
│
├── cli/
│   └── main.py
│
└── tests/
    └── test_inventory.py


---

🧩 Task Breakdown (Mapped to Your Assignment)

Task 1 — Book Class

Implemented in: library_manager/book.py

Includes:

title, author, isbn, status

__init__(), __str__(), to_dict()

issue(), return_book(), is_available()



---

Task 2 — LibraryInventory Manager

Implemented in: library_manager/inventory.py

Features:

Add book

Search by title

Search by ISBN

Display all books

Load existing catalog

Save updates automatically



---

Task 3 — JSON File Persistence

Uses json + pathlib.Path

Loads catalog.json safely

Handles missing/corrupt files via try/except



---

Task 4 — Menu-Driven CLI

Implemented in: cli/main.py

Options:

1. Add Book
2. Issue Book
3. Return Book
4. Search Book
5. View All Books
6. Exit

Input validation + clean formatting included.


---

Task 5 — Exception Handling & Logging

All file operations inside try–except

Logging using:

INFO for normal operations

ERROR for invalid operations



Log file auto-created:

library.log


---

Task 6 — Packaging

This project follows Python package structure with separate modules.

Bonus: Test file provided optionally.


---
▶️ How to Run

Step 1 — Navigate to the main project folder

cd library-inventory-manager

Step 2 — Run using Python module execution

python -m cli.main

(Required because the CLI imports from the package.)


---

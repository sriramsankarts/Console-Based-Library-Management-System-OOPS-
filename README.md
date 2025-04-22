📚 Library Management System (Console-Based) - C++

📖 Description

This project is a console-based Library Management System developed using C++ and the principles of Object-Oriented Programming (OOP). It stimulates the core functionalities of a real-world library, where users can add, issue, return, and view books.

The project is built for educational purposes and showcases the use of encapsulation, inheritance, polymorphism, and file handling in C++. The system supports two types of users: **Admins** and **Students**, each with their own capabilities.

🧑‍💻 Tech Stack

Language:** C++
IDE:** Code::Blocks / VS Code / Dev C++
Concepts Used:** Classes & Objects, Inheritance, Polymorphism, File I/O
Compiler:** g++ / MinGW / GCC

🎯 Objectives

Demonstrate OOP concepts using a practical scenario
Practice file handling and user-defined data structures
Simulate user roles and book transactions in a digital environment

⚙️ Features

👨‍🏫 Admin Panel:
- Add new books to the system
- Delete books by ID
- Update book details (title, author, availability)
- View all books in the library
- Save changes to a persistent file

🎓 Student Panel:
- View available books
- Search books by title or author
- Issue a book (if available)
- Return a previously issued book
- View their issued book list

🧱 Project Structure

```bash
LibraryManagementSystem/
│
├── src/
│   ├── main.cpp           # Entry point of the application
│   ├── Book.h / Book.cpp  # Book class definition and implementation
│   ├── User.h             # Base class for Admin and Student
│   ├── Admin.cpp          # Admin functionalities
│   ├── Student.cpp        # Student functionalities
│   ├── Library.cpp        # Manages the list of books and file handling
│
├── data/
│   └── books.txt          # File for persistent book storage
│
├── README.md              # Project documentation
└── LICENSE                # Optional: MIT License or any other

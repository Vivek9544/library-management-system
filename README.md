# library-management-system
A console-based library management system written in C++ style using file handling. Supports book issuing, student records, and more.

# 📚 Library Management System (Turbo C++)

This is a console-based **Library Management System** written in **C++ (Turbo C++ style)**. It uses **binary file handling** to manage records of books and students, and provides options for issuing and returning books, with a simple text-based interface.

---

## 🧩 Features

- 📖 Add, view, modify, and delete **book records**
- 👨‍🎓 Add, view, modify, and delete **student records**
- 📕 Issue books to students
- 📗 Return books and calculate late fines
- 🔍 Search for specific book or student
- 📋 View complete lists of books and students
- 🧑‍💼 Administrator-only menu for secure actions

---

## 🛠️ Technologies Used

| Tool/Library       | Purpose                         |
|--------------------|----------------------------------|
| C++ (Turbo style)   | Core programming language       |
| `<fstream.h>`       | File handling with binary files |
| `<conio.h>`         | Console UI and effects          |
| `<iostream.h>`      | Input/Output operations         |
| Turbo C++ / DOSBox  | IDE / Emulator for execution    |

## 📁 File Structure

LibraryManagementSystem/
├── book.h # Book class and functions
├── student.h # Student class and functions
├── main.cpp # Main program and menus
├── *.dat # Binary data files created at runtime
└── README.md # Project documentation (this file)

# 🎓 Student Management System Using Python

A **console-based Student Management System** developed using Python and Object-Oriented Programming (OOP). This project helps manage student records efficiently through a simple menu-driven interface.

## 📌 Features

- **Add Student** – Register students with a unique roll number, name, and marks.
- **Display Students** – View all student records.
- **Search Student** – Find student details using a roll number.
- **Update Student** – Modify student names and marks.
- **Delete Student** – Remove student records.
- **Calculate Average Marks** – Calculate the average marks of all students.
- **Save Records** – Store student details in a text file.
- **Load Records** – Automatically load previously saved records when the program starts.
- **Input Validation** – Check duplicate roll numbers and validate marks between 0 and 100.

## 🛠️ Technologies Used

- **Language:** Python 3
- **Programming Paradigm:** Object-Oriented Programming (OOP)
- **Modules:** `abc` (Abstract Base Classes)
- **Storage:** Text File (`student.txt`)
- **Interface:** Command-Line Interface (CLI)

## 🧠 OOP Concepts Implemented

| Concept | Implementation |
|---|---|
| Abstraction | Abstract class `Students` and abstract method `student_section()` |
| Encapsulation | Private attributes `__Name`, `__Roll_No`, and `__Marks` |
| Inheritance | `Section` class inherits from `Students` |
| Polymorphism | `Section` provides its own implementation of `student_section()` |

## 📂 Project Structure

```text
Student-Management-System/
│
├── student_management.py
├── student.txt
└── README.md
```

**Note:** `student.txt` is generated automatically when records are saved.

## ⚙️ Installation and Execution

**1. Clone the repository**

```bash
git clone https://github.com/USERNAME/Student-Management-System.git
```

**2. Navigate to the project folder**

```bash
cd Student-Management-System
```

**3. Run the program**

```bash
python student_management.py
```

Replace `USERNAME` with your GitHub username.

No external Python packages are required.

## 💻 Program Menu

```text
====Student Management System====

1. Add Student
2. Display Students
3. Search Student
4. Update Student
5. Delete Student
6. Calculate Average
7. Save Records
8. Exit

Enter your choice:
```

## 📝 Example Student Record

```text
Roll_No: 101
Name: Rahul
Marks: 85.0
```

### Saved File Format

Student records are stored in `student.txt` in the following format:

```text
101,Rahul,85.0
102,Priya,92.0
103,Aman,78.0
```

Each line contains:

`Roll_Number,Name,Marks`

## 🔄 How It Works

1. The application starts and loads previously saved records from `student.txt`, if available.
2. The user selects an operation from the menu.
3. The system performs the requested operation.
4. Student records are maintained as objects in a Python list.
5. The user can save records manually using option 7.
6. When the user selects option 8, the application saves the records and exits.

## 📚 Python Concepts Practiced

- Classes and Objects
- Abstract Base Classes
- Inheritance and Polymorphism
- Encapsulation using private attributes
- Getter and Setter Methods
- Lists and Loops
- Conditional Statements
- Exception Handling (`try`, `except`)
- File Handling (`open`, `read`, `write`)
- CRUD Operations

## 🚀 Future Enhancements

- Add SQLite or MySQL database support.
- Develop a GUI using Tkinter.
- Add student attendance tracking.
- Generate student report cards.
- Export student records to CSV.
- Improve input validation and error handling.

## 🎯 Project Objective

The objective of this project is to strengthen Python programming skills by building a practical student record management application using OOP principles, data structures, and file handling.

## ⭐ Support

If you find this project helpful, consider giving the repository a star!

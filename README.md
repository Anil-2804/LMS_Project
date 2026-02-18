# Libary Management system(LMS)

## 📌 Overview

Library Management System (LMS) is a simple Python-based software to manage **Books, Students, Teachers, and Admins** in a library. It allows three types of users to interact with the system:

* **Admin** 
* **Teacher** 
* **Student** 

The system provides basic functionalities like login, role-based access, and session control.

---

## ⚙️ Features

### 1. Admin

* Login with username & password.
* Access admin-specific options.
* Can add new Admins.
* Can add Students.
* Can add Teachers.
* Can add Books.
* Can Update Students.
* Can Update Teachers.
* Can Update Books.
* Can Delete Students.
* Can Delete Teachers.
* Can Delete Books.
* Ability to log out.

### 2. Teacher

* Login with teacher credentials.
* View Books
* Take Books
* Return Books
* Ability to log out.

### 3. Student

* Login with student credentials.
* View Books
* Take Books
* Return Books
* Ability to log out.

### 4. General

* Secure login system.
* Option to **turn off** the program.
* After logout, users are redirected back to the login menu.

---

## 🖥️ How It Works

1. Run the program:

   ```bash
   python main.py
   ```

2. You will see the **welcome screen**:

   ```
   ========================================
   Welcome to LMS
   ========================================

   Who are you? Select any one below:

   1. ADMIN
   2. STUDENT
   3. TEACHER
   4. TURN OFF
   ```

3. Based on your choice:

   * **Admin →** Enter admin username & password.
   * **Teacher →** Enter teacher username & password.
   * **Student →** Enter student username & password.
   * **Turn Off →** Exits the program.

4. After successful login, you can perform role-based actions. Example:

   ```
   ****** ADMIN LOGIN IS SUCCESSFUL ******
   ```

5. Choosing **Logout** returns you back to the login menu instead of shutting down the program.

---

## 📂 Project Structure

```
└── 📁LMS
    └── 📁assests
        ├── __init__.py
        ├── data.py                # Stores LMS data in memory
    └── 📁commons
        ├── __init__.py
        ├── login.py                # Handles login logic for Admin/Student/Teacher
    └── 📁utils
        ├── admin_utils.py          # Handles Admin-related actions
        ├── book_utils.py           # (Future) Handle book operations
        ├── display_utils.py        # Handles displaying menus and collecting user input
        ├── student_utils.py        # Handles adding Students and Teachers
    ├── config.py                   # Holds constant values (DEPTS, YEARS, SEMS)
    ├── main.py                     # Entry point for running LMS
    ├── README.md                   # Project documentation
    └── requirement.txt             # Python dependencies (if any)
```

---

## 📝 Requirements

* Python 3.13.5

Run the program with:

```bash
python main.py
```

---

## Flow chart

* [https://lmsflowchart.netlify.app/](https://lmsflowchart.netlify.app/)

## 👨‍💻 Author

* Developed by **ANIL kUMAR BALU** ✨

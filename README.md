# AS/400 COBOL Employee Management System

## 📌 Project Overview
This project is an enterprise-level **Employee Management System** developed on **IBM AS/400 (IBM i)** using **COBOL, DB2, and DDS**.  
The application follows a **menu-driven green-screen architecture** and supports complete CRUD operations with validations and subfile-based data display.

The project reflects real-time AS/400 backend development practices used in enterprise and BFSI environments.

---

## 🛠️ Technologies Used
- COBOL
- IBM AS/400 (IBM i)
- DB2
- DDS (Physical File, Logical File, Display File)

---

## 📋 Application Features
- Menu-driven navigation
- Add Employee
- Update Employee
- Delete Employee
- View Employee Details
- Subfile listing with paging
- Proper validation & confirmation messages

---

## 🖥️ Screen Flow & Screenshots

### 🔹 Main Menu Screen
The main menu allows users to select different operations like Add, Update, Delete, View, and Exit.

![Main Menu](/IMG/main%20menu.png)

---

### 🔹 Add Employee Screen
This screen is used to add new employee records into the DB2 physical file.

![Add Screen](/IMG/add%20scr.png)

---

### 🔹 Update Employee Screen
Used to modify existing employee details. The system validates record existence before allowing updates.

![Update Screen](/IMG/upd%20scr.png)

![Update Notification](/IMG/update%20notifi.png)

---

### 🔹 Delete Employee Screen
Allows deletion of employee records with proper confirmation messages to prevent accidental deletion.

![Delete Menu](/IMG/delete%20mm.png)

![Delete Screen](/IMG/delete%20scr.png)

![Delete Notification](/IMG/delete%20notifi.png)

---

### 🔹 View / Detail Screen
Displays employee details based on employee ID input.

![Detail Screen](/IMG/detail%20scr.png)

![Detail View](/IMG/detail.png)

---

### 🔹 Subfile Display Screen
Subfile is used to display multiple employee records with paging functionality for easy navigation.

![Subfile Screen 1](/IMG/subfile.png)

![Subfile Screen 2](/IMG/subfile%201.png)

![Subfile Screen 3](/IMG/subfile2.png)

---

## ✅ Validations Implemented
The application includes robust validations to ensure data integrity:

- Mandatory field validation
- Numeric and alphabet-only checks
- Action code validation in menu
- Record existence validation
- Confirmation messages for update and delete actions

![Menu Validation](/IMG/valid%20mm.png)

![Action Validation](/IMG/validation%20of%20action%205.png)

---

## 📂 Source Code
COBOL source code is provided in `.txt` format for reference and understanding:
- Add Program
- Update Program
- Delete Program
- Detail/View Program
- Menu Program
- Subfile Program

---

## 🎯 Key Learning Outcomes
- Enterprise COBOL program structure
- Screen handling using DDS
- Subfile implementation with paging
- DB2 file operations on AS/400
- Validation and error-handling techniques
- Real-world AS/400 application workflow

---

⭐ **This project demonstrates hands-on experience in AS/400 backend development using COBOL and DDS.**

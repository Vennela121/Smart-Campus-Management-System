# Smart Campus Management System

## 📌 Project Overview

The Smart Campus Management System is a Java and MySQL-based application designed to simplify and automate various campus administrative activities. The system provides a centralized platform for managing students, faculty, attendance, events, complaints, and user authentication.

This project aims to reduce manual paperwork, improve data management, and enhance communication within educational institutions through a user-friendly interface and efficient database operations.

---

## 🎯 Objectives

* Automate campus management activities.
* Maintain student and faculty records efficiently.
* Track attendance digitally.
* Manage campus events and announcements.
* Handle student complaints systematically.
* Provide secure login and authentication.
* Improve data accuracy and accessibility.

---

## ✨ Features

### 🔐 User Authentication

* Secure login system
* Username and password validation
* Role-based access control

### 👨‍🎓 Student Management

* Add student records
* View student details
* Update student information
* Delete student records

### 👨‍🏫 Faculty Management

* Add faculty details
* View faculty information
* Update faculty records
* Manage faculty database

### 📅 Attendance Management

* Record student attendance
* View attendance records
* Maintain attendance history

### 🎉 Event Management

* Create campus events
* View event details
* Manage event schedules

### 📝 Complaint Management

* Register complaints
* Track complaint status
* Manage complaint records

### 🗄️ Database Management

* Store and retrieve data using MySQL
* JDBC-based database connectivity
* Efficient data handling

---

## 🛠️ Technologies Used

### Programming Language

* Java

### Database

* MySQL

### Connectivity

* JDBC (Java Database Connectivity)

### Development Tools

* Visual Studio Code (VS Code)
* Git
* GitHub

### Database Driver

* MySQL Connector/J

---

## 📂 Project Structure

```text
Smart-Campus-Management-System/
│
├── MainMenu.java
├── Login.java
├── DBConnection.java
├── StudentManagement.java
├── FacultyManagement.java
├── AttendanceManagement.java
├── EventManagement.java
├── ComplaintManagement.java
├── README.md
└── .gitignore
```

## 🗃️ Database Configuration

### Database Name

```sql
smart_campus
```

### Sample Database Connection

```java
String url = "jdbc:mysql://localhost:3306/smart_campus";
String username = "root";
String password = "your_password";
```

---

## 🚀 Installation and Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/Vennela121/Smart-Campus-Management-System.git
```

### Step 2: Open the Project

Open the project folder using VS Code or any Java IDE.

### Step 3: Configure MySQL

* Install MySQL Server.
* Create the required database.
* Update database credentials in `DBConnection.java`.

### Step 4: Add MySQL JDBC Driver

Download MySQL Connector/J and place the JAR file in the project directory.

### Step 5: Compile the Project

```bash
javac *.java
```

### Step 6: Run the Application

```bash
java MainMenu
```

---

## 📸 Future Enhancements

* Graphical User Interface (GUI)
* Student Portal
* Faculty Portal
* Online Attendance System
* Event Registration System
* Email Notifications
* Report Generation
* Dashboard Analytics
* Cloud Database Integration
* Mobile Application Support

---

## 📚 Learning Outcomes

Through this project, the following concepts were implemented and practiced:

* Object-Oriented Programming (OOP)
* Java Programming
* JDBC Connectivity
* MySQL Database Management
* CRUD Operations
* Exception Handling
* Git and GitHub Version Control
* Software Development Best Practices

---

## 👩‍💻 Author

**Vennela Gajula**

B.Tech Computer Science and Engineering

GitHub: https://github.com/Vennela121

---

## 📄 License

This project is developed for educational and learning purposes.

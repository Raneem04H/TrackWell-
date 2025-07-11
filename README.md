#  TrackWell 

**TrackWell** is a Java-based desktop application designed to help users manage and monitor their physical activities. Developed as an OOP project, the application features a user-friendly GUI, basic tracking and registration capabilities, and uses **JDBC** to connect to a **MySQL** database for storing user information, activities, and other data. 

---

## 📌 Key Features

- 🖥️ User-friendly Java Swing GUI  
- 🔄 Real-time synchronization with SQL database using JDBC  
- 🔔 Automated health notifications  
- 🧩 Modular OOP-based architecture  
- 🔐 Login, Registration, Admin, and User Dashboard interfaces  

---

## 💾 Technologies

- Java (Swing)  
- JDBC (SQL Database)  
- Object-Oriented Programming (OOP)  

---

## 📂 Project Structure

TrackWell-Health-Tracker/
│
├── src/
│ ├── GUI/ # Graphical User Interface (GUI) classes
│ │ ├── AdminDashBoard.java # Admin dashboard
│ │ ├── Dashboard.java # User dashboard
│ │ ├── LoginFrame.java # Login interface
│ │ ├── RegistrationFrame.java # Registration interface
│ │ └── WelcomePage.java # Welcome / Start page
│ │
│ ├── model/ # Data models for the application
│ │ ├── Activity.java
│ │ ├── Admin.java
│ │ ├── Cycling.java
│ │ ├── Notification.java
│ │ ├── Payment.java
│ │ ├── Report.java
│ │ ├── Running.java
│ │ ├── Swimming.java
│ │ ├── Trainee.java
│ │ ├── User.java
│ │ ├── Yoga.java
│ │ └── WeightTraining.java
│ │
│ ├── Database/ # Database connection and queries
│ │ └── DBConnection.java
│ │
│ └── Main/ # Main class to run the application
│ └── TrackWell.java
│
├── resources/ # Application resources (images, icons, etc.)
│ ├── logo.png
│ └── logo1.png
│
├── Database/ # SQL scripts for database setup
│ └── database.sql
│
├── README.md # Project documentation (this file)




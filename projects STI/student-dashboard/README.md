# 🎓 Student Dev Dashboard

A full-stack, database-driven web application designed to help student developers track daily study hours, log programming tasks, and monitor learning progress with live statistical updates.

---

## 📌 Overview

Because GitHub Pages hosts static assets only, **this project requires a local PHP server engine and a MySQL database (such as XAMPP) to execute**. 

To test and run this project live on your machine, follow the setup instructions below to download the repository and import the database schema into your local environment (`localhost`).

---

## ✨ Features

- **Task & Time Logging:** Record project topics alongside exact hours spent.
- **Dynamic Stats Calculation:** Real-time database queries automatically aggregate total completed tasks and cumulative study hours.
- **Asynchronous Data Handling:** Uses JavaScript's `Fetch API` for dynamic UI updates without requiring page reloads.
- **Relational Database Storage:** Powered by MySQL with clean table schemas and structured queries.

---

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6 / Fetch API)
- **Backend:** PHP 8.x
- **Database:** MySQL / MariaDB
- **Local Server Environment:** XAMPP (Apache + MySQL) / VS Code

---

## 🗄️ Database Schema & File Overview

```text
student-dashboard/
├── index.php             # Main UI dashboard layout
├── api.php               # Server-side PHP script (Database connection & CRUD operations)
├── app.js                # Frontend JavaScript logic (Fetch requests & DOM updates)
├── style.css             # App styling & responsive layout
├── student_dashboard.sql # Database schema dump for localhost import
└── README.md             # Project documentation

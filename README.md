# 🎓 Student Management System

A full-stack database-driven web application designed to manage student records efficiently. This system allows users to perform CRUD operations such as adding, updating, viewing, and deleting student data through a clean and intuitive interface.

---

## 🚀 Tech Stack

* **Backend:** Node.js, Express.js
* **Database:** MySQL
* **Frontend:** HTML, CSS, JavaScript

---

## ✨ Features

* 📌 Add new student records
* 📌 View all students in a structured format
* 📌 Update existing student details
* 📌 Delete student records
* 📌 RESTful API integration with MySQL
* 📌 Clean and normalized database schema

---

## 🧱 Project Structure

```
student-management-system/
│── backend/
│   ├── config/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   └── server.js
│
│── frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
│── database/
│   └── schema.sql
│
│── README.md
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/student-management-system.git
cd student-management-system
```

### 2️⃣ Setup Backend

```bash
cd backend
npm install
```

### 3️⃣ Configure Environment Variables

Create a `.env` file:

```
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=student_db
PORT=5000
```

### 4️⃣ Setup Database

Run the SQL file:

```sql
CREATE DATABASE student_db;
USE student_db;

CREATE TABLE students (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(100),
    email VARCHAR(100),
    phone VARCHAR(15),
    course VARCHAR(100),
    created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

### 5️⃣ Run Backend Server

```bash
npm start
```

---

## 🔌 API Endpoints

| Method | Endpoint      | Description        |
| ------ | ------------- | ------------------ |
| GET    | /students     | Fetch all students |
| GET    | /students/:id | Fetch one student  |
| POST   | /students     | Add student        |
| PUT    | /students/:id | Update student     |
| DELETE | /students/:id | Delete student     |

---

## 💡 Future Improvements

* 🔐 Authentication & Authorization
* 🔍 Search & filtering
* 📄 Pagination
* 🌐 Deployment on cloud
* 📊 Dashboard analytics

---

## 🤝 Contributing

Contributions are welcome! Feel free to fork this repo and submit a pull request.

---

## 📬 Contact

If you have any questions or suggestions, feel free to reach out.

---

⭐ If you found this project helpful, consider giving it a star!

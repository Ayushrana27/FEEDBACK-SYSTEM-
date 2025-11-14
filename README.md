# 📘 Faculty Feedback System
A modern, user-friendly, secure **Faculty Feedback Management System** built using **PHP, XML Storage, and Chart.js analytics**.  
Students submit feedback, faculty view insights, and admins access full analytics.

---

## 🚀 Features

### ✔ Student Panel
- Student login  
- Submit feedback  
- Give rating (1–5)  
- Write comments  
- Stored as **XML files**  

### ✔ Faculty Panel
- Faculty login  
- View total feedback  
- Average rating  
- All comments + student details  

### ✔ Admin Panel
- Admin login  
- View all feedback records  
- Faculty-wise average rating  
- Course-wise analytics  
- **Top performing faculty** auto-detection  
- Chart.js graphs  
- Comments grouped by faculty  

---

## 📊 Tech Stack

| Component | Technology |
|----------|------------|
| Frontend | HTML, CSS, JS |
| Backend | PHP |
| Storage | XML files |
| Charts | Chart.js |
| Server | XAMPP (Apache) |

---


│── login.php
│── authenticate.php
│── feedback_form.php
│── faculty_dashboard.php
│── admin_reports.php
│── logout.php
│── style.css
│── README.md
│
├── xml_data/
│ └── *.xml (auto-generated)
│
└── assets/
└── images, logos (optional)




---

## 🔐 Default Login Credentials

| Role    | Username | Password |
|---------|----------|----------|
| Admin   | admin    | 123      |
| Faculty | faculty  | 123      |
| Student | student  | 123      |

*(Modify inside `authenticate.php`)*  

---

## 🛠️ How to Run

### 1️⃣ Start XAMPP  
Enable:
- Apache  
*(MySQL not needed — uses XML)*

### 2️⃣ Move Project Folder  
Copy into:





### 4️⃣ Login  
Use any of the default credentials.

---

## 📈 Admin Dashboard Includes
- Faculty rating chart  
- Course-wise rating chart  
- Feedback summary cards  
- Table analytics  
- Comment grouping  

---

## 🧩 Future Enhancements
- Migrate XML → MySQL  
- Email verification  
- Online deployment  
- PDF report generation  
- Student-specific analytics  

---

## ⭐ Support
If this project helped you, give a **⭐ Star** on GitHub!



## 📁 Project Structure


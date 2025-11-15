# 💬 **ChatApp — Real-Time PHP Chat Application**

<p align="center">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</p>

<p align="center">
  A lightweight real-time chat system built with <strong>PHP + MySQL + AJAX</strong>.
<br>
Designed for simplicity, learning, and fast real-time message updates.
</p>

---

## ✨ **Features**

✔️ Real-time message fetching (polling every 1s)  
✔️ User-friendly and modern interface  
✔️ Timestamps for each message  
✔️ Mobile-responsive layout  
✔️ Sound alerts on new messages  

---

## 🧩 **Tech Stack**

| Layer | Technologies |
|-------|--------------|
| **Frontend** | HTML, CSS, JavaScript (AJAX) |
| **Backend** | PHP (Procedural) |
| **Database** | MySQL / MySQLi |
| **Server** | XAMPP / Apache / Nginx |

---

## 🛠 **Installation Guide**

### **1️⃣ Clone the project**
```bash
git clone https://github.com/yourname/chatapp.git
2️⃣ Configure your database

Edit db.php with your DB credentials.

3️⃣ Create the chat table
<div style="backgroundbackground-color: tomato;">
CREATE TABLE chat (
    id INT AUTO_INCREMENT PRIMARY KEY,
    name VARCHAR(255) NOT NULL,
    msg TEXT NOT NULL,
    date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
</div>
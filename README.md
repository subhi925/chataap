# ChatApp

A simple real-time chat application built with **PHP** and **MySQL**.

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## Language
Primary language: **PHP** (server-side files: .php)

## Features
- Real-time message updates
- Message display with timestamps
- Simple UI and sound notification

## Requirements
- PHP 7.0+
- MySQL / MySQLi
- XAMPP or similar local server

## Installation
1. Place project in your web server folder (e.g. D:\xampp\htdocs\chatapp)
2. Configure DB in `db.php`
3. Create `chat` table:
```sql
CREATE TABLE chat (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255) NOT NULL,
  msg TEXT NOT NULL,
  date TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```
4. Open: http://localhost/chatapp/

## Files
- index.php — chat UI
- chat.php — loads messages (AJAX)
- db.php — DB connection
- style.css — styles

## Contact
- Email: subhihamed88@gmail.com  
- LinkedIn: https://linkedin.com/in/subhi-mouhammed-hamed-223410360  
- Portfolio: http://subhimyportfolio.ct.ws/index.html

## Security
Use prepared statements, validate input, and avoid storing credentials in source code.

License: MIT
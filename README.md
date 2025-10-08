# 💼 PHPLedger

A simple yet powerful **Double Entry Accounting System** built using **PHP**, **MySQL**, **HTML**, **CSS**, **JavaScript**, **jQuery**, and **Bootstrap**.  

Developed by **Sutlej Solutions**, this project aims to streamline everyday accounting needs with simplicity and reliability.

> ⚠️ *PHPLedger is open-source and free to use. However, no free support or customization help is provided.*

---

## 🌟 Features

- 🧾 **Double Entry Accounting System** — Manage accurate debits and credits.  
- 👥 **Account Management** — Easily manage Assets, Liabilities, Income, and Expenses.  
- 💰 **Transaction Recording** — Record, edit, and balance transactions efficiently.  
- 📊 **Ledger & Reports** — Generate account summaries and financial reports.  
- 🖥️ **Web-Based UI** — Clean and responsive interface built with Bootstrap & jQuery.  
- ⚙️ **Lightweight & Fast** — Works seamlessly on any PHP + MySQL environment.  
- 🔒 **Database-Driven** — Secure data management with MySQL schema.  

---

## 🧠 Tech Stack

| Component | Technology |
|------------|-------------|
| **Backend** | PHP 8+ |
| **Database** | MySQL |
| **Frontend** | HTML5, CSS3, Bootstrap, jQuery |
| **Version Control** | Git / GitHub |

---

## ⚙️ Installation Guide

Follow these steps to install and run **PHPLedger** locally.

---

### 🟩 Step 0 — Install Git

Download and install Git from:  
👉 [https://git-scm.com/downloads](https://git-scm.com/downloads)

---

### 🟦 Step 1 — Clone the Repository

```bash
git clone https://github.com/rmak78/phpledger.git
cd phpledger



If Composer is not installed, download it from:
👉 https://getcomposer.org/download/

🟧 Step 2 — Set Up Local Server

Install a local PHP environment such as XAMPP, Laragon, or WAMP.

Start Apache and MySQL services.

Ensure PHP version is 8.0 or above.

👉 Download XAMPP: https://www.apachefriends.org/download.html

🟥 Step 4 — Create Database

Open phpMyAdmin (usually at http://localhost/phpmyadmin
)

Click New → Create a database (e.g., phpledger_db)

Import the SQL file:

/database/phpledger.sql

🟦 Step 5 — Configure Database Connection

Open the config.php or .env file in your project directory and update with your local credentials:

$servername = "localhost";
$username   = "root";
$password   = "";
$dbname     = "phpledger_db";


Save the file after updating your details.

🟨 Step 6 — Folder Setup (For XAMPP or Laragon)

Move or copy your project folder to your server’s web directory:

For XAMPP → C:\xampp\htdocs\phpledger

For Laragon → C:\laragon\www\phpledger

🟧 Step 7 — Launch the Application

Open your browser and visit:

👉 http://localhost/phpledger

🟩 Step 8 — Default Login Credentials

If demo credentials are provided, try:

Username: admin
Password: admin123


⚠️ Make sure to change your password immediately after login for security reasons.

Submit a Pull Request 🚀

🧑‍💻 Developed By

BixiSoft Solutions Pvt ltd
🌐 http://www.phpledger.com

📜 License

This project is licensed under the MIT License — free to use and modify.
However, no free support or customization assistance will be provided.


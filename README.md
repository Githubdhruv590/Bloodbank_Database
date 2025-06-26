🩸 Blood Bank Database Management System
A mini project simulating the core operations of a blood bank, including donor and patient management, blood donation tracking, inventory monitoring, and request handling. This system includes both:

💾 A robust backend built using Oracle SQL and PL/SQL

🌐 A simple HTML/CSS/JavaScript frontend for visualization and interaction
📂 Project Structure## 🧨 LifelineDB - A Blood Bank Management System

**Oracle SQL + JS + HTML + CSS**

A **Blood Bank Management System** that enables users to register donors and patients, record blood donations, request blood units, track inventory, and view reward points — all powered by **Oracle SQL procedures**, with a **dynamic HTML/CSS/JavaScript frontend**.

> ⚙️ *Built for academic, demonstration, and DBMS lab purposes (mini-projects).*

---

### ✨ Key Features

* ✅ Register new **donors** and **patients**
* 🧪 Record **blood donations** with volume and blood group
* 🧨 Request **blood units** and auto-update inventory
* 📄 View **donors**, **requests**, and **inventory summaries**
* 🏅 Implement **donor rewards system** with points
* 🔍 **Find donors** by blood group
* 🧠 PL/SQL-powered logic (procedures, cursors, sequences)

---

### 🗂️ Technologies Used

| Tech                      | Purpose                      |
| ------------------------- | ---------------------------- |
| Oracle SQL                | Database schema & logic      |
| PL/SQL                    | Stored procedures & triggers |
| HTML/CSS                  | Frontend UI                  |
| JavaScript                | Form handling, validation    |
| SQL Developer             | DB interface                 |

---

### 📸 Screenshots

#### 🔘 1. Main Dashboard UI

Shows navigation menu and real-time feedback from user actions.
![Dashboard](screenshots/dashboard.png)

#### ➕ 2. Donor Registration Form

User-friendly form to register new donors with blood group, last donation, and contact info.
![Donor Form](screenshots/register_donor.png)

#### 🧾 3. View Inventory Summary

Dynamically fetches inventory status by blood group using stored procedures.
![Inventory](screenshots/inventory_summary.png)

#### 🏱 4. Donor Reward History

Displays donor rewards fetched using procedure `show_rewards`.
![Rewards](screenshots/donor_rewards.png)

> 📁 Store screenshots in a folder named `screenshots/` in the project root.

---

### 🛠️ Setup Instructions

1. **Oracle Setup**

   * Install Oracle XE / use SQL Developer
   * Run the `project file.sql` to create tables, sequences, and procedures

2. **Frontend Setup**

   * All HTML/CSS/JS files are already included
   * Open `index.html` in a browser to start

> ❗ PHP is not included in this version. Backend functionality is simulated using frontend JS and SQL procedures manually executed.

---

### 📁 Folder Structure

```
Bloodbank_Database/
├── index.html
├── styles.css
├── script.js
├── project file.sql
├── ER.drawio.png
├── screenshots/
│   ├── dashboard.png
│   ├── register_donor.png
│   ├── inventory_summary.png
│   ├── donor_rewards.png
└── README.md
```

---

### 📌 Future Enhancements

* Add backend support using PHP or Node.js
* Create real-time donor search with AJAX
* Add user login & authentication system
* Include graphical analytics using Chart.js

---

### 📜 License

This project is created for **educational use only**.
Feel free to fork, modify, and use it for your **DBMS lab**, **mini-project**, or as a learning reference.

pgsql
Copy
Edit
blood-bank-dbms/
│
├── frontend/
│   ├── index.html
│   ├── styles.css
│   └── script.js
│
├── backend/
│   ├── tables.sql
│   ├── procedures.sql
│   ├── sample_data.sql
│   └── menu_script.sql
│
└── README.md
💻 Features
Frontend
Clean and responsive interface using HTML/CSS

Dropdown menu to select actions (Insert Donor, Request Blood, Show Donors, etc.)

Basic interaction via JavaScript for triggering database procedures (demo-based)

Backend
✅ Donor and patient insertion procedures

✅ Donation and blood request tracking

✅ Automatic reward point updates

✅ Inventory summaries

✅ Cursor-based reporting (showing donors, patients, requests, etc.)

🔧 Technologies Used
Frontend: HTML, CSS, JavaScript

Backend: Oracle SQL, PL/SQL (Procedures, Sequences, Cursors)

Tools: SQL Developer / Oracle Live SQL

📸 Screenshots


📑 Key PL/SQL Procedures
insert_donor: Adds a new donor to the database

add_donation: Records a donation and updates inventory & rewards

request_blood: Deducts inventory based on patient request

show_donors: Uses cursor to list all donors

find_donors_by_blood_group: Filters donors by blood type

📘 How to Run

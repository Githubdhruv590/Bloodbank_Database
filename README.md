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

Shows navigation menu.
![image](https://github.com/user-attachments/assets/6d0b299f-d281-4561-8400-168d24ded9e6)



#### ➕ 2. Insert Donor

User-friendly form to register new donors with blood group, last donation, and contact info.
![image](https://github.com/user-attachments/assets/66b69808-1126-4902-b533-f9710313253e)


#### 🧾 3. View Inventory Summary

Dynamically fetches inventory status by blood group using stored procedures.
![Inventory](screenshots/inventory_summary.png)

#### 🏱 4. Donor Reward History

Displays donor rewards fetched using procedure `show_rewards`.
![Rewards](screenshots/donor_rewards.png)



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


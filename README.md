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
![image](https://github.com/user-attachments/assets/7f2980cd-2af3-42a8-9573-fb74cf98467c)

#### ➕ 2. Insert Donor
User-friendly form to register new donors with blood group, last donation, and contact info.
![image](https://github.com/user-attachments/assets/1b44cb06-75c3-4e04-bbd6-2715032b85af)

#### 🧾 3. Insert Patient
![image](https://github.com/user-attachments/assets/5d240493-9ddb-44c5-ba0d-ec97e9cc8566)

#### 🧾 4. Add Donation
![image](https://github.com/user-attachments/assets/59d3c2b9-dbff-473d-a487-c3e8ae8e99a9)

#### 🧾 5. Request Blood
![image](https://github.com/user-attachments/assets/8b2fce99-4dbd-46f1-8440-8a35af932d38)

#### 🧾 6. Show Donors
![image](https://github.com/user-attachments/assets/a29c2b5a-7695-466f-84c2-5c23948a3c29)

#### 🏱 7. Show Patients by Hospital
![image](https://github.com/user-attachments/assets/23f939b5-6314-41bb-9439-64acd321660b)

#### 🏱 8. Show Inventory Summary
![image](https://github.com/user-attachments/assets/591e5bae-4873-424d-b22f-469ff610966f)

#### 🏱 9. Show All Requests
![image](https://github.com/user-attachments/assets/2a2de579-07b4-4713-aad2-952eb60fddcd)

#### 🏱 10. Show Donor Reward History
![image](https://github.com/user-attachments/assets/259886e0-13b2-4dbf-b286-14bb3f4f4d59)

#### 🏱 11. Find Donor by Blood Request
![image](https://github.com/user-attachments/assets/1ba16518-15f5-42b8-bc09-10493f738b33)


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


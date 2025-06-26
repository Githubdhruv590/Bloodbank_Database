🩸 Blood Bank Database Management System
A mini project simulating the core operations of a blood bank, including donor and patient management, blood donation tracking, inventory monitoring, and request handling. This system includes both:

💾 A robust backend built using Oracle SQL and PL/SQL

🌐 A simple HTML/CSS/JavaScript frontend for visualization and interaction
📂 Project Structure
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

# Batch-GPA-Dashboard

#  Batch GPA Dashboard – DBMS Project

This is a full-stack web application that displays **semester-wise average GPAs** for student batches from **1952 to 1971**. Built using **Node.js**, **Express**, **PostgreSQL**, and **Alpine.js**, the app allows users to filter GPA data by **year** and **semester**, or view **all historical data**.

---

##  Features

-  Select batch year and semester to view average GPA and student count.
-  Fetch all batch GPA records between 1952–1971.
-  Secure PostgreSQL connection with `.env` support (e.g., NeonDB).
-  GPA calculated using combined marks from theory and coursework (`marks`, `cmarks`, `dist`, `cdist` tables).

---

##  Project Structure
project/
│
├── main.js # Entry point (Express server)
├── db.js # PostgreSQL DB connection
├── route/
│ └── routes.js # Route handling logic (GET /batch-gpa)
│
├── public/
│ ├── index.html # Frontend (Alpine.js)
│ ├── app.js # Frontend logic for UI interaction
│ └── styles (optional) # Add if you modularize CSS
│
├── .env # DB credentials (not committed)
├── package.json
└── README.md

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/batch-gpa-dashboard.git
cd batch-gpa-dashboard
2. Install Dependencies
npm install



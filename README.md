
 💼 SQL Task 2 – Employee Data Insertion & NULL Handling

📌 Objective
To demonstrate understanding of SQL DML operations like `INSERT`, `UPDATE`, `DELETE`, and `SELECT` with a focus on handling `NULL` values, default constraints, and realistic business data.


 🛠 Tools Used
- SQLiteStudio (Local SQL environment)
- SQL (SQLite dialect)

 🧱 Table Structure

CREATE TABLE employees (
    id INTEGER PRIMARY KEY,
    name TEXT NOT NULL,
    email TEXT,
    salary REAL DEFAULT 30000,
    department TEXT
);

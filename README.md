# MySQL Database Operations with Python (`airportdb`)

A Python project demonstrating how to connect to a MySQL server using `mysql-connector-python` to automate database creation, schema modeling, and core SQL CRUD operations.

---

## Features

* **Connection Handling:** Safe local MySQL server connection setup using structured `try-except` error handling.
* **Database & Schema Creation:** Automates the creation of the `airportdb` database and the structured `airport` table with primary key constraints.
* **Data Insertion:** Executes SQL batch inserts to populate relational records.
* **Data Fetching:** Reads and iterates over table rows using cursor execution and `fetchall()`.
* **Data Deletion & State Updates:** Performs targeted row deletion by primary key and commits transactional changes to MySQL.

---



---

## Prerequisites

* **Python 3.8+**
* **MySQL Server** (running locally on `127.0.0.1:3306` or a remote host)

---
bash
git clone [https://github.com/your-username/mysql-python-airportdb.git](https://github.com/your-username/mysql-python-airportdb.git)
cd mysql-python-airportdb

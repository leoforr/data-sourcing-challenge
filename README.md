# Retrieve Data from MySQL Database

This project connects to a MySQL database and retrieves data from a specified table using Python. The notebook demonstrates how to establish a secure connection, execute SQL queries, and load the results into a pandas DataFrame for further analysis.

---

## Purpose

- Connect to a MySQL database using Python
- Retrieve and inspect table contents
- Convert query results into a pandas DataFrame for analysis

---

## Tools & Libraries

- Python 3
- pymysql – MySQL database connector
- sqlalchemy – SQL toolkit and ORM
- pandas – Data analysis and manipulation

---

## How It Works

1. **Database Connection**
   - Uses SQLAlchemy and pymysql to establish a connection
   - Requires the following credentials:
     - Username
     - Password
     - Host
     - Database name

2. **Query Execution**
   - A SQL query is passed to retrieve records from a specific table
   - Data is loaded into a pandas DataFrame

3. **Data Output**
   - The first few rows of the retrieved table are displayed
   - Ideal for quick inspection or pre-processing before deeper analysis

---

## How to Run

1. Install required libraries:
   ```bash
   pip install pandas sqlalchemy pymysql

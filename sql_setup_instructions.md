# SQL Environment Setup Instructions

Follow these steps to prepare your local SQL environment before starting the course.

## 1. Install a Database Server
- Download and install **PostgreSQL** or **MySQL** for your operating system.
- During installation, note the superuser credentials and default port.

## 2. Create the Course Database
```sql
CREATE DATABASE sql_ds;
```
- Connect using your database client (psql, mysql, DBeaver, pgAdmin, etc.).
- Run the command above to create the `sql_ds` database.

## 3. Import the Superstore Dataset
1. Place `datasets/raw/superstore.csv` in an accessible directory for the database server.
2. Create a destination table matching the CSV columns.
3. Execute the `COPY` command (PostgreSQL example):
```sql
COPY superstore
FROM '/path/to/superstore.csv'
WITH (FORMAT csv, HEADER true);
```
- For MySQL, use `LOAD DATA INFILE` with the appropriate syntax.

## 4. Verify the Import
```sql
SELECT COUNT(*) FROM superstore;
```
- Confirm the returned row count matches the number of records in the CSV.

## 5. Next Steps
- Repeat the import process for other datasets as needed.
- Update connection strings in notebooks or BI tools to point to `sql_ds`.

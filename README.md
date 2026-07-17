# SQL Transaction Analysis Project

## Project Overview

This project demonstrates how SQL can be used to analyze customer transaction data and answer common business questions. The project simulates a banking environment where transaction records are queried to identify spending trends, summarize transaction activity, and generate business insights.

The analysis was completed using SQL and focuses on skills commonly used by Fraud Analysts, AML/KYC Analysts, Risk Analysts, Compliance Analysts, and Operations Analysts.

---

## Project Objectives

- Analyze customer transaction data using SQL
- Practice writing SQL queries to answer business questions
- Summarize transaction activity and customer spending
- Demonstrate core SQL skills used in analyst roles

---

## Tools Used

- SQL
- DB Fiddle (or SQLite Online)
- Microsoft Excel (for creating the sample dataset)

---

## Dataset

### Customers Table

| Column | Description |
|---------|-------------|
| customer_id | Unique customer identifier |
| customer_name | Customer's full name |
| state | Customer's state |

### Transactions Table

| Column | Description |
|---------|-------------|
| transaction_id | Unique transaction identifier |
| customer_id | Customer making the transaction |
| transaction_date | Date of transaction |
| amount | Transaction amount (USD) |

---

## Business Questions

This project answers the following questions:

1. Show all transactions.
2. Show transactions greater than $1,000.
3. Count the total number of transactions.
4. Calculate the total transaction volume.
5. Calculate the average transaction amount.
6. Find total transaction volume by state.
7. Identify the top customers by total spending.
8. Count transactions for each customer.
9. Identify customers with multiple transactions.

---

## SQL Skills Demonstrated

- SELECT
- WHERE
- ORDER BY
- COUNT
- SUM
- AVG
- GROUP BY
- HAVING
- INNER JOIN

---

## Project Files

```
sql-transaction-analysis/
│
├── README.md
├── transaction_analysis.sql
├── customers.csv
├── transactions.csv
└── images/
```

---

## Sample Analysis

Example Question:

**Which state processed the highest transaction volume?**

The SQL query groups transactions by state and calculates the total amount processed in each state.

Example Question:

**Who are the highest-spending customers?**

The SQL query groups transactions by customer and calculates total spending to identify the top customers.

---

## Skills Developed

- Data Analysis
- SQL Query Writing
- Business Reporting
- Transaction Analysis
- Financial Data Analysis
- Problem Solving

---

## Future Improvements

Future enhancements to this project may include:

- Adding customer risk scores
- Detecting potentially suspicious transactions
- Building a SQL fraud monitoring project
- Creating an Excel dashboard from SQL query results

---

## Author

Christopher Walden

Aspiring Fraud Analyst | Risk Analyst | Compliance Analyst | Operations Analyst

# Credit Card Financial Dashboard

Power BI dashboards for credit card customers and transactions, with the SQL used to build the underlying database.

## What is included

| File | Purpose |
| --- | --- |
| `Credit Card Financial Dashboard-Customer.pdf` | Customer dashboard |
| `Credit Card Financial Dashboard-Transaction.pdf` | Transaction dashboard |
| `Credit Card Financial Weekly Dashboard Report.pdf` | Weekly report |
| `SQL Query - Financial Dashboard Data.sql` | Creates the `ccdb` database and loads the four CSVs |
| `credit_card.csv`, `cc_add.csv` | Card and transaction data (10,108 rows in `credit_card.csv`) |
| `customer.csv`, `cust_add.csv` | Customer data (10,108 rows in `customer.csv`) |

## Fields covered

Card category, annual fees, 30-day activation, customer acquisition cost, credit limit, revolving balance, transaction amount and count, utilization ratio, chip use, expense type, and weekly, quarterly and yearly periods.

## Run it

1. Run `SQL Query - Financial Dashboard Data.sql` in MySQL to create and load the database
2. Connect Power BI to the database

## Stack

Power BI, SQL (MySQL)

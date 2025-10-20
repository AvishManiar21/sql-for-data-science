# Datasets Overview

This folder stores all data assets used throughout the SQL for Data Science course.

## Structure
- `raw/`: Original files downloaded from source systems.
- `processed/`: Cleaned or transformed outputs ready for analysis.

## Sources
- `superstore.csv`: Kaggle Superstore Sales dataset.
- `chinook.sql`: Chinook sample database schema and seed data.
- `online_retail.xlsx`: UCI Online Retail II workbook with multiple sheets (by year).
- `online_retail.csv`: CSV export produced from the primary sheet for easier loading.
- `marketing_campaign.csv`: UCI Bank Marketing campaign outcomes.
- `olist_ecommerce/`: Kaggle Olist Brazilian E-Commerce tables split into CSVs (orders, order_items, customers, products, payments, reviews, geolocation).
- `pizza_sales.csv`: Maven Analytics Pizza Sales dataset.

## Loading Guidelines
1. Inspect each file to understand schema and encoding.
2. Create staging tables in the `sql_ds` database.
3. Use `COPY`, `LOAD DATA`, or client import tools to populate tables.
4. Document any transformations in the `processed/` directory.

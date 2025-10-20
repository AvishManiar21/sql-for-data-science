# Datasets Overview

This folder stores all data assets used throughout the SQL for Data Science course.

## Structure
- `raw/`: Original files downloaded from source systems.
- `processed/`: Cleaned or transformed outputs ready for analysis.

## Sources
- `superstore.csv`: Kaggle Superstore Sales dataset.
- `chinook.sql`: Chinook sample database schema and seed data.
- `online_retail.csv`: UCI Online Retail II transactional data.
- `marketing_campaign.csv`: UCI Bank Marketing campaign outcomes.
- `olist_ecommerce.csv`: Kaggle Olist Brazilian E-Commerce data.
- `pizza_sales.csv`: Maven Analytics Pizza Sales dataset.

## Loading Guidelines
1. Inspect each file to understand schema and encoding.
2. Create staging tables in the `sql_ds` database.
3. Use `COPY`, `LOAD DATA`, or client import tools to populate tables.
4. Document any transformations in the `processed/` directory.

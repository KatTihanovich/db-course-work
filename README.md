# DB Course Work – Garden Centre

This is an academic database course project that models and implements a data system for a small business called **Garden Centre**.

The project includes both OLTP and OLAP database layers, data loading pipelines, and analytical structure design.

---

## Project Description

Garden Centre is a small shop in London that sells indoor plants, trees, seeds, gardening tools, soil, and fertilizers. It also provides gardening equipment rental services.

The main goal of this project is to design and implement a full database system that supports transactional operations (OLTP) and analytical processing (OLAP).

---

## Architecture

The project consists of two main parts:

### OLTP Database
- Customer management
- Product catalog (products, categories, suppliers)
- Orders and order details
- Rentals and rental details
- Business logic functions (data validation, calculations)

### OLAP Database (Data Warehouse)
- Dimensional model (DimCustomer, DimProduct, DimDate, etc.)
- Fact tables (FactSales, FactRental)
- Optimized for analytical queries and reporting

---

## Technologies

- PostgreSQL
- SQL / PLpgSQL
- PostgreSQL FDW (Foreign Data Wrapper)
- Power BI (for visualization)
- CSV data import

---

## Features

- Full relational schema design (OLTP)
- Data validation and preprocessing functions
- Automated CSV data loading
- ETL process from OLTP to OLAP
- Star schema data warehouse design
- Analytical data model for reporting

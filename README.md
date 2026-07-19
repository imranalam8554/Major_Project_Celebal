# RetailMart Data Engineering Project

## Overview

This project implements a centralized data engineering pipeline for RetailMart using **PySpark** and **Spark SQL** following the **Medallion Architecture (Bronze, Silver, and Gold)**.

The pipeline transforms raw retail transaction data into clean, analytics-ready datasets that support customer analytics, business reporting, and decision-making.

---

## Project Objectives

- Build a centralized analytics platform using PySpark.
- Implement the Medallion Architecture (Bronze, Silver, and Gold).
- Clean and standardize raw retail datasets.
- Create a unified Customer 360 view.
- Implement Slowly Changing Dimension (SCD Type 2).
- Generate business-ready analytical datasets using Spark SQL.

---

## Technologies Used

- Python
- Apache Spark (PySpark)
- Spark SQL
- Pandas
- Parquet
- Jupyter Notebook

---

## Project Workflow

```
Raw CSV Files
       │
       ▼
Bronze Layer
       │
       ▼
Silver Layer
       │
       ▼
Spark SQL Views
       │
       ▼
Customer 360
       │
       ▼
Gold Layer
       │
       ▼
Business Insights
```

---

## Features

- Data Ingestion
- Data Cleaning and Standardization
- Bronze, Silver, and Gold Layers
- Spark SQL Analytics
- Customer 360
- Slowly Changing Dimension (SCD Type 2)
- Customer Segmentation
- Product Ranking using Window Functions
- Business-Ready Gold Tables

---

## Gold Layer Outputs

- Customer 360
- Monthly Revenue
- Trending Products
- Customer Segments
- Payment Summary
- Product Ranking

---

## Repository Contents

```
RetailMart-Data-Engineering/

├── RetailMart_Data_Engineering.ipynb
├── README.md
└── requirements.txt
```

---

## Dataset

This project uses the RetailMart datasets provided as part of the assignment.

If the datasets are not included in this repository, place the following CSV files inside a `data/` directory before running the notebook:

- raw_customers_dataset.csv
- raw_orders_dataset.csv
- raw_products_dataset.csv
- raw_items_dataset.csv
- raw_payments_dataset.csv

---

## Installation

Install the required Python packages:

```bash
pip install -r requirements.txt
```

---

## Running the Project

1. Place the RetailMart CSV datasets inside the `data/` directory.
2. Launch Jupyter Notebook.
3. Open `RetailMart_Data_Engineering.ipynb`.
4. Run all cells sequentially.

---

## Author

**Imran Alam**

B.Tech in Information Technology

SKIT Jaipur

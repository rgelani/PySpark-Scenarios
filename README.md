# PySpark Real-Life Scenarios

This repository contains practical examples of using PySpark in real-world scenarios. Each example demonstrates how PySpark can be applied to solve common data engineering and analytics challenges efficiently.

## Scenarios

### 1. Incremental Upsert for Product Catalog Updates
A retail company receives daily updates to its product catalog, including new items, price changes, and discontinued products. Instead of replacing the entire catalog or simply adding new records, they need to upsert the incoming data. This means updating existing products with the latest information and inserting new ones so the catalog stays accurate and up to date in real time.

### 2. Incremental Data Load from Azure Data Lake
A retail company receives daily sales transaction files from multiple store locations in an Azure Data Lake folder. Instead of reprocessing all historical data every day, Spark Structured Streaming is used to incrementally load only the new files into a Delta table. This ensures analytics dashboards are updated in near real-time while optimizing compute costs and processing time.

## How to Use
- Clone this repository.
- Explore the individual scenario notebooks/scripts.
- Run them in your PySpark environment to see real-world use cases in action.


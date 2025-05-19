# Health Data Modeling Project

This project demonstrates how to model healthcare data using PySpark and Delta Lake, following a star schema for data warehousing.

## 🔧 Technologies Used
- PySpark
- Delta Lake
- Apache Spark
- Databricks (or local Spark setup)
- Git & GitHub

## 📁 Project Structure
- `health_data_modeling.ipynb`: PySpark code with detailed transformations
- `health_data.csv`: Sample healthcare dataset
- `scripts/`: Optional .py script version of notebook

## 📊 Data Model
- Patient Dimension
- Date Dimension
- Fact Table with health metrics (BP, Glucose, BMI)

## 📌 Transformations Performed
- Parsing blood pressure column
- Date formatting and enrichment
- Creating dimension tables
- Constructing fact table
- Saving as Delta Lake format

## 📦 Output
Delta tables stored in `/delta/` format.

---

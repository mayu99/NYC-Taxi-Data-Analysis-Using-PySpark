# 🗽 NYC Taxi Data Analysis Using PySpark

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mayu99/NYC-Taxi-Data-Analysis-Using-PySpark/blob/main/nyc_taxi_analysis.ipynb)

---

## 📌 Project Overview

This project leverages **PySpark**, a Python API for Apache Spark, to analyze large-scale **New York City Taxi trip datasets**. The goal is to uncover insights into urban mobility, identify ride trends, and enable data-driven decisions for optimizing transportation infrastructure in NYC.

By using PySpark's distributed data processing capabilities, we ensure scalability and performance for handling millions of records efficiently.

---

## 🎯 Objectives

- Load and process large NYC taxi trip datasets using PySpark
- Analyze spatial and temporal trip patterns
- Identify peak pickup/drop-off times and locations
- Derive insights into trip duration, passenger count, and fare amount
- Visualize trends for better interpretation (optional)

---

## 🧰 Tools & Technologies

| Tool          | Purpose                                    |
|---------------|--------------------------------------------|
| **Apache Spark (PySpark)** | Distributed data processing             |
| **Python**     | Data manipulation and scripting            |
| **Google Colab** | Cloud-based development and experimentation |
| **Git & GitHub** | Version control and collaboration         |
| **Jupyter Notebook** | Analysis and visualization (if local)   |
| **Pandas / Matplotlib / Seaborn** |  Data wrangling & plots  |

---

## 📂 Dataset Information

We used the official **NYC Yellow Taxi Trip Data**, available from the NYC Taxi and Limousine Commission (TLC):

- ✅ Source: [https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- ✅ Format: CSV
- ✅ Size: 13 M record
- ✅ Sample Columns:
  - `pickup_datetime`, `dropoff_datetime`
  - `pickup_longitude`, `pickup_latitude`
  - `dropoff_longitude`, `dropoff_latitude`
  - `passenger_count`, `trip_distance`
  - `fare_amount`, `payment_type`

---

## 🔍 Key Analysis Tasks

- Cleaning and filtering records (nulls, invalid coordinates)
- Parsing datetime fields to extract hour/day/month
- Aggregating trips by time and location
- Calculating average fare, distance, and trip duration
- Analyzing frequency of pickup and drop-off zones
- Visualizing trends and anomalies



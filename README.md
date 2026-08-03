# NYC Taxi Trip Analytics using Apache Spark

## Big Data Analytics (DS-313) – Assignment #3

### Student Information

* **Name:** Muhammad Safyan Ramzan
* **Roll Number:** 221980025
* **Course:** Big Data Analytics (DS-313)
* **Instructor:** Zuhaib Hussain Butt
* **University:** GIFT University

---

# Project Overview

This project analyzes the **NYC Yellow Taxi Trip Records (January 2025)** using **Apache Spark** running in **Local Mode** with **Docker** and **PySpark**. The objective is to perform large-scale data analysis, data cleaning, Spark transformations, Spark SQL queries, window functions, and performance optimization on a real-world Big Data dataset.

---

# Technologies Used

* Ubuntu 24.04 LTS
* Docker
* Apache Spark
* PySpark
* Python 3
* Jupyter Notebook
* Spark SQL

---

# Dataset

**Dataset:** NYC Yellow Taxi Trip Records (January 2025)

The dataset contains millions of taxi trip records, including:

* Pickup and drop-off timestamps
* Passenger count
* Trip distance
* Fare amount
* Payment type
* Pickup and drop-off location IDs
* Total trip amount

---

# Project Structure

```text
RollNo_Name/

│── notebook.ipynb
│── README.md
│── report.pdf
│── execution_log.txt
│
├── screenshots/
│   ├── schema.png
│   ├── jobs.png
│   ├── stages.png
│   ├── storage.png
│   └── executors.png
│
├── output/
│   ├── query1.csv
│   ├── query2.csv
│   └── query3.csv
│
└── data/
    └── yellow_tripdata_2025-01.parquet
```

---

# Assignment Tasks Completed

Environment Setup

* Configured Docker environment
* Started Apache Spark Local Mode
* Connected Jupyter Notebook

---

Dataset Loading

* Loaded January 2025 NYC Taxi dataset
* Displayed schema
* Counted records
* Displayed first 20 rows

---

Exploratory Data Analysis

Performed analysis including:

* Total trips
* Earliest trip
* Latest trip
* Unique vendors
* Average trip distance
* Average fare
* Maximum fare
* Minimum fare
* Average passenger count
* Payment methods

---

Data Cleaning

Performed:

* Duplicate removal
* Invalid trip distance removal
* Negative fare removal
* Missing value handling

---

Spark Transformations

Implemented:

* filter()
* select()
* withColumn()
* orderBy()
* drop()
* distinct()
* groupBy()
* alias()
* repartition()
* join()

---

Spark SQL

Executed multiple SQL queries including:

* Top longest trips
* Peak pickup hours
* Monthly revenue
* Average fare by payment type
* Trips over 20 miles
* Highest fare trips
* Vendor analysis
* Passenger analysis

---

Window Functions

Implemented:

* row_number()
* rank()
* dense_rank()

---

Performance Optimization

Applied:

* cache()
* repartition()
* explain()

Compared execution time before and after caching.

---

Spark UI Analysis

Captured screenshots of:

* Jobs
* Stages
* Storage
* Executors

---

# How to Run the Project

### 1. Clone Repository

```bash
git clone https://github.com/sufe01/221980025_SafyanRamzan_Spark_Assignment3
```

### 2. Navigate to Project

```bash
cd 221980025_SafyanRamzan_Spark_Assignment3
```

### 3. Start Docker Container

```bash
docker-compose up
```

### 4. Open Jupyter Notebook

Open the URL displayed in the terminal after the container starts.

### 5. Run Notebook

Execute all notebook cells in order.

---

# Learning Outcomes

Through this assignment, I gained practical experience with:

* Apache Spark
* Distributed data processing
* Spark SQL
* Window Functions
* Data Cleaning
* Performance Optimization
* Spark UI Analysis
* Docker-based Spark environment

---

# Author

**Name:** Muhammad Safyan Ramzan

**Roll Number:** 221980025

**Department:** Computer Science

**University:** GIFT University


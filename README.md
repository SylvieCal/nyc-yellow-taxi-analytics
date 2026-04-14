<<<<<<< HEAD
# 🚕 NYC Yellow Taxi Analytics Project

A complete data project built with NYC Yellow Taxi trip data using Python, SQL, PostgreSQL, Jupyter Notebook, and Power BI. This project takes raw parquet files, cleans and transforms the data, stores it in a structured database, and turns it into clear analysis and dashboards.

It was built to show practical skills in data cleaning, SQL analysis, database work, exploratory analysis, and dashboard development.

---

## Overview

This project follows the full workflow of a real data project, from raw trip records to data that is ready for analysis and reporting, using NYC TLC Yellow Taxi Trip Record Data.

The purpose of the project is to show the ability to work across multiple stages of the data process, including:

- loading raw data
- cleaning and validating records
- creating useful features for analysis
- storing curated data in PostgreSQL
- exploring trends in Jupyter Notebook
- building dashboards in Power BI

This project combines technical data work with business focused analysis.

---

## Data Source

This project uses NYC TLC Yellow Taxi Trip Record Data. The dataset includes trip level details such as pickup and dropoff dates and times, pickup and dropoff locations, trip distance, itemized fare details, rate type, payment type, and driver reported passenger count.

According to TLC, the data was collected and provided by authorized technology providers, and the agency does not guarantee its accuracy.

---

## Tools Used

| Category | Tools |
|---|---|
| Programming | Python 3.11 |
| Data Analysis | Pandas, NumPy, PyArrow |
| Database | PostgreSQL |
| Querying | SQL |
| Exploration | Jupyter Notebook |
| Visualization | Power BI, Matplotlib |
| Environment | Conda |
| Development | VS Code |

---

## Project Workflow

```text
Raw NYC Taxi Parquet Files
        ↓
Python Data Ingestion
        ↓
Data Cleaning and Transformation
        ↓
Processed Data
        ↓
PostgreSQL Database
        ↓
SQL and Jupyter Analysis
        ↓
Power BI Dashboard
```

---

## Project Structure

```text
nyc-taxi-platform/
│
├── data/
│   ├── raw/                       # Raw parquet files
│   └── processed/                 # Cleaned data outputs
│
├── notebooks/
│   └── exploration.ipynb          # Exploratory analysis and validation
│
├── src/
│   ├── ingest.py                  # Reads raw parquet data
│   ├── transform.py               # Cleans data and creates features
│   └── load.py                    # Loads data into PostgreSQL
│
├── sql/
│   └── analysis_queries.sql       # SQL queries for analysis
│
├── environment.yml
├── requirements.txt
├── .gitignore
└── README.md
```

---

## What This Project Does

### Data ingestion

Reads raw NYC Yellow Taxi parquet files into Python for processing.

### Data cleaning

Prepares the data for analysis by removing invalid records, handling missing values, and standardizing key fields.

### Feature creation

Creates new columns that make the data more useful for analysis, such as:

- trip duration
- pickup hour
- day of week
- fare per mile

### Data storage

Loads the cleaned data into PostgreSQL so it can be queried efficiently with SQL.

### Data analysis

Uses SQL and Jupyter Notebook to explore patterns in trip activity, revenue, and rider behavior.

### Dashboarding

Uses Power BI to create visual reports and highlight important metrics and trends.

---

## Example Questions This Project Can Answer

- What times of day have the highest taxi demand?
- Which days of the week generate the most trips?
- How does revenue change across different time periods?
- What is the relationship between trip distance and fare amount?
- What patterns appear in passenger and trip behavior?

---

## Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/SylvieCal/nyc-yellow-taxi-analytics.git
cd nyc-yellow-taxi-analytics
```

### 2. Set up the environment

Using Conda:

```bash
conda env create -f environment.yml
conda activate nyc-env
```

Or with pip:

```bash
pip install -r requirements.txt
```

### 3. Download the raw data

Download NYC Yellow Taxi parquet files from the NYC TLC Trip Record Data site (https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page) and place them in: 

```text
data/raw/
```

### 4. Configure PostgreSQL

Create a local PostgreSQL database and update the connection string in `src/load.py`.

Example:

```python
DATABASE_URL = "postgresql://username:password@localhost:5432/nyc_taxi"
```

### 5. Run the scripts

```bash
python src/ingest.py
python src/transform.py
python src/load.py
```

---

## Project Outputs

This project produces:

- cleaned datasets in `data/processed/`
- PostgreSQL tables for SQL analysis
- Jupyter based analysis and validation
- Power BI dashboards for reporting

---

## Why This Project Matters

This project shows the ability to work with real world data from raw file ingestion to final reporting. It highlights skills that are important in both data analyst and junior data engineering roles, including:

- data cleaning
- SQL querying
- database loading
- exploratory analysis
- dashboard development
- communicating insights from data

---

## Future Improvements

- automate the workflow with Apache Airflow
- add data quality checks
- improve performance for larger datasets
- expand Power BI dashboards with more business metrics
- move storage to a cloud platform

---

## Author

**Sylvie Calvaire**  
Data Engineering and Analytics Portfolio
=======
# nyc-taxi-trip-analysis-dashboard
>>>>>>> 3a72c5fb12f362d3e533db0d38a8e71ba7fdbdb6

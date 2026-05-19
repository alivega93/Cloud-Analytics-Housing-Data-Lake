# Cloud Analytics & Housing Data Lake

End-to-end cloud analytics project focused on simulating a Data Lake workflow, processing housing data with Python, implementing ETL operations, storing transformed information in SQLite and generating business insights through SQL analysis and visualization.

---

## Business Problem

How can housing data be processed, stored and analyzed using a cloud-inspired analytics workflow to generate actionable insights about property prices, geographic distribution and housing characteristics?

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- SQLite
- SQL
- ETL
- Data Lake
- Cloud Analytics

---

## Project Architecture

Raw Data → Data Lake Structure → Python Processing → SQLite Storage → SQL Analysis → KPI Reporting & Visualization

This project simulates a simplified Cloud Analytics pipeline using local folders as a Data Lake environment for storing, processing and analyzing housing information.

---

## Methodology

### 1. Data Lake Setup

A simplified Data Lake structure was created using folders for *raw* and *processed* data to simulate cloud storage organization and analytical workflows.

### 2. Data Import & Preparation

The Housing dataset was imported using Python and Pandas. Data quality validation included:

- reviewing duplicates
- validating structure
- preparing the dataset for ETL processing

### 3. ETL Workflow

An ETL pipeline was implemented to:

- extract housing data
- transform variables and dataset structure
- load processed data into SQLite

This workflow created a structured analytical environment for downstream analysis.

### 4. Database Storage with SQLite

SQLite was used to store processed information and simulate a lightweight analytical database layer.

### 5. Business KPI Analysis

Key business indicators were calculated, including:

- Average property price
- Average living area
- Average number of bedrooms

### 6. SQL Analytics

SQL queries were developed to:

- analyze average prices by zipcode
- identify higher-value geographic areas
- compare housing characteristics across locations

### 7. Visualization

Visual analysis was performed using scatter plots to explore the relationship between:

- property price
- living area
- housing distribution patterns

---

## Key Insights

- Property prices vary considerably across zipcodes.
- Larger living areas tend to correlate with higher housing prices.
- SQL analysis revealed important geographic differences in property valuation.
- The Data Lake structure improved separation between raw and processed information.
- The project demonstrates a simplified Cloud Analytics and ETL workflow.

---

## Author

*Ali Vega*  
Data Analytics • Cloud Analytics

---

## Repository Structure

```text
cloud-analytics-housing-data-lake
├── README.md
├── notebooks
│   └── Cloud Analytics & Housing Data Lake.ipynb
└── report
    └── Cloud Analytics & Housing Data Lake.pdf
```

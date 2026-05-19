# Cloud Analytics & Housing Data Lake

Cloud analytics project focused on building a simple Data Lake structure, processing Housing data with Python, storing transformed data in SQLite and generating business insights through KPIs, SQL queries and visual analysis.

## Business Problem

How can housing data be processed, stored and analyzed using a simple cloud analytics workflow to generate useful insights about property prices, size and location?

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- SQLite
- SQL
- Data Lake
- ETL
- Cloud Analytics

## Project Overview

This project simulates a basic Data Lake architecture using local folders for raw and processed data. The workflow includes data ingestion, cleaning, transformation, database storage, KPI calculation, SQL querying and visualization.

## Methodology

### 1. Data Lake Setup

A simple Data Lake structure was created with folders for raw and processed data, simulating a cloud storage workflow.

### 2. Database Configuration

SQLite was used to create a local database for storing and processing the Housing dataset.

### 3. Data Import and Cleaning

The Housing dataset was imported using Python and Pandas. Duplicate records were reviewed and the dataset was prepared for analytical processing.

### 4. ETL Process

The dataset was transformed and loaded into a SQLite database, creating a structured workflow for later analysis.

### 5. Business KPIs

Key metrics were calculated, including:

- Average property price
- Average living area
- Average number of bedrooms

### 6. SQL Analysis

SQL queries were used to analyze average prices by zipcode and identify areas with higher property values.

### 7. Visualization

A scatter plot was created to analyze the relationship between living area and property price.

## Key Insights

- Property prices vary significantly by zipcode.
- Larger living areas tend to be associated with higher prices.
- SQL queries helped identify geographic differences in housing values.
- The Data Lake structure allowed a clearer separation between raw and processed data.
- The workflow demonstrates a basic Cloud Analytics and ETL process.
  
## Author

Ali Vega

Data Analytics • Cloud Analytics

## Repository Structure

```text
cloud-analytics-housing-data-lake/
│
├── README.md
├── report/
├── notebooks/
└── data/

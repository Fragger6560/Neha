## Hi! I'm Neha Verma  
**Business Analyst and MBA Student at UCW**

# AWS Data Analytic Platform for The City of Vancouver

## Overview

This project demonstrates the implementation of a **Data Analytic Platform (DAP)** on **AWS** for analyzing and optimizing business licenses within the City of Vancouver. It leverages AWS services to provide secure, efficient, and scalable data management, enhancing the city's operational capabilities and fostering citizen engagement.

---

## Objectives

- **Analyze business licenses**: Identify trends and insights using parameters such as employee count, expiration dates, and issue dates.
- **Implement AWS Services**: Utilize AWS Glue, S3, and Data Brew for data cleaning, storage, and analysis.
- **Provide actionable insights**: Develop exploratory and descriptive analytics for decision-making.

---

## Project Workflow

### 1. Data Discovery
Data was obtained from [Open Data Vancouver](https://opendata.vancouver.ca) and formatted as Excel/CSV files for ingestion. These datasets serve as the foundation for further analysis.

### 2. Data Storage Design
A robust storage architecture was implemented:
- **Landing**: Operational data storage.
- **Raw**: Cleaned data storage from AWS Glue Data Brew.
- **Curated**: Analytical data prepared for visualization.

### 3. Data Cleaning
AWS Glue Data Brew was used to:
- Remove duplicates.
- Fix formatting issues.
- Eliminate unnecessary columns for analysis.

### 4. ETL Pipeline Design
An ETL pipeline was designed using **draw.io** to:
- **Extract** data from the source.
- **Transform** data using custom logic.
- **Load** the cleaned data into AWS S3 for analysis.

### 5. Data Analysis
Graphical visualizations were created to:
- Count licenses by expiration year.
- Determine the average number of employees per license.

---

## Key Figures

### Data Insights
- **License Count by Expiration Year**: Aggregated for 2024.
- **Average Number of Employees**: ~5.47 employees/license.

### ETL Pipeline

---

## AWS Services Used
- **AWS Glue**: For ETL operations.
- **AWS S3**: For scalable data storage.
- **AWS Data Brew**: For no-code data cleaning.

---

## Results
The DAP platform:
- Streamlines the city's data management processes.
- Enhances service delivery efficiency.
- Provides real-time, secure access to critical data.

---

## About the Developer
**Neha Verma**  
I am a data enthusiast with expertise in AWS and a passion for creating impactful analytics solutions. Connect with me on [LinkedIn](https://www.linkedin.com/in/your-profile).

---

## Repository Structure
```plaintext
.
├── data/
│   ├── raw/
│   ├── cleaned/
│   └── curated/
├── scripts/
│   ├── etl_pipeline.py
│   └── data_analysis.py
├── images/
│   ├── etl_pipeline.png
│   └── data_visualization.png
└── README.md

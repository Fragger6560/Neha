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

# Descriptive Analysis

## Data Analytical Question Formulation
The possibilities of the DAP platform in the development and functioning of social infrastructure have been presented for the city of Vancouver as follows:

### Business Licenses
#### Data Discovery
Report files were obtained from Open Data Vancouver and downloaded as Excel or CSV files: business licenses within the city that form a basis for further analysis in AWS.

### Figure 1
<img width="964" alt="Screenshot 2024-12-04 at 1 02 19 AM" src="https://github.com/user-attachments/assets/7a6d54e4-ebae-4530-b2b0-8cf1aca0f164">

---

### DAP Steps: Data Analytical Question Formulation

**Goal:** To analyze the number of employees through the expiration date in Vancouver.  
**Parameter:** Number of Employees and Expired Date  

This is a **Descriptive Analysis**. This analysis aims to leverage AWS services to examine various aspects of Vancouver's business license by analyzing relevant parameters such as the number of employees, expiration date, issued date, etc.

### Figure 2
<img width="958" alt="Screenshot 2024-12-04 at 1 02 27 AM" src="https://github.com/user-attachments/assets/7e9ee57d-945e-452e-917a-5cd6c6e2a0df">
A graphical representation of data in a column format by year on the X-axis (as Expired Date). The total number of licenses is on the Y-axis. This graph clearly indicates that all licenses selected have an Expired Date in one year only (probably 2024 according to the label).

---

### Data Analytical Question Formulation
Specifically, the Digital Application Platform (DAP) on AWS is the key for Vancouver City as it improves the delivery of digital services, fosters effective data management, and utilizes scale and speed. This platform enhances the participation of the citizens, embraces efficiency in the execution of services and tasks, and guarantees the secure and authorized availability of necessary city resources and information in real-time.

---

### Data Analytic Platform Implementation
<img width="1062" alt="Screenshot 2024-12-04 at 1 02 36 AM" src="https://github.com/user-attachments/assets/366235c7-3d4a-4032-a580-cc9516998af9">
**Note:** Business requirement

#### Data Storage Design
Data Storage Design on AWS is fundamental to ensuring that data is stored securely and organized. It will also provide ease of access, handle volumes of data efficiently, and scale up when needed. In this setup, data will be safe and managed easily for analysis whenever required.

- **Landing:** Operational Data Storage  
- **Raw:** Cleaned Data Storage from Glue Data Brew  
- **Curated:** Analytical Data from AWS Glue  

<img width="1064" alt="Screenshot 2024-12-04 at 1 02 46 AM" src="https://github.com/user-attachments/assets/bed9c419-6910-46a5-b91c-156de3ba1d02">
**Figure 4:** Neha Data Storage Design in AWS

---

#### Data Ingestion
After collecting data from the operational environment, it is transferred to the Data Analysis Environment (AWS).  
**Figure 5**

<img width="1065" alt="Screenshot 2024-12-04 at 1 02 56 AM" src="https://github.com/user-attachments/assets/84129636-58cd-475e-befd-04fe1eac06d6">

---

#### Data Profiling
AWS Glue Data Brew is specifically used for data preparation and transformation. It makes it easier for users to work through cleaning, transforming, and structuring datasets without code. This means the data is well-sorted, complete, credible, and prepared for analysis or presentation.  
**Figure 6**

<img width="1007" alt="Screenshot 2024-12-04 at 1 12 30 AM" src="https://github.com/user-attachments/assets/4da4f2f0-a55f-489c-8c73-dbbaef0a0d91">

---

#### Data Cleaning
AWS Glue Data Brew is used for data preparation and transformation. It helps in cleaning datasets by removing duplicates, fixing formatting problems, addressing missing data, etc. For business licenses, unnecessary columns were deleted to achieve the desired outcome.  
**Figure 7**

<img width="1007" alt="Screenshot 2024-12-04 at 1 12 39 AM" src="https://github.com/user-attachments/assets/6952c9bc-e23d-4536-8d7b-c2437231db7e">

---

### ETL Pipeline Design
In draw.io, the ETL trial structure comprises the following stages: Extract, Transform, and Load. Starting with the data connection and retrieval process, then the extraction process, and finally applying transformation logic, the data is then loaded into the AWS S3 bucket or any database. To make each step clear and logical, a number of shapes and connectors are used.

- **Output:** Discovered the count of employees through the expiration date.  
- **Result:** 339  

<img width="1017" alt="Screenshot 2024-12-04 at 1 12 46 AM" src="https://github.com/user-attachments/assets/d7e2483b-1ae8-48d3-a566-fb58561eee4f">

**Figure 9:** Neha Pipeline Design  

<img width="847" alt="Screenshot 2024-12-04 at 1 12 54 AM" src="https://github.com/user-attachments/assets/4c240166-0d97-4bed-8c33-c73f5513a80d">

**Figure 10**  

<img width="877" alt="Screenshot 2024-12-04 at 1 13 01 AM" src="https://github.com/user-attachments/assets/76a24aca-5f58-4c6c-9276-07d3e4a32e3b">

**Figure 11:** Aggregation and Data Preview in ETL Pipeline 

<img width="1023" alt="Screenshot 2024-12-04 at 1 13 11 AM" src="https://github.com/user-attachments/assets/c6397a9e-cccf-44bf-ae00-655522aff8e6">

---

## Exploratory Analysis

### Data Analytical Question Formulation
The possibilities of the DAP platform in the development and functioning of social infrastructure have been presented for the city of Vancouver as follows:

---

### Business Licenses
#### Data Discovery
Report files were obtained from Open Data Vancouver and downloaded as Excel or CSV files: business licenses within the city that form a basis for further analysis in AWS.

**Figure 2**

This shows at least two key indicators presented next to each other:
1. The Count of Licenses (represented in blue columns).  
2. Average Number of Employees per License (represented in green columns).  

Data segmented by Expired Date (likely the year of expiration) shows results for 2024. A graphical representation of data in a column format has the year on the X-axis (as Expired Date) and the total number of licenses on the Y-axis. This graph indicates that all licenses selected have an Expired Date in one year only (probably 2024 according to the label).

---

### DAP Steps: Data Analytical Question Formulation
Specifically, the Digital Application Platform (DAP) on AWS is the key for Vancouver City as it improves the delivery of digital services, fosters effective data management, and utilizes scale and speed. This platform enhances the participation of the citizens, embraces efficiency in the execution of services and tasks, and guarantees the secure and authorized availability of necessary city resources and information in real-time.

---

### Data Analytic Platform Implementation

**Note:** Business requirement

#### Data Storage Design
The figure is the same as the Descriptive Analysis.

#### Data Ingestion
The figure is the same as the Descriptive Analysis.

#### Data Profiling
The figure is the same as the Descriptive Analysis.

#### Data Cleaning
The figure is the same as the Descriptive Analysis.

#### ETL Pipeline Design
In draw.io, the ETL trial structure comprises the following stages: Extract, Transform, and Load. Starting with the data connection and retrieval process, then the extraction process, and finally applying transformation logic, the data is then loaded into the AWS S3 bucket or any database. To make each step clear and logical, a number of shapes and connectors are used.

- **Output:** Found the average number of employees through expiration date.  
- **Result:** 5.47  

**Figure 9:** Neha Pipeline Design  
**Figure 10**  
**Figure 11**  

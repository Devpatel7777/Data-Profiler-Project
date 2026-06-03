# Customer Data Profiler Project

## Overview

The Customer Data Profiler Project is a complete Data Analysis and Exploratory Data Analysis (EDA) project developed using Python. This project demonstrates the complete data science workflow including data collection, data cleaning, visualization, SQL integration, JSON handling, API usage, and automated profiling reports.

The project uses a customer dataset containing information such as Age, Income, Purchases, Gender, and Churn status.

---

## Features

* Data Collection using CSV, JSON, SQL, and APIs
* Data Cleaning and Preprocessing
* Missing Value Handling
* Duplicate Data Detection
* Exploratory Data Analysis (EDA)
* Histograms and Boxplots
* Scatterplots and Heatmaps
* Correlation Analysis
* Automated Data Profiling Report
* Tensor Examples using NumPy
* Machine Learning Problem Understanding

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* SQLite
* Requests
* ydata-profiling

---

## Dataset Features

The dataset contains the following columns:

* CustomerID
* Name
* Age
* Gender
* Income
* Purchases
* Churn

---

## Project Structure

```text
Customer_Data_Profiler_Project/
│
├── customer_analysis_dataset.csv
├── customers.json
├── customer.db
├── report.html
├── project.ipynb
├── README.md
└── requirements.txt
```

---

## Installation

Install required libraries using:

```bash
pip install pandas numpy matplotlib seaborn requests ydata-profiling
```

---

## Import Libraries

```python
import pandas as pd
import numpy as np

import matplotlib.pyplot as plt
import seaborn as sns

import json
import sqlite3
import requests

from ydata_profiling import ProfileReport
```

---

## Exploratory Data Analysis

The project includes:

* Age Distribution
* Income Distribution
* Purchases Distribution
* Gender vs Purchases
* Income vs Purchases
* Correlation Heatmap
* Pairplot Analysis

---

## Data Profiling

Automated profiling report generation using:

```python
from ydata_profiling import ProfileReport

profile = ProfileReport(df_csv)
profile.to_file("report.html")
```

---

## Learning Outcomes

By completing this project, you will learn:

* Data Collection Techniques
* Data Cleaning Methods
* Exploratory Data Analysis
* Data Visualization
* SQL Integration
* JSON Handling
* API Data Fetching
* Profiling Reports
* Python for Data Science

---

## Future Improvements

* Add Machine Learning Models
* Build Streamlit Dashboard
* Deploy Project Online
* Add Advanced Visualizations
* Real-Time Data Analysis



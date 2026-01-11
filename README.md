# Smartphone Battery Analysis  
## APSSDC Data Analytics Internship Project

This project was developed as part of the **APSSDC (Andhra Pradesh State Skill Development Corporation)** Data Analytics Internship.  
The objective of this project is to analyze how different smartphone specifications influence **battery performance**.

---

## Project Objectives

- Analyze the impact of smartphone specifications on battery life  
- Perform data cleaning and preprocessing  
- Conduct exploratory data analysis (EDA)  
- Visualize relationships between features  
- Generate insights using Python  

---

## Dataset Overview

The dataset contains **500+ smartphone records** with the following attributes:

- Brand  
- Model  
- Battery Capacity (mAh)  
- RAM  
- Processor  
- Screen Size  
- Charging Time  
- Operating System (OS)  

---

## Data Cleaning & Preprocessing

Steps performed:

- Removed missing and inconsistent values  
- Converted data types  
- Normalized numerical features  
- Encoded categorical variables  
- Removed duplicate records  
- Handled outliers  

### Data Visualization

- Heatmap – Correlation between battery capacity and other features

- Scatter Plots – RAM, OS, and charging time vs battery life

- Bar Charts – Brand-wise battery capacity comparison

### Technologies & Tools

- Python
- Pandas
NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

### Project Structure
smartphone-battery-analysis/
├── CODE.ipynb
├── dataset.csv
├── visualizations/
└── README.md


### Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns


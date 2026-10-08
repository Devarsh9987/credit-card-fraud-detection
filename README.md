# 💳 Credit Card Fraud Detection

### Python Data Analysis Project

## Project Overview

This project analyzes credit card transaction data to identify patterns between genuine and fraudulent transactions.

The project focuses on data cleaning, data exploration, visualization, and finding useful insights from the transaction dataset.

## Dataset

The dataset used in this project is the **Credit Card Fraud Detection Dataset** from Kaggle.

The dataset contains information about credit card transactions, including transaction time, transaction amount, anonymized transaction features, and transaction class.

- **Dataset Source:** Kaggle
- **Number of Records:** 284,807
- **Number of Columns:** 31
- **Target Column:** `Class`
- `Class = 0` → Genuine Transaction
- `Class = 1` → Fraudulent Transaction

## Project Objectives

The main objectives of this project are:

- To understand the structure of the dataset
- To check and clean missing values
- To check duplicate records
- To check data types
- To identify outliers
- To analyze genuine and fraudulent transactions
- To create different visualizations
- To identify useful patterns and insights from the data

## Data Cleaning

The following data cleaning steps were performed:

- Checked for missing values
- Checked for duplicate records
- Checked the data types of columns
- Identified outliers using box plots
- Prepared the dataset for further analysis

## Data Visualizations

The following visualizations were created:

1. Transaction Amount Distribution
2. Genuine vs Fraudulent Transactions
3. Genuine vs Fraudulent Transaction Count
4. Transaction Time Distribution
5. Transaction Amount Box Plot
6. Time vs Transaction Amount
7. Correlation Heatmap

These visualizations help in understanding transaction patterns and the difference between genuine and fraudulent transactions.

## Key Findings

The analysis provides insights into:

- The distribution of transaction amounts
- The proportion of genuine and fraudulent transactions
- Transaction patterns over time
- Unusually high or low transaction amounts
- Relationships between selected transaction features
- The imbalance between genuine and fraudulent transactions

## Tools and Libraries Used

The following tools and Python libraries were used:

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab
- GitHub

## Implementation

The project was implemented using Python in Google Colab.

The following libraries were used for data analysis and visualization:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns

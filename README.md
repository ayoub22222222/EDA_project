# Exploratory Data Analysis (EDA) on Economic Dataset

## Overview

This project performs an exploratory data analysis (EDA) on an economic dataset, using Python libraries like `pandas`, `matplotlib`, and `seaborn`. The goal of this analysis is to understand the dataset, uncover underlying patterns, detect anomalies, and draw preliminary insights that can inform further modeling and decision-making.

## Table of Contents

- [Dataset Description](#dataset-description)
- [Objective](#objective)
- [EDA Steps](#eda-steps)
- [Technologies Used](#technologies-used)
- [How to Run](#how-to-run)
- [Results](#results)
- [Future Work](#future-work)

## Dataset Description

The dataset used in this analysis includes quarterly data on economic indicators across different years. Key variables include:

- **Year**: The year in which the data was recorded.
- **Quarter**: The quarter of the year (Q1, Q2, Q3, Q4).
- **CPI (Consumer Price Index)**: Measures inflation by tracking changes in the price of a basket of goods and services over time.
- **M1 (Money Supply)**: The amount of money in circulation, including cash and demand deposits.
- **Unemp (Unemployment Rate)**: The percentage of unemployed individuals in the labor force.
- **Infl (Inflation Rate)**: The rate at which the general price level of goods and services is rising.

## Objective

The main objectives of this EDA project are:

1. **Understand the Data Structure**: Examine data types, missing values, and the general structure of the dataset.
2. **Identify Relationships**: Study correlations and patterns between different economic variables.
3. **Detect Trends and Seasonality**: Look for annual or quarterly trends in variables like CPI, M1, and Unemployment Rate.
4. **Visualize Key Insights**: Use visualizations to highlight significant findings.

## EDA Steps

1. **Data Cleaning**:
   - Handling missing values.
   - Converting date and categorical information to the appropriate formats.
   
2. **Data Transformation**:
   - Creating new features like `Date` from `Year` and `Quarter`.
   - Aggregating data if needed (e.g., annual summaries).
   
3. **Descriptive Statistics**:
   - Calculating mean, median, variance, and other statistics for quantitative variables.
   
4. **Data Visualization**:
   - **Histograms** for distribution analysis.
   - **Boxplots** to detect outliers.
   - **Line plots** to observe trends over time.
   - **Correlation heatmaps** to understand relationships between variables.

5. **Trend Analysis**:
   - Analyzing year-over-year trends in inflation, unemployment, and CPI.

## Technologies Used

- **Python**
  - `pandas`: Data manipulation and analysis.
  - `matplotlib` & `seaborn`: Data visualization.
  - `statsmodels`: Statistical analysis for economic data.

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/eda-economic-dataset.git
   cd eda-economic-dataset


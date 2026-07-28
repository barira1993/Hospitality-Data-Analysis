# Hospitality-Data-Analysis
Exploratory Data Analysis of the Hospitality dataset using Python, Pandas, NumPy, Matplotlib and Seaborn.

Project Overview

This project focuses on performing Exploratory Data Analysis (EDA) on the Hospitality dataset using Python. The objective is to analyze booking patterns, occupancy trends, revenue performance, room categories, and customer ratings to generate meaningful business insights.

Problem Statement

The hospitality industry generates a large volume of booking and revenue data. Through this project, I analyzed the dataset to identify booking trends, capacity utilization, revenue distribution, and data quality issues that could support better business decisions.

Dataset

The dataset contains information related to hotel properties, room categories, bookings, capacity, revenue, and customer ratings.

Tools and Libraries Used Python Pandas NumPy Matplotlib Seaborn Jupyter Notebook

Data Cleaning Performed

Handled missing values in the capacity column using the median value. Identified and removed records where successful_bookings exceeded capacity. Checked for outliers in the revenue_realized column. Converted and standardized date columns. Verified data consistency across room categories.

Exploratory Data Analysis

The analysis includes:

Total bookings by property. Occupancy analysis. Revenue analysis. Room category analysis. Booking vs capacity comparison. Customer rating analysis. Outlier detection.

Key Insights

RT4 (Presidential Suite) rooms generally have higher revenue. No significant outliers were found in the revenue_realized column. A large number of customer ratings were missing, so I retained those records to avoid excessive data loss. Some booking records exceeded the available capacity and were removed during data cleaning.

Files in this Repository hospitality_eda.ipynb – Jupyter notebook containing the complete EDA. README.md – Project documentation.

Conclusion

This project demonstrates my ability to perform data cleaning, exploratory data analysis, visualization, and insight generation using Python and Pandas. It is my first end-to-end EDA project in the hospitality domain and an important step in building my data analytics portfolio.

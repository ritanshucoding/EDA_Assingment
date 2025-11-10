**📘 Project Overview**

This project performs Exploratory Data Analysis (EDA) and Feature Engineering on the Zomato Restaurants Dataset to gain insights into restaurant trends, customer preferences, and market patterns across different cities and countries.
The main objective is to clean, analyze, visualize, and derive insights from the data that could help in better business decision-making for restaurant-based platforms.

| File Name                         | Description                                                                                |
| --------------------------------- | ------------------------------------------------------------------------------------------ |
| `1-eda-feature-engineering.ipynb` | Jupyter Notebook containing complete data analysis and feature engineering process.        |
| `zomato.csv`                      | Primary dataset containing restaurant details such as names, cuisines, ratings, and costs. |
| `Country-Code.xlsx`               | Supplementary dataset mapping country codes to their respective country names.             |

**🧠 Project Objectives**

Understand dataset structure and variable characteristics

Clean and preprocess raw data (remove nulls, duplicates, incorrect entries)

Merge datasets for enhanced context and consistency

Perform EDA to explore:

Country-wise restaurant distribution

Top cuisines by popularity

Rating vs cost relationships

City and country-level comparisons

Engineer meaningful new features for deeper insights or model preparation

**📊 Methodology**

Data Loading & Understanding
Imported data from CSV and Excel files using Pandas and checked dataset shape, info, and summary statistics.

Data Cleaning

Handled missing and duplicate values

Converted data types

Removed unnecessary columns

Data Merging
Combined zomato.csv with Country-Code.xlsx to link restaurants to their respective countries.

Exploratory Data Analysis (EDA)
Used visualizations to uncover trends and insights, such as:

Most popular cuisines

Countries with the highest number of restaurants

Cost distribution by rating

Restaurant types and service patterns

Feature Engineering
Created new features such as cost categories, binary flags, and normalized variables to support modeling and better understanding.

**🧰 Tools & Libraries**

Programming Language: Python

Libraries Used:

pandas

numpy

matplotlib

seaborn

plotly

openpyxl

Environment: Jupyter Notebook / Google Colab

**📈 Insights & Findings**

India has the largest number of Zomato-listed restaurants.

North Indian, Chinese, and Fast Food cuisines dominate globally.

Restaurant ratings are typically higher in regions with moderate to high average costs.

Countries with more developed food industries show more variety and diversity in cuisine types.

Feature engineering allows better segmentation of restaurant markets.

**🧾 Requirements**

You can include this as a separate requirements.txt file in your repository:

pandas
numpy
matplotlib
seaborn
plotly
openpyxl

**RITANSHU TIWARI
📧 ritanshutiwari100@gmial.com
🔗 https://github.com/ritanshucoding
 | LinkedIn-- https://www.linkedin.com/in/ritanshu-tiwari-572808329/**

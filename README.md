# Black Friday Sales Analysis

This repository contains a Python-based Exploratory Data Analysis (EDA) project focused on a Black Friday sales dataset. The project utilizes popular data analysis and visualization libraries like Pandas, NumPy, and Seaborn to gain insights into customer behavior, purchasing patterns, and product performance during the Black Friday sales event.  The goal is to provide valuable market insights to benefit the company.

## Prerequisites

Before running the code in this repository, ensure you have the following Python libraries installed:

- Pandas: For data manipulation and analysis.
- NumPy: For numerical computing.
- Seaborn: For statistical data visualization.

Dataset Overview
The dataset contains 537,578 rows and 12 columns, capturing various aspects of customer transactions during Black Friday.

Project Overview
This EDA project is divided into seven key sections:

Dataset Walkthrough: Explores the basic properties of the dataset, including column names, data types, and missing values.  This section addresses the missing values in Product_Category_2 and Product_Category_3 by removing the entire columns to avoid significant data loss that would occur from row deletion.

Analyzing Columns: Uses unique() and nunique() functions to understand the distribution of values within each column. This helps identify the number of unique customers, products, and other categorical variables.  For example, we determine the total number of unique customers and products.

Analyzing Gender: Focuses on analyzing the Gender column.  This section investigates the distribution of male and female customers and their purchasing behavior.  We use groupby() to analyze which gender spends more and visualize the findings with pie charts and bar plots.

Analyzing Age & Marital Status: Analyzes the Age and Marital_Status columns. This includes identifying which age group makes the most purchases and has the highest purchasing amount.  The distribution of marital status is also examined and visualized.

Multi-Column Analysis: Performs multi-column analysis using Seaborn to explore relationships between variables.  Specifically, the relationship between Age and Gender is explored and visualized with appropriate plots, including legends (using the hue parameter).

Occupation and Products Analysis: Analyzes the Occupation, Product_ID, and Product_Category_1 columns.  countplot is used to understand the distribution of different occupations and product categories.  Bar plots, in conjunction with groupby(), are used to identify the products with the highest purchasing amounts.

Combining Gender & Marital Status: Combines Gender and Marital_Status for analysis.  Seaborn is used to visualize and gain insights into the combined effect of these two variables on purchasing behavior, primarily using countplot

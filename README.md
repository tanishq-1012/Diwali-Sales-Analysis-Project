# Diwali Sales Data Analysis

## Project Overview

This project focuses on analyzing Diwali sales data to gain insights into customer purchasing behavior, top-performing product categories, and sales trends across different demographics. The analysis includes data cleaning, exploratory data analysis (EDA), and visualization using Python.

## Dataset

The dataset contains sales records from a Diwali festival period, with attributes such as customer demographics, purchase details, and transaction amounts.

## Features

**Gender**: Customer gender (Male/Female)

**Age**: Age group of the customer

**Orders**: Number of orders placed

**Amount**: Transaction amount (purchase value)

**State**: Customer's location

**Marital_Status**: Customer's marital status

**Product_Category**: Type of product purchased

## Tools & Libraries Used

**Pandas**: Data manipulation and preprocessing

**NumPy**: Numerical operations

**Matplotlib & Seaborn**: Data visualization

## Data Cleaning

Removed unnecessary columns (Status, unnamed1)

Checked for null values and handled them appropriately

Converted Amount column to integer format for analysis

## Exploratory Data Analysis (EDA)

The following insights were derived from the data:

**Gender-based Analysis**: Female customers had a higher purchasing power.

**Age Group Analysis**: The 26-35 age group contributed the most sales.

**State-wise Analysis**: Uttar Pradesh and Maharashtra recorded the highest purchases.

**Marital Status Analysis**: Spending habits varied between married and unmarried customers.

**Product Category Analysis**: Identified top-selling product categories.

## Visualization

**Bar charts** for gender-based and state-wise sales distribution.

**Pie charts** for customer segmentation.

**Heatmap** to visualize correlations between numerical attributes.

**Histograms** to analyze spending behavior trends.

# Future Scope

Perform predictive modeling to forecast future sales trends.

Implement clustering algorithms (e.g., K-Means) for customer segmentation.

Identify seasonality patterns to optimize marketing strategies.

## How to Run the Project

1. Clone the repository:
   git clone https://github.com/your-username/diwali-sales-analysis.git

2. Install requried dependencies:
    pip install pandas numpy matplotlib seaborn

3. Run the analysis script:
   python analysis.py

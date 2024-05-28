# Exploratory Data Analysis (EDA) of Sales Dataset

This repository contains the Jupyter Notebook for the Sales Analysis Exploratory Data Analysis (EDA) project. The analysis is performed on the Superstore sales data to uncover insights and trends.

## Table of Contents
- [Project Overview](#project-overview)
- [Key Objectives](#key-objectives)
- [Data](#data)
- [Methodology](#methodology)
- [Tools and Libraries](#tools-and-libraries)
- [Insights](#insights)
- [Requirements](#requirements)
- [Usage](#usage)
  
## Project Overview

The goal of this project is to analyze sales data from a Superstore to uncover insights and trends that can inform business decisions. This analysis involves several steps, including data cleaning, preprocessing, feature engineering, and visualization.

### Key Objectives

1. **Data Cleaning and Preprocessing**:
    - Handle missing values in the dataset.
    - Convert date columns to datetime objects for better manipulation.

2. **Feature Engineering**:
    - Create new features such as `order_month` and `order_year` to facilitate time-based analysis.

3. **Exploratory Data Analysis**:
    - Explore the sales data to answer key questions, such as:
      - What is the overall sales trend?
      - Which products are top sellers?
      - What are the peak sales periods?
      - Who are the most valuable customers?
      - Which states generate the highest revenue?
      - Which cities generate the highest revenue?
      - How does revenue vary across different regions?
      - What is the sales breakdown by category and subcategory?
      - How do sales change year-over-year by category?
      - How does sales performance vary by shipping mode?

## Data

The dataset used for this project is the Superstore sales data, downloaded from Kaggle. You can download the dataset [here](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting/code).

The dataset includes information on orders, sales, profit, customer details, and shipment modes. The data spans several years, allowing for comprehensive time-series analysis.

## Methodology

1. **Data Cleaning**:
    - Impute missing values in the `Postal Code` column.
    - Convert `Order Date` and `Ship Date` columns to datetime format.

2. **Feature Engineering**:
    - Extract month and year from the order date to create `order_month` and `order_year` features.

3. **Visualizations**:
    - **Bar Plots**: To highlight top customers, states, and cities by revenue.
    - **Sunburst Charts**: To visualize sales breakdown by category, subcategory, and shipping mode.
    - **Year-over-Year Analysis**: To track sales trends over time within each product category.

## Tools and Libraries

- **Python**: Programming language used for the analysis.
- **pandas**: For data manipulation and analysis.
- **matplotlib and seaborn**: For creating static visualizations.
- **plotly**: For creating interactive visualizations.

## Insights

The analysis provides insights into key sales drivers, customer behavior, and regional performance. These insights can help identify high-performing products, target valuable customer segments, and optimize shipping strategies.

## Requirements

- Python 3.x: The programming language used for the analysis.
- Jupyter Notebook: The interactive environment for running Python code and displaying results.
- pandas: A library for data manipulation and analysis in Python.
- numpy: A library for numerical computations in Python, often used alongside pandas.
- matplotlib: A library for creating static visualizations such as line plots, bar charts, histograms, etc.
- seaborn: A statistical data visualization library built on top of matplotlib, providing more aesthetically pleasing and informative visualizations.
- plotly: A library for creating interactive visualizations and dashboards.

## Usage

To run the analysis, clone this repository and open the Jupyter Notebook in your preferred environment.

```bash
git clone https://github.com/gangadhar107/sales-analysis-eda.git
cd sales-analysis-eda
jupyter notebook sales_analysis.ipynb

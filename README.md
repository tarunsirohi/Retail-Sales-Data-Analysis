# Retail Sales Data Analysis

This repository contains a comprehensive analysis of retail sales data, exploring customer behaviors, product category preferences, pricing effects, and demographic patterns using Python (Pandas, Seaborn, Matplotlib). The analysis includes visualizations and interpretations that follow best practices for data analytics and business intelligence reporting.

---

## Table of Contents

- [About](#about)
- [Features & Insights](#features--insights)
- [Visualizations & Interpretations](#visualizations--interpretations)
    - [1. Sales Heatmap](#1-sales-heatmap)
    - [2. Gender Distribution](#2-gender-distribution)
    - [3. Age Distribution Histogram](#3-age-distribution-histogram)
    - [4. Correlation Heatmap](#4-correlation-heatmap)
    - [5. Spending by Age Group and Gender](#5-spending-by-age-group-and-gender)
    - [6. Price Distribution per Category](#6-price-distribution-per-category)
    - [7. Repeat Purchase Frequency by Age](#7-repeat-purchase-frequency-by-age)
    - [8. Pareto Analysis (80-20 Rule)](#8-pareto-analysis-80-20-rule)
    - [9. Category Popularity by Age](#9-category-popularity-by-age)
    - [10. Price vs Quantity Analysis](#10-price-vs-quantity-analysis)
    - [11. Product Category Exploration by Age](#11-product-category-exploration-by-age)
- [How to Run](#how-to-run)
- [Requirements](#requirements)

---

## About

This project analyzes a retail dataset to uncover trends in customer demographics, product category preferences, effects of pricing/discounts on sales volume, and customer loyalty patterns. It addresses key business questions such as:
- Which age groups and genders contribute most to revenue?
- Do discounts or lower prices significantly increase sales?
- Which product categories are most popular among different demographics?
- Who are the most valuable (Pareto/top 5%) customers?

---

## Features & Insights

- **Heatmaps** for monthly and categorical sales trends
- **Pie charts** for gender distribution
- **Histograms** and **bar charts** for age, spending, and repeat purchase analysis
- **Correlation analysis** for key features
- **Pareto (80-20) analysis** of customer revenue contribution
- **Boxplots** for price distributions across product categories
- **Scatter plots** for price vs. quantity sold, including by category

---

## Visualizations & Interpretations

### 1. Sales Heatmap
- **Purpose:** Compare sales amounts across months and product categories.
- **Insight:** Reveals seasonality and top-performing categories per month.

### 2. Gender Distribution
- **Purpose:** Pie chart showing proportion of male/female customers.
- **Insight:** Dataset is almost equally balanced between genders.

### 3. Age Distribution Histogram
- **Purpose:** Histogram of customer ages.
- **Insight:** Well-distributed sample across age groups; no strong skew.

### 4. Correlation Heatmap
- **Purpose:** Show correlations between numerical features (e.g., quantity, price, total amount).
- **Insight:** Total Amount is strongly correlated with Price per Unit and Quantity, as expected.

### 5. Spending by Age Group and Gender
- **Purpose:** Grouped bar plot of total spending by demographic.
- **Insight:** Customers aged 36+ are the biggest spenders; spending is similar for both genders at higher ages.

### 6. Price Distribution per Category
- **Purpose:** Boxplots of price per unit for Beauty, Clothing, Electronics.
- **Insight:** All categories have similar price distributions.

### 7. Repeat Purchase Frequency by Age
- **Purpose:** Bar chart of how often customers in each age group make repeat purchases.
- **Insight:** Repeat purchases increase with age—older customers are more loyal.

### 8. Pareto Analysis (80-20 Rule)
- **Purpose:** Identify top 5% of customers and those contributing to 80% of revenue.
- **Insight:** A small fraction of customers generate most of the revenue.

### 9. Category Popularity by Age
- **Purpose:** Stacked bar chart showing which categories are most popular with which age groups.
- **Insight:** Older customers buy more, especially Clothing and Electronics.

### 10. Price vs Quantity Analysis
- **Purpose:** Scatter plots of price vs quantity sold, overall and by category.
- **Insight:** No clear evidence that discounts/lower prices significantly increase sales volume.

### 11. Product Category Exploration by Age
- **Purpose:** Bar chart of number of categories tried by each age group.
- **Insight:** All age groups try all available categories—broad and uniform engagement.

---

## How to Run

1. Download or clone this repository.
2. Open the Jupyter notebook file (`.ipynb`) in [Jupyter Notebook](https://jupyter.org/) or [Jupyter Lab](https://jupyterlab.readthedocs.io/).
3. Ensure the dataset file (e.g., `sales_data.csv`) is in the same directory as the notebook.
4. Run the cells of the notebook to reproduce all analyses and visualizations.

---

## Requirements

The analysis uses the following Python libraries:

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
import warnings
warnings.filterwarnings('ignore')
```

Install the necessary packages with:

```bash
pip install pandas numpy matplotlib seaborn
```

---

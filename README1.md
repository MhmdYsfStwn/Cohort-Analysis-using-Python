# User Retention Cohort Analysis

## Project Overview

This project is part of the **Python for Data Analysis** training program by **MySkill** and focuses on analyzing user retention using **Cohort Analysis**. The analysis groups customers based on their first purchase month and tracks their purchasing activity over time to identify customer retention patterns.

The project covers data cleaning, exploratory data analysis (EDA), cohort analysis, and retention analysis. The results are used to identify key customer retention patterns and provide business recommendations.

## Objectives

* Understand customer purchasing behavior over time.
* Measure customer retention across different customer cohorts.
* Identify patterns and changes in customer retention.
* Provide insights and recommendations to support customer retention strategies.

## Dataset

The dataset used in this project was provided by **MySkill** under the name **"Retail Online Data"**. It contains more than **460,000 transaction records** with 7 features covering order, product, quantity, price, order date, and customer information.

**Dataset features:**

* `Order ID`
* `Product Code`
* `Product Name`
* `Quantity`
* `Order Date`
* `Price`
* `Customer ID`

## Analysis Process

The analysis was conducted through the following steps:

1. **Data Cleaning** – Checked and handled missing values, incorrect data formats, and outliers.
2. **Exploratory Data Analysis (EDA)** – Analyzed descriptive statistics, transaction status, best-selling products, and monthly transaction trends.
3. **Cohort Analysis** – Grouped customers based on their first purchase month and tracked their purchasing activity over subsequent months.
4. **Retention Analysis** – Calculated retention rates and visualized customer retention patterns using a cohort heatmap.
5. **Insights & Recommendations** – Identified key findings and provided recommendations based on the analysis results.

## Key Findings

* **97.8% of transactions were delivered**, while only 2.2% were canceled.
* **January had the largest customer cohort**, with 713 customers making their first purchase.
* The **January cohort showed relatively strong retention**, with a 39% retention rate in the second month and around 40%+ in several following months.
* **Most cohorts had retention rates below 50%**, indicating relatively low customer retention overall.
* **December recorded the lowest retention rates** across all cohorts compared to previous periods.
* Transaction activity increased significantly from **August to November**, before declining sharply in December.

## Recommendations

* **Improve customer retention** by implementing targeted promotions, personalized offers, and follow-up campaigns to encourage repeat purchases.
* **Learn from the January cohort** by analyzing its purchasing behavior and characteristics to identify strategies that may help improve retention in other cohorts.
* **Strengthen customer engagement before December** through targeted campaigns to reduce the decline in retention observed at the end of the period.
* **Optimize high-demand products** by prioritizing them in inventory planning and using them for cross-selling or product bundling opportunities.

## Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

  ## Project File

[User Retention Cohort Analysis Notebook](./Projek_MySkill_1%20(1).ipynb)

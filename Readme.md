# E-Commerce Performance & Profitability Analysis

# Dataset Overview
 
This project analyzes the Sample Superstore dataset from Kaggle.

# Dimensions: 13 columns and 9,994 rows.

# Data Cleaning: Identified and removed 17 duplicate rows. Checked for missing values (no NaN values found).

# Feature Engineering: Created two new columns: `Cost` and `Profit Margin %`.

# Data Export: Exported the cleaned dataset using `decimal=','` to ensure seamless loading into Google Sheets without regional formatting errors.

# Data Formatting: Ensured that `Profit`, `Cost`, `Profit Margin %`, `Discount`, and `Sales` were properly formatted as numerical data types for data modeling.



# Dashboard & Key Insights (Looker Studio)

An interactive dashboard was built using Looker Studio to track executive KPIs and business performance.

 [Click here to explore the interactive dashboard](https://datastudio.google.com/s/tmjx_3wt5Wk)


1. Overall Performance: The business shows positive total profits with a healthy profit margin of 12.01%.
   
2. Discount vs. Profitability: A deep dive into the data reveals a critical insight: there is a strong negative correlation between high discounts and profitability. Specifically, average discounts exceeding 20% consistently lead to net losses (negative profits).


3. Category Performance:Technology (50.8%) and Office Supplies (42.7%) drive the vast majority of the profits.


4. Geographic Distribution: The order map visualization highlights that the highest concentration of orders originates from the central-eastern regions.
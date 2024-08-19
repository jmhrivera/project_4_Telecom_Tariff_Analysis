### Project Name: project_04_DS_Telecom_Tariff_Analysis

### README
#### Overview

This project investigates the performance of two prepaid tariffs (Surf and Ultimate) offered by MegaLine, a telecommunication company. The main objective is to analyze customer behavior and determine which tariff generates more revenue. The project involves loading, cleaning, and processing datasets related to customers, calls, internet usage, and messages. Various analyses and visualizations are also conducted to draw meaningful insights into customer behavior and tariff effectiveness.

#### Objectives

1. Load and preprocess multiple datasets related to customers, calls, internet usage, and messages.
2. Clean and correct the data for consistency, removing duplicates and handling missing values.
3. Enrich the data by transforming and aggregating relevant columns.
4. Calculate the monthly usage statistics for each customer (calls, messages, and internet).
5. Determine the monthly revenue generated per customer for each tariff.
6. Analyze user behavior and visualizations to understand trends and patterns in usage.
7. Conduct hypothesis testing to validate key assumptions about the tariffs and customer behavior.

#### Way to Work

1. **Data Importing:** Load datasets for customers, calls, internet usage, messages, and tariffs into separate DataFrames.
2. **Data Cleaning:**
    - Remove duplicates and handle missing values appropriately.
    - Standardize data types for consistency.
    - Enrich the data by creating new columns (e.g., transforming MB to GB).
3. **Data Aggregation:**
    - Calculate monthly usage statistics (e.g., calls, message count, internet usage) per customer.
    - Merge multiple datasets to form a unified dataset containing all relevant information per customer.
4. **Revenue Calculation:**
    - Calculate the additional charges for usage exceeding the plan limits.
    - Compute the total monthly revenue for each customer.
5. **Behavior Analysis:**
    - Generate visualizations to analyze usage trends and customer behavior by tariff.
    - Surface key insights about user behavior and usage distributions.
6. **Hypothesis Testing:**
    - Test hypotheses such as revenue differences between tariffs and revenue comparison across regions.
7. **Conclusion:**
    - Summarize the findings, insights, and actionable recommendations based on the analysis.

#### Requirements

- pandas
- numpy
- matplotlib
- seaborn
- scipy

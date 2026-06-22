# **Superstore Sales Analysis (Python)**
## **Project Overview**

This project presents an exploratory data analysis (EDA) of the Global Superstore dataset using Python. The goal is to analyze sales performance, profitability, customer trends, and shipping efficiency to derive actionable business insights.

The project covers the full data analysis workflow including data cleaning, feature engineering, visualization, and insight generation.

## **Dataset Description**

The dataset contains transactional sales data from a global retail company.

**Key Features:**
Order Date / Ship Date – timeline of order and delivery
Customer Name – customer information
Region, Country, State, City – geographical data
Category & Sub-Category – product classification
Sales, Profit, Quantity, Discount – business metrics
Ship Mode – delivery method

**Data Preprocessing:**
- Converted date columns to datetime format
- Handled missing values (e.g., Postal Code)
- Created new features such as:
- Year, Month, Quarter
- Shipping Days (delivery time)

## **Analysis Methods Used**

The following techniques were applied:

**1. Data Cleaning**
- Handling missing values
- Correcting data types
- Removing inconsistencies
**2. Feature Engineering**
- Extracted time-based features (Year, Month)
- Calculated shipping duration
**3. Exploratory Data Analysis (EDA)**
-Sales and profit aggregation
- Group-by analysis (Category, Region, Customer, Product)
- Trend analysis over time
**4. Data Visualization**
- Line plots (sales trends)
- Bar charts (category, region, sub-category performance)
- Scatter plots (discount vs profit relationship)
- Boxplots (shipping performance)

**Tools used:**
Python
Pandas
Matplotlib
Seaborn

## **Key Insights**
- **Sales Trend:** Sales show an overall increasing trend over time
- **Category Performance:** Technology category generates the highest revenue
- **Profitability:** Some sub-categories (e.g., furniture items) produce negative profit
- **Discount Impact:** Higher discounts are strongly associated with lower profitability
- **Customer Contribution:** A small number of customers contribute a large portion of total sales
- **Regional Performance:** Certain regions outperform others in both sales and profit
- **Shipping Efficiency:** Faster shipping modes reduce delivery time but may not always be most used

## **Outcomes**
- Identified key drivers of sales and profit
- Highlighted loss-making products and inefficiencies
- Demonstrated practical skills in:
    - Data cleaning
    - Data visualization
    - Business insight generation

This project can be extended into a dashboard using tools like Tableau or Power BI for interactive reporting.

## **Conclusion**

The analysis provides a comprehensive understanding of sales dynamics within the Superstore dataset and offers insights that can support data-driven business decisions.

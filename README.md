# Coffee Sales Analysis

## Overview  
This project explores four years of transactional data from a coffee shop to uncover patterns in customer behavior, product performance, and regional trends. The objective is to support business decisions using real insights from sales, profit, and customer engagement.

##  Problem Statement  
The coffee shop needs to understand which coffee types perform best in terms of revenue and profit, how sales have evolved over time, and which customer or regional segments are most valuable. They also want to evaluate the impact of loyalty programs on profitability.

##  Tools & Technologies  
- **Python**  
- **Pandas** – Data manipulation  
- **Matplotlib** – Data visualization  
- **Excel** – Data source

##  Methodology & Steps  

1. **Dataset Upload and Merging**  
   - Loaded three Excel sheets: `Orders`, `Products`, and `Customers`.  
   - Merged them using `Customer ID` and `Product ID` to create a unified dataset.

2. **Data Cleaning**  
   - Updated shorthand roast types (e.g., `M` to `Medium`).  
   - Checked for duplicates, nulls, and datatype consistency.  
   - Created `Total_sales` and `Cost` columns.  
   - Extracted `year` and `month` from `Order Date`.

3. **Exploratory Data Analysis**  
   - Computed KPIs like total sales, quantity sold, and average profit.  
   - Grouped data by various dimensions for deep insights.  
   - Visualized findings using bar, line, and stacked bar charts.

## KPIs  
- **Overall Sales:** Total revenue from all transactions  
- **Overall Quantity:** Total number of coffee items sold  
- **Average Profit:** Mean profit across all sales

##  Analysis & Insights  

### 1. Revenue and Profit by Coffee Type  
**Chart:** Bar chart showing total revenue and profit by coffee type  


![COFFEE BY PROFIT](https://github.com/user-attachments/assets/173c2cff-de62-435e-aaf7-804b31d4f8bd)

- **Most Revenue:** *Excelsa*  
- **Most Profit:** *Liberica*

### 2. Yearly Sales Trend  
**Chart:** Line plot of total sales by year  

![YEARLY REV TREND](https://github.com/user-attachments/assets/4d89e622-ad03-4db2-be60-3cacb0c012e5)

- Sales rose steadily from 2019 to 2021  
- Sharp drop in 2022 indicates potential business challenges

### 3. Top 5 Customers by Revenue  
**Chart:** Horizontal bar chart  

![CUST BY REV](https://github.com/user-attachments/assets/a281220e-4604-414c-bbbb-fd73a0c16dce)

- High-value customers that could be prioritized in future marketing

### 4. Roast Type Popularity by Country  
** Chart:** Stacked bar chart

![ROAST BY COUNTRY](https://github.com/user-attachments/assets/a557aff8-7739-4b3a-b9ee-c2953b2b7890)

- Shows distinct roast preferences across the US, UK, and Ireland

### 5. Sales & Profit by Country  

**Findings:**  
- **Top Sales & Profit:** United States  
- UK lags behind in both metrics

### 6. Monthly Profit Trend   
- Reveals seasonal buying patterns and potential promotion windows

### 7. Top 10 Customers by Profit  
- Shows individual profit contribution from key customers

### 8. Impact of Loyalty Card    
- Surprisingly, customers *without* loyalty cards generated slightly more profit

## Recommendations  

- Focus on **Excelsa and Liberica** coffee types for promotions  
- Strengthen market presence in the **United States**  
- Introduce loyalty rewards for high-value customers  
- Analyze 2022's sales decline to prevent recurrence  
- Plan seasonal campaigns using monthly profit data

## Conclusion  
This analysis uncovered actionable insights that can help the coffee shop optimize its product offerings, improve customer loyalty, and boost regional performance. Data-driven strategies based on these findings can significantly increase profitability and customer satisfaction.



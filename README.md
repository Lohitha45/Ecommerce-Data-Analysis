# Ecommerce-Data-Analysis
 ### Overview
 This project analyzes Ecommerce sales data using **Power BI**. It includes Creating Date Table, Data Visualization, Creating Dashboard, Generating Insights to analyze KPIs and Trends. The goal is to identify top-selling Products, uncover sales trends, and optimize sales strategies.
### 📚Table of Contents:
1. [Overview](#overview)
2. [Data Sources](#data-sources)
3. [Tools Used](#tools-used)
4. [Problem Statement](#problem-statement)
5. [Data Cleaning and Processing](#data-cleaning-and-processing)
6. [SQL Queries for Data Analysis](#sql-queries-for-data-analysis)
7. [Process](#process)
8. [Result and Findings](#result-and-findings)
9. [Recommendations](#recommendations)
10. [Conclusion](#conclusion)
### 🗂️ Data Sources <a name="data-sources"></a> 
- The dataset used for this analysis is the "Pizza_Sales_Data.csv" file, containing detailed information.
- You can download the dataset from the following link: [Ecommerce Sales Dataset-1](ecommerce_data.csv) and [Ecommerce Sales Dataset-2](us_state_long_lat_codes.csv)       
### 🛠️Tools Used <a name="tools-used"></a>
 - **Excel**: Data Cleaning and Data Processing
 - **Power BI**: Data Modeling, Data Visualization, Creating Dashboard, Generating Insights

### ❓Problem Statement
 - Create a KPI Banner showing YTD Sales, YTD Profit, YTD Quantity sold, YTD Profit Margin

 - Find Year on Year growth for each KPI and show a YTD sparkline for each measure in the KPI to understand the monthly trend for each fact.

 - Find YTD Sales, PYTD Sales, YoY Sales growth for different customer category. Add a trend Icon for each category.

 -  Find YTD Sales performance by each State

 -  Top 5 and Bottom 5 Products by Sales

 -  YTD Sales by Region to know best and worst performing region all over country

 -  YTD Sales by Shipping Type to get the best shipping type percentage
### 🧹Data Cleaning and Processing
- <b>Steps Taken:</b>
   1. Identified inconsistent entries in the <b>"pizza_size"</b> column (S, M, L, XL, XXL).
   2. Extracted the day of the week from the <b>"order_date"</b> column to analyze sales trends based on weekdays.
- <b>Issues Encountered and Resolutions:</b>
  - The values in the pizza_size column (S, M, L, XL, XXL) were updated to more descriptive names for better clarity:
<b>S → Regular,
M → Medium,
L → Large,
XL → X-Large,
XXL → XX-Large.</b>
  - Added a new column named <b>"order_day"</b> that represents the day of the week (e.g., Monday, Tuesday, etc.).
### 🧑‍💻SQL Queries for Data Analysis
SQL queries were used to analyze pizza sales data, focusing on key performance indicators (KPIs) like total sales, top-selling pizzas, and sales trends by day and region. These queries helped address the problem statement and uncover valuable insights for optimizing sales strategies. For the complete list of SQL queries, click here for : [ SQL_Queries_for Data_Analysis ](https://github.com/Lohitha45/pizza-sales-analysis/blob/main/PIZZA%20SALES%20SQL%20QUERIES.docx).
### 📂Process
1. Data Cleaning and Processing
2. Made sure data is consistent and clean with respect to data type, data format and values used.
3. Data Modeling for Representing Relationships Between Datasets in Power BI
4. Data Visualization
5. Creating Dashboard, Generating Insights

### 📊Result and Findings <a name="result-and-findings"></a>
![Screenshot (185)](https://github.com/Lohitha45/Ecommerce-Data-Analysis/blob/15d8d3bcd7fcce44892fee2a9331e1dfa36f7f24/Screenshot%20(185).png)
### 🧐Key Findings
#### 1. Busiest Days and Times
- **Days**: Orders are highest on weekends, particularly on **Friday** and **Saturday evenings**.
- **Times**: Peak order times are between **12:00–1:00 PM** and **4:00–8:00 PM**.

#### 2. Category Performance
- The **Classic** category leads in both total orders and sales revenue.

#### 3. Size Contribution
- **Large-sized pizzas** generate the maximum revenue and contribute the most to total sales.

#### 4. Best Sellers
- **Classic Deluxe** and **Chicken Pizza** are the top-performing products, driving both orders and revenue.

#### 5. Worst Performer
- The **Brie Carre** has the lowest orders and revenue, ranking at the bottom in performance.

---
### 📈Recommendations <a name="recommendations"></a> 

1. **Boost Weekend and Evening Sales**  
   - Increase promotional offers or special deals during weekends and peak evening hours.

2. **Capitalize on Popular Products**  
   - Introduce combo offers or discounts on **Classic** and **Large-size pizzas** to maintain their popularity and increase revenue.

3. **Address Underperforming Products**  
   - Rethink the strategy for the **Brie Carre** by either marketing it differently or replacing it with a new flavor to cater to customer preferences.

4. **Enhance Operations During Peak Hours**  
   - Optimize staffing and operations during peak times (**12:00–1:00 PM** and **4:00–8:00 PM**) to handle higher order volumes effectivel
### Conclusion 
The pizza sales analysis reveals that weekends and evenings see the highest order volumes, with Classic and Large-sized pizzas leading in revenue. To boost sales, promotional offers during peak times should be introduced. The Brie Carre pizza underperforms and could benefit from better marketing or replacement. Optimizing staffing during peak hours will improve service efficiency. Continuous monitoring of seasonal factors and customer preferences will help adjust strategies for sustained growth.

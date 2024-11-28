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
- You can download the dataset from the following link: [Ecommerce Sales Dataset-1](ecommerce_data.csv) and [Ecommerce Sales Dataset-2](ecommerce_data.csv)       
### 🛠️Tools Used <a name="tools-used"></a>
 - **Excel**: For data cleaning, analysis, and initial visualizations.
 - **SQL Server**: For querying and analyzing the dataset.

### ❓Problem Statement
 - ####  KPIs Requirement:

   We need to analyze key indicators for our pizza sales data to gain insights into our business performance. Specifically, we want to calculate the following metrics:

   <b>1. 💰 Total Revenue:</b> The sum of the total price of all pizza orders.

   <b>2. 🧾  Average Order Value:</b> The average amount spent per order, calculated by dividing the total revenue by the total number of orders.

   <b>3. 🍕 Total Pizzas Sold:</b> The sum of the quantities of all pizzas sold.

   <b>4. 📦 Total Orders:</b> The total number of orders placed.

   <b>5. 🍽️ Average Pizzas Per Order:</b> The average number of pizzas sold per order, calculated by dividing the total number of pizzas sold by the total number of orders.
   

 
  - #### Charts Requirement:

    We would like to visualize various aspects of our pizza sales data to gain insights and understand key trends. We have identified the following requirements for creating charts:

    <b>  1. 📅 Daily Trend for Total Orders:</b>

    Create a bar chart that displays the daily trend of total orders over a specific time period. This chart will help us identify any patterns or fluctuations in order volumes on a daily basis.

    <b>2. ⏰ Hourly Trend for Total Orders:</b>

    Create a line chart that illustrates the hourly trend of total orders throughout the day. This chart will allow us to identify peak hours or periods of high order activity.

    <b>3. 🍕 Percentage of Sales by Pizza Category:</b>

    Create a pie chart that shows the distribution of sales across different pizza categories. This chart will provide insights into the popularity of various pizza categories and their contribution to overall 
    sales.
 
    <b>4. 🍕📏 Percentage of Sales by Pizza Size:</b>

    Generate a pie chart that represents the percentage of sales attributed to different pizza sizes. This chart will help us understand customer preferences for pizza sizes and their impact on sales.

    <b>5.  🍽️ Total Pizzas Sold by Pizza Category:</b>

    Create a funnel chart that presents the total number of pizzas sold for each pizza category. This chart will allow us to compare the sales performance of different pizza categories.

    <b>6.  🌟  Top 5 Best Sellers by Total Pizzas Sold:</b>

    Create a bar chart highlighting the top 5 best-selling pizzas based on the total number of pizzas sold.

    This chart will help us identify the most popular pizza options.

    <b>7. ❌ Bottom 5 Worst Sellers by Total Pizzas Sold:</b>

    Create a bar chart showcasing the bottom 5 worst-selling pizzas based on the total number of pizzas sold. This chart will enable us to identify underperforming or less popular pizza options.

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
1. SQL Queries for Data Analysis
2. Data Cleaning and Processing
3. Made sure data is consistent and clean with respect to data type, data format and values used.
4. Created pivot tables according to the questions asked.
5. Merge all pivot tables into one dashboard.
### 📊Result and Findings <a name="result-and-findings"></a>
![Screenshot (184)](https://github.com/user-attachments/assets/8a640cab-1585-4a8e-ad15-e3be73a7fe4a)
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

# 📊 Data Analytics Project – Sales Trends & Hypothesis Testing in Python

This project is a comprehensive sales analysis of a multi-tool retail dataset using Python. Through 26+ targeted data analysis tasks, the project simulates a real-world business scenario where data is used to inform decision-making and extract deep insights on performance.

---
## 📊 Key Visual Insights
##  Country-wise Order Distribution
## 🌍 Orders by Country

![Country-wise Orders](https://github.com/HarshitaSahu1/-Data-Analytics-Project-Sales-Trends-Testing-in-Python-/blob/7333cb4623564cba43d02d34b0323ef102b390ba/Country_wise_orders.png)

*Germany and the USA accounted for the highest number of orders, indicating strong customer bases in these markets.*

#### 📊 Yearly Product Trends – count-45-50

![Yearly Product Count](images/yearly_trend_45_54.png)

### Categorizing Customers Based on RFM Score
RFM (Recency, Frequency, Monetary) analysis was used to segment customers based on their purchase behavior:

- **Recency (R):** How recently a customer made a purchase  
- **Frequency (F):** How often they made purchases  
- **Monetary (M):** How much they spent in total
![RFM Segments](https://github.com/HarshitaSahu1/-Data-Analytics-Project-Sales-Trends-Testing-in-Python-/blob/064af61a1e7104dd6275b9406759ac4688b88d00/Categorizing_Customer_based_RFM_Score.png)

### Customer_Growth_Chart
![Customer Growth](https://github.com/HarshitaSahu1/-Data-Analytics-Project-Sales-Trends-Testing-in-Python-/blob/f6efd2208b237fed6c7226492a0bbf6f0f60885d/Customer_Growth_Chart.png)

💬 *Dual-axis chart comparing total and new customers monthly.*
### Revenue by Customer Type (Old vs New)
Customers were classified into two categories based on their first purchase date:

- **New Customers:** First-time buyers in the selected time period
- **Old Customers:** Returning or repeat buyers

![Revenue by Customer Type](https://github.com/HarshitaSahu1/-Data-Analytics-Project-Sales-Trends-Testing-in-Python-/blob/d0a426c7d9d9c8f2d1e48c1166f833368e65e47d/Revenue_Customer_Type.png)
- 

### Relationship Between Revenue and Quantity Sold

![Revenue vs Quantity](https://github.com/HarshitaSahu1/-Data-Analytics-Project-Sales-Trends-Testing-in-Python-/blob/55b6221fe869bd5fb80c6e03a5073e3dc2e25f6b/Revenue_vs_Quantity.png)

*Each dot represents a transaction. A mild upward trend suggests that higher quantity contributes to higher revenue, but not always linearly.*



## 📌 Project Objective

The aim of the project is to clean and analyze retail sales data, uncover customer purchasing patterns, understand the impact of time (e.g., weekdays vs weekends) on sales, identify outliers, and perform statistical tests to validate business hypotheses — all using Python and open-source libraries.

---

## 🔄 Analysis Workflow

The project followed a complete data analytics lifecycle:

### 1. 🧹 Data Cleaning
- Handled missing values and invalid data types
- Used the IQR method to remove outliers from key columns like Revenue, Cost, Quantity, and Profit
- Created a reusable function to apply outlier removal on multiple features

### 2. 📊 Exploratory Data Analysis (EDA)
- Analyzed revenue, cost, quantity, profit, and customer behavior
- Explored relationships across days, customer types (new vs existing), order frequency, and more
- Performed **RFM (Recency, Frequency, Monetary)** segmentation
- Examined product-level insights like top-selling products, highest profit items, and loss-generating products

### 3. 📅 Time-Based Analysis
- Extracted day, month, and weekday/weekend from date columns
- Compared sales behavior on weekdays vs weekends
- Identified peak revenue months and seasonality patterns
- Created **dual-axis charts** for total vs new customers over time

### 4. 📈 Data Visualization
- Used **Matplotlib** and **Seaborn** to create:
  - Bar charts, line charts, and boxplots
  - Correlation heatmaps and grouped comparisons
  - Visuals showing customer trends, sales peaks, and outlier impacts
- Saved visualizations as `.png` images to showcase in the README

### 5. 🧪 Hypothesis Testing
- Formulated null and alternate hypotheses to test revenue differences between weekdays and weekends
- Used statistical testing (`f_oneway` from SciPy or alternative logic) to compare distributions
- Interpreted p-values to make business conclusions with 95% confidence

---

## 🎯 Outcomes & Key Insights

- March recorded the highest number of new customers
- Sales and revenue do not differ significantly between weekdays and weekends (p > 0.05)
- Outlier removal helped improve accuracy of mean-based metrics
- Some products generated high revenue but low profit — potential pricing issues
- Customer churn patterns were visible by analyzing first vs last purchase dates
- Dual-axis charts gave strong visuals of customer growth vs acquisition rate

---

## 👩‍💻 Technical Summary

- Language: Python  
- Libraries: Pandas, Matplotlib, Seaborn  
- Concepts: EDA, Data Cleaning, Outlier Detection, Hypothesis Testing, Customer Segmentation, Data Visualization

---

## 🙋‍♀️ About Me

I'm **Harshita Sahu**, an aspiring data analyst with a passion for turning messy data into meaningful business insights.  
This project reflects my hands-on learning and practical application of core data analytics techniques using Python.

📫 Let's connect on [LinkedIn](https://www.linkedin.com/in/harshitasahu19231923)

---

## 📌 Related Tags

`Python` `EDA` `Data Cleaning` `Outlier Detection` `Sales Analysis` `Visualization` `Hypothesis Testing` `Retail Analytics` `Customer Behavior` `Women In Tech`

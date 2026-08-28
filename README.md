# Online Retail II Project
This project takes a real, messy two year retail dataset and turns it into a working relational database and a Excel dashboard,
with every decision along the way reasoned through rather than just executed. It follows the path an actual analytics project
would take, cleaning and profiling raw data in Paython use Pandas, This project focuses on analyzing online retail data to uncover actionable insights regarding sales trends, product performance, and customer purchasing behaviors. By leveraging advanced dashboard visualizations, the project aims to optimize inventory planning, enhance targeted marketing strategies, and improve overall business decision-making for the upcoming quarter.

📊 Project Presentation

For a detailed overview of the project, methodology, analysis, and key insights, check out the full presentation below:

👉 "View Project Presentation" :[Presentation.pdf](https://github.com/user-attachments/files/31567181/Presentation.pdf)






### Data Cleaning & Preparation
•	Before conducting the analysis and building the dashboard, the dataset underwent a rigorous cleaning and structuring process to ensure data integrity and accuracy:
•	Standardized Column Names & Formatting: Ensured consistent naming conventions and uniform data structures across all tables.
•	Irrelevant Data Removal: Filtered out unnecessary fields and irrelevant records to streamline the dataset.
•	Duplicate Removal: Identified and eliminated duplicate records to prevent skewed metrics.
•	Handling Cancelled Transactions: Separated cancelled transactions from regular sales to analyze them independently without affecting core revenue calculations.
•	Validation Checks: Removed transactions with invalid or non-positive prices (\le 0) and quantities (\le 0).
•	Standardization: Cleaned and standardized product descriptions and date values to enable accurate time-series and product performance tracking
Each of these came with a documented decision, not just a fix, and the full reasoning behind each one is in the report



Tools, Data Cleaning & Dashboard Metrics
Tools & Technologies Used:
Python (Pandas, NumPy): Utilized for robust data cleaning, handling missing/invalid records, and data preprocessing.
Microsoft Excel & Pivot Tables: Utilized for data modeling, creating interactive pivot tables, and designing the executive dashboard.
Key Dashboard Metrics (KPIs):
Total Revenue: 19.68M
Total Orders: 1.00M
Total Quantity Sold: 11.18M
Average Revenue (AVG Revenue): 20
Core Analytical Views Included in the Dashboard:
Revenue by Country: Highlighting geographic performance and market concentration (with a strong dominance of the UK market).
Sales Over The Days: Analyzing sales distribution across days of the week.
Revenue by Customers (Top 10): Tracking top high-value customers and their purchasing volume.
Revenue by Year, Month & Quarters (Time-Series): Tracking quarterly fluctuations and identifying seasonal spikes (such as Q4 performance).
Revenue & Quantity by Products (Top 10): Identifying top-performing products by revenue and quantity sold.



### Key Insights & Recommendations
Key Insights:
Geographic Concentration: The United Kingdom dominates the total revenue (generating approximately 17M out of 19.68M), indicating a strong dependency on the British market.
Seasonal Trends (Seasonality): A recurring and significant revenue spike is observed consistently in the fourth quarter (Q4) across all years, reflecting strong seasonal customer demand.
Top Products & Performance: Specific top-performing products (such as regency cakestand 3 tier) drive a massive percentage of total revenue and quantities sold.
Strategic Recommendations:
Market Diversification: While maintaining the strong UK market, the company should develop alternative growth markets (such as the Netherlands and Eire) to reduce concentration risk.
Proactive Inventory Planning: Leverage the identified Q4 seasonal pattern to scale up inventory levels and launch targeted marketing campaigns well ahead of time, avoiding stockouts and missed sales opportunities.
Customer Retention Strategies: Implement loyalty and reward programs tailored to the top-tier customers identified in the RFM/Customer analysis to sustain long-term revenue growth.



### Dashboard Overview & Narrative
•	Executive Summary Dashboard: The interactive dashboard designed for the online retailer (under the Lacoste performance structure) provides a comprehensive, high-لوفل overview of the business's overall health. It integrates key financial metrics with granular behavioral analytics, enabling management to track performance seamlessly across multiple dimensions up to December 2011.
•	Revenue & Sales Distribution: The dashboard highlights a total revenue of 19.68M generated across 1.00M orders and 11.18M total quantities sold. Through the geographical breakdown (Revenue by Country), it becomes immediately evident that the United Kingdom represents the dominant market share (generating roughly 17M), while other regions like the Netherlands and Eire contribute smaller, incremental shares. Furthermore, the Sales Over The Days chart illustrates a steady distribution of transactions throughout the week, peaking notably toward the end of the workweek.
•	Time-Series & Product Trends: The Revenue by Year, Month & Quarters time-series line chart reveals critical cyclical behavior, displaying sharp upward surges during the fourth quarter (Q4) of each operating year, followed by expected corrections in the first quarter. Additionally, the Revenue & Quantity by Products and Revenue by Customers views successfully isolate the top 10 revenue-driving products and high-value customer segments, providing the exact granular insights needed to optimize upcoming inventory restocking and targeted marketing campaigns.

<img width="1477" height="771" alt="Screenshot 2026-08-28 042558" src="https://github.com/user-attachments/assets/1b9c7d64-99f9-4bcf-ab67-74f9862f71d9" />




### Detailed Dashboard Charts Narrative
### •	1. Total Revenue, Orders, Quantity, and Average Revenue (KPI Cards):
The top KPI cards provide an immediate high-level summary of the overall business performance, recording a
##### 1.Total revenue of 19.68M. 
##### 2.Toal Orders 1.00M 
##### 3.Total orders 11.18M.
##### 4.Total quantities20.

### •	2. Revenue by Country (Bar Chart): 
This chart illustrates the geographical distribution of sales, revealing a massive concentration of revenue in the United Kingdom (generating approximately 17M), while other international markets like the Netherlands, Eire, Germany, and France contribute significantly smaller shares.

<img width="986" height="605" alt="Screenshot 2026-08-28 041440" src="https://github.com/user-attachments/assets/bd985b72-0612-4274-99b7-59349a3a24e1" />

### •	3. Sales Over The Days (Horizontal Bar Chart):
This view breaks down transaction performance across the days of the week, showing steady commercial activity with peak sales performance occurring toward the later part of the workweek (specifically peaking on Thursday with 4.01M).
<img width="747" height="500" alt="Screenshot 2026-08-28 041347" src="https://github.com/user-attachments/assets/bfc143b4-ef2b-4f57-b04a-c9b6ca3a055f" />

### •	4. Revenue by Customers - Top 10 (Column & Line Combo Chart):
This chart highlights the top 10 high-value customers based on total revenue and quantity purchased, helping isolate key high-tier buyers who drive substantial transaction volume compared to the rest of the customer base.
<img width="986" height="605" alt="Screenshot 2026-08-28 041440" src="https://github.com/user-attachments/assets/4b33ca5e-492a-40cf-b8dc-c1bd786c1b49" />

### •	5. Revenue by Year, Month & Quarters (Time-Series Line Chart):
This timeline tracks revenue fluctuations across operating years (2009 to 2011), clearly capturing cyclical behavior and recurrent seasonal surges during the fourth quarter (Q4) of each year, followed by standard contractions in the first quarter.
<img width="1067" height="592" alt="Screenshot 2026-08-28 041007" src="https://github.com/user-attachments/assets/d493105b-1282-4a3a-a047-dd9f12857f22" />

### •	6. Revenue & Quantity by Products - Top 10 (Column & Line Combo Chart): 
This chart isolates the top 10 best-performing products (such as regency cakestand 3 tier), tracking both their revenue contribution percentages and total quantities sold to guide future inventory restocking decisions.
<img width="1208" height="570" alt="Screenshot 2026-08-28 041256" src="https://github.com/user-attachments/assets/ea1728e0-d89e-4c24-a81d-8fed4960f5d8" />


### A Note on Transparency & Data Integrity
Throughout this project, every analytical choice—from handling data anomalies to defining threshold parameters—was approached with strict transparency and adherence to data integrity. Rather than relying on assumptions when encountering irregular metrics, discrepancies were thoroughly investigated and resolved using evidence-based validation. Furthermore, supplementary structures, such as synthetic inventory logs, are explicitly acknowledged and contextualized, ensuring that all findings and visualizations reflect an honest and accurate representation of the underlying data.

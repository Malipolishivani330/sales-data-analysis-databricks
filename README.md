📊 Sales Data Analysis using Databricks & PySpark
📌 Overview

This project focuses on analyzing sales data to identify monthly trends using PySpark in Databricks. The objective is to process raw data and convert it into meaningful business insights.

🎯 Objective

To build a simple data analysis pipeline that:

Processes raw sales data
Aggregates monthly sales
Visualizes trends for decision-making
🛠️ Tech Stack
Python
PySpark
Databricks
SQL (basic operations)
Data Visualization
🔄 Project Workflow (Step-by-Step)
1️⃣ Data Ingestion

Loaded sales dataset into the Databricks environment for processing.

2️⃣ Data Understanding & Cleaning
Checked schema and structure
Verified columns like order_date, sales
Ensured data is consistent and usable
3️⃣ Feature Engineering

Extracted month from the order_date column to analyze monthly trends.

4️⃣ Data Transformation

Used PySpark operations:

groupBy(month)
sum(sales)

to calculate total monthly sales.

5️⃣ Sorting & Optimization

Sorted data by month to maintain proper sequence for analysis.

6️⃣ Data Visualization

Created a line chart to represent monthly sales trends:

X-axis → Month
Y-axis → Total Sales
📈 Results & Insights
Highest sales observed in Month 1 (~446K)
Significant drop in Month 3 (~280K)
Partial recovery in Month 4 (~358K)
Overall declining trend towards Month 6
💡 Business Impact
Helps identify peak and low sales periods
Supports decision-making for inventory & marketing
Can be extended for forecasting
🚀 Future Enhancements
Add real-time data processing
Build dashboard using Power BI/Tableau
Implement predictive analytics
📌 Conclusion

This project demonstrates how PySpark can be used for efficient data processing and how raw data can be transformed into actionable insights.

🔗 Repository Link

https://github.com/Malipolishivani330/sales-data-analysis-databricks

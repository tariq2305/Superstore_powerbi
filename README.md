📊 Superstore Sales Performance Dashboard
📝 Overview
This project features a comprehensive Power BI dashboard that analyzes the sales performance of a retail superstore. The dashboard transforms raw sales data into actionable business intelligence, highlighting regional performance, product category profitability, and seasonal revenue trends to aid in executive decision-making.

🛠️ Tools & Technologies Used
Data Visualization: Power BI

Data Manipulation: DAX (Data Analysis Expressions)

Data Cleaning: Power Query

📁 Dataset
Source File: Sample_Superstore_Cleaned_UTF8

Details: Cleaned retail sales data containing order dates, geographic regions, product categories, and revenue metrics.

💡 Key Executive Insights
The dashboard focuses on three primary business takeaways:

🌎 Regional Sales: The West region generated the highest total sales revenue, significantly outperforming the South region, which recorded the lowest overall sales.

🏷️ Category Performance: Technology was the top-performing category for overall sales revenue, whereas Office Supplies saw lower revenue but the highest volume of total orders.

📈 Seasonal Trends: Sales exhibited a strong seasonal trend, consistently peaking in Q4—specifically November and December—while experiencing the lowest activity in January and February.

💻 Custom DAX Formulas
To enable accurate chronological sorting and clean visualizations for the time-series analysis, custom DAX calculated columns were created, including:

Code snippet
Order Month-Year = FORMAT('Sample_Superstore_Cleaned_UTF8'[Order_Date], "MMM-YYYY")
🎨 Dashboard Design & Layout
The dashboard utilizes a modern "Side-Panel" layout for maximum readability:

Top-Left: Line chart tracking Sales Over Months to establish overall business health.

Bottom-Left: Bar chart (Sales by Region) and Donut chart (Sales by Category) for detailed metric breakdowns.

Right Sidebar: A dedicated text panel displaying the Key Executive Insights, allowing stakeholders to immediately grasp the "why" behind the data

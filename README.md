📊 Power BI Sales Dashboard
🎯 Project Overview

This Power BI project focuses on analyzing and visualizing sales performance across products, customers, and time.
The goal was to design a dynamic, interactive dashboard that provides clear insights into revenue growth, product profitability, and customer value.

🧩 Data Preparation

To begin, multiple datasets were used — including:

Sales

Products

Customers

The raw data was imported from CSV files into Power BI Desktop.
Relationships were created between tables using Product ID and Customer ID, forming the foundation of the data model.

Before visualization, the data was cleaned in Power Query, where:

Column names were standardized

Data types were corrected

Headers were promoted for consistency

📐 Data Modeling (DAX & Calculations)

Several calculated columns and measures were created using DAX to derive key insights.

🧮 Key DAX Calculations:
Revenue = Sales[Quantity] * Sales[Unit Price]

Profit = [Revenue] - (Sales[Quantity] * Sales[Unit Cost])

Total Revenue = SUM(Sales[Revenue])

Total Profit = SUM(Sales[Profit])

Profit Margin % = DIVIDE([Total Profit], [Total Revenue])

Total Quantity Sold = SUM(Sales[Quantity])

Top 5 Customers Contribution % = 
DIVIDE([Top5 Revenue], [Total Revenue])


These measures provided deeper financial insights into profitability, customer contribution, and revenue performance.

📊 Dashboard Design & Visualizations

The Power BI dashboard was designed to be interactive, minimal, and executive-friendly, with a focus on clarity and usability.

🖥️ Key Visuals Included:

KPI Cards – Total Revenue, Total Profit, Profit Margin %, and Total Quantity Sold

Line Chart – Monthly Sales Trends showing performance and seasonality

Bar Chart – Revenue by Product and Category

Donut Chart – Revenue Distribution by Category

Table – Top 5 Customers by Revenue

Table – Product-level Profitability

Consistent fonts, colors, and layouts were used to maintain a professional and modern visual design.

💡 Insights & Findings

From the analysis, the following insights were uncovered:

💻 Computers category contributed the highest share of total revenue.

📈 Monthly sales showed a consistent upward trend throughout the year.

🧍‍♂️ Top 5 customers accounted for approximately 40% of total revenue.

⚙️ Some products generated high revenue but low profit margins, indicating opportunities for cost optimization.

🧠 Business Impact & Conclusion

The final Power BI dashboard empowers management to:

Track key business KPIs in real time

Identify top-performing products and customers

Analyze profitability trends effectively

Make data-driven strategic decisions confidently

This project demonstrates how Power BI’s DAX modeling, visual storytelling, and interactivity can transform raw sales data into actionable business insights that support growth and performance improvement.

📁 Project KPIs Summary
Metric	Value	Description
Total Revenue	₹201,784,000	Total revenue generated
Total Profit	₹19,350,661	Profit after cost deduction
Total Quantity Sold	12,442	Total units sold
Profit Margin %	9.58%	Overall profit margin
🎧 Audio Presentation

🎵 Listen to Project Overview (AI Voice)

🛠️ Tools & Technologies Used

Power BI Desktop

Power Query

DAX (Data Analysis Expressions)

Excel / CSV

GitHub for version control

AI Voice Narration (MP3)

👨‍💼 About Me

Kartik Verma
📊 Data Analyst with 3+ years of experience in transforming data into meaningful insights and interactive dashboards using Power BI, Excel, and SQL.
I specialize in creating visually compelling reports that help businesses make informed, data-driven decisions.

🔗 LinkedIn
 • GitHub

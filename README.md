Customer-Purchase-Insights-Excel-Analysis
This project showcases an Excel dashboard built to analyze customer purchase data. It highlights patterns across age groups, discounts, and profit margins, enabling better understanding of consumer behavior and sales trends.

🧭 Project Overview
The goal of this project is to analyze how customer demographics and discount rates affect total sales and profitability.
Using Excel’s built-in analytical tools, the dataset was transformed into a dynamic dashboard that presents key business KPIs and visual insights.

🧾 Dataset Description
Customer ID	
1. Age
2. Gender
3. Transaction ID
4. Product	Category
5. Quantity
6. Price per unit
7. Discount
8. Final Amount
9. Profit
10. Age Group
11. Date

⚙️ Steps Performed
1. Data Cleaning
Removed duplicates and blank rows
Standardized column names and data types
Used formulas to calculate the Final Amount, Discount, and Profit

2. Data Transformation
Created an Age Group column using:
=IF(F2<25,"Below 25",
IF(F2<=40,"25-40",
IF(F2<=60,"41-60","Above 60")))
Added calculated fields and formatted numbers, dates, and percentages

3. Dashboard Design
Built PivotTables for Sales and Profit summaries
Designed KPI Cards for Total Sales, Total Quantity Sold, Total Profit, Average Transaction Value, and Total Customers
Added Pivot charts

💡 Key Insights from the Dashboard
1. Overall Business Performance
The company achieved ₹456,000 in total sales with 2,514 total quantities sold and 1,000 unique customers.
The average transaction value is ₹456, showing consistent purchase patterns across customers.
The total profit generated is ₹136,800, reflecting healthy margins.

2. Sales by Gender
Male customers contributed slightly more to total sales compared to female customers, indicating higher spending per transaction by men.
However, both genders are actively contributing, showing a balanced customer base.

3. Sales by Product Category
The Electronics category leads in total sales (₹185,600), followed by Clothing (₹156,000) and Beauty (₹114,400).
This suggests that customers are more inclined toward high-value electronic products.
Marketing efforts can be strengthened in the Beauty segment to boost sales.

4. Monthly Sales Trend
Sales show steady movement with visible peaks in certain months, indicating seasonal or promotional sales periods.
A potential spike suggests effective marketing or discount campaigns in those months.
Continuous sales consistency indicates good customer retention.

5. Sales by Age Group
Customers aged 25–40 dominate the purchase activity, contributing the highest revenue (~₹173,000).
The 41–60 age group follows, indicating strong engagement among working professionals.
The segment below 25 has the lowest sales, showing room for youth-focused marketing campaigns.

6. Profit by Product Category
The Electronics category generates the highest profit (~₹67,200), followed by Clothing (~₹48,600).
The Beauty category shows the least profit (~₹21,000), possibly due to lower margins or higher discounts.
This helps identify where to adjust pricing and discount strategies for optimal profitability.

🧠 Business Recommendations
1. Increase targeted promotions toward 25–40-year-old customers, as they are the most profitable segment.
2. Explore discount optimization for Beauty products to increase profitability.
3. Maintain focus on Electronics, but consider introducing bundled offers to increase volume.
4. Introduce youth-oriented campaigns to capture the below-25 segment, perhaps via social media engagement.

📈 Dashboard Features
✅ KPI Cards for key business metrics
✅ Visual analysis by Age Group, Product, and Gender

🧠 Skills & Tools Used
Microsoft Excel (Formulas, PivotTables, Charts)
Data Cleaning & Formatting Techniques
Business Analysis & Dashboard Design
Problem Solving & Analytical Thinking


🧍‍♀️ Author
Tanishque Gupta
📍 Jammu, India
🎓 BBA (Information Technology), Lovely Professional University

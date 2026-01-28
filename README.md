# Coffee-Sales-Analysis-Dashboard-Power-BI-
This project analyzes coffee sales data to uncover insights into customer behavior, product performance, and revenue trends.
# Project Overview
This Power BI dashboard analyzes coffee sales data across multiple dimensions including customer behavior, product performance, geographic distribution, and temporal trends. The analysis covers 1,000 customers generating 957 orders with total revenue of $45,134.26.
Using Power BI, the dashboard provides an interactive view of key business metrics to support data-driven decision-making.
The analysis focuses on sales performance, customer preferences, geographic distribution, and time-based revenue trends.
# Tools & Skills
* Power BI – Data modeling, DAX calculations, and dashboard visualization
* Power Query – Data cleaning and transformation
* DAX – Measures and calculated fields
* Data Modeling – Star schema with fact and dimension tables
# Dashboard Components
Key Performance Indicators (KPIs):
* Total Customers: 1,000
* Total Orders: 957
* Average Order Value (AOV): $47.16
* Total Revenue: $45,134.26
* Loyal Customers: 487 (48.7%)
# Visualizations:
* Orders by Country - Bar chart showing geographic distribution
* Revenue Share by Roast Type - Donut chart showing Light, Medium, and Dark roast preferences
* Revenue by Coffee Type - Clustered bar chart comparing Arabica, Excelsa, Liberica, and Robusta
* Customer Preference by Coffee Type - Bar chart showing order distribution
* Revenue Performance Overtime - Line chart showing temporal trends
* Interactive Filters - Year slicer (2019-2022) and Loyalty Card filter
# Data Structure
Tables Used:
* Customers Table
Customer ID
Customer Name
City
Country
Loyalty Card (Yes/No)
* Orders Table
Order ID 
Order Date
Customer ID
Product ID
Quantity (typically 2 units per order)
Revenue
* Products Table
Product ID 
Coffee Type (Arabica, Excelsa, Liberica, Robusta)
Roast Type (Light, Medium, Dark)
Unit Price (range: $2.685 - $36.455)
Profit per unit
Relationships
Orders → Customers (via Customer ID)
Orders → Products (via Product ID)
# Key Insights & Analysis
1. Critical Customer Performance
Finding:
1,000 customers have placed only 957 total orders
Average orders per customer: 0.96 (less than 1!)
This indicates most customers purchase only once and never return
* Why This Matters:
Customer acquisition costs are typically 5-7x higher than retention costs
One-time buyers provide minimal lifetime value
Business model is unsustainable without repeat purchases
* Revenue Impact:
If each customer ordered just 3 times instead of 1: Revenue would be $135,000+ (3x growth)
Current lost opportunity: ~$90,000 in potential revenue
# Loyalty Program Ineffectiveness 📉
* Finding:
 487 customers have loyalty cards (48.7% of total)
These loyal customers generated only 464 orders (48.5% of total)
Loyal customers average: 0.95 orders each
Regular customers average: 0.96 orders each
Loyal customers actually order LESS than regular customers and generate lower revenue than regular customers.
* Analysis:
The loyalty program is not creating actual loyalty. Having a card doesn't translate to behavioral change or repeat purchases.
Program Issues:
* Insufficient incentives
* No exclusive benefits
* Poor communication/engagement
* No tiered rewards system
# Geographic Distribution
The United States is the dominant market with 423 orders.
Ireland (146 orders) and the United Kingdom (68 orders) contribute significantly less, highlighting potential growth opportunities outside the US.
* Finding:
United States: ~80% of orders (dominant market)
Ireland: ~15% of orders
United Kingdom: ~5% of orders
Risk Analysis:
Heavy dependence on single market (US)
Vulnerable to US market disruptions
Untapped potential in Ireland and UK
Opportunity:
Ireland and UK markets exist but underperforming
Small marketing investment could yield significant returns
Markets show demand but need focused attention.
# Product Performance
All four types show relatively balanced revenue contribution,Excelsa and Liberica are the highest revenue-generating coffee types.
Arabica performs moderately, while Robusta contributes the least revenue, indicating lower customer demand.
* Roast Types (3 varieties):
Light: ~38.45%
Medium: ~32.35%
Dark: ~29.2%
Nearly equal distribution shows diverse customer preferences
* Findings:
 Product diversification strategy is working
No single product dependency
All segments have demand
Can market different products to different customer.
* Customer Preferences
Customer preferences are relatively balanced across coffee types, with Arabica slightly leading.
Robusta is the least preferred, aligning with its lower revenue contribution.
# Revenue Trend Analysis
Revenue fluctuates over time with visible peaks and dips rather than a steady growth pattern.
These variations may be influenced by seasonality, promotions, or demand cycles, suggesting opportunities for deeper time-series analysis.
* Observation from Trend Line:
Revenue shows significant fluctuations with peaks and valleys throughout the year.
* Sales Dip Analysis:
The dashboard shows a notable decline in August. Possible reasons:
Summer Vacation Effect
Customers away on vacation
Office/business clients closed
Reduced coffee consumption in hot weather
Competition
Seasonal promotions from competitors
Cold brew alternatives gaining market share in summer
Inventory/Supply Issues
Possible stockouts during peak demand
Shipping/fulfillment delays
Marketing Gap
No August promotional campaigns
Reduced advertising spend
* Recommended Investigation:
Analyze order patterns: Are existing customers buying less, or are there fewer new customers?
Check inventory records: Were popular products out of stock?
Review competitor activity during this period
Survey customers about summer buying habits
# Conclusion
The Coffee Sales Dashboard reveals a business with solid transaction economics ($47.16 AOV) but critical retention challenges (0.96 orders per customer). The primary opportunity is not in acquiring more customers or increasing prices, but in getting existing customers to buy more frequently.
Customers are buying mid-to-high priced products,bundle size (2 units) is reasonable
No need to dramatically increase prices,focus should be on increasing frequency, not transaction size
 The Path Forward:
Fix retention first 
Make loyalty program actually create loyalty 
Address seasonal volatility 
Then scale internationall
Perform customer segmentation to identify high-value customers
Analyze seasonality and promotional impact on revenue
Bundling strategies to improve AOV.![coffe sales D](https://github.com/user-attachments/assets/8783e95b-cfa7-4ab2-900c-ed6733a73c23)

📊 Superstore USA — Sales Analytics Dashboard

An interactive Tableau dashboard built to analyze retail sales performance across the United States, helping stakeholders make data-driven decisions on products, regions, and customer segments.


🖼️ Dashboard Preview
![Dashboard Preview](dashboard_preview.png)


🧩 Business Problem
A US-based retail superstore operates across multiple regions and product categories — Technology, Furniture, and Office Supplies. The management team faced key challenges:

Which product categories and sub-categories drive the most revenue?
Which US states and regions are performing well vs. underperforming?
What is the overall profit margin and is the business growing over time?
Which customer segments (Consumer, Corporate, Home Office) generate the most sales?
What are the top-selling individual products?

Without a centralized view, these questions were difficult to answer quickly, leading to slow decision-making and missed opportunities.

💡 Solution
This Tableau dashboard provides a single-page interactive analytics report that consolidates all key business metrics into one view. It enables stakeholders to:

Switch between Sales, Profit, and Order Count metrics using the Matrix selector
Filter data by Region and Year of Order Date
Click on category bars to drill down into specific product segments
View geographic distribution of sales across all US states


📁 Dataset
FileDescriptionSuperstore.xlsxMain orders dataset — Order ID, Order Date, Ship Date, Ship Mode, Customer details, Region, Product Category/Sub-Category, Sales, Quantity, Discount, ProfitOrders.xlsxSupporting orders data — Customer ID, Order ID, Sales, Product IDCustomers.xlsxCustomer master data — Customer ID, Name, Salary details
Key fields used:

Sales, Profit, Quantity, Discount
Category, Sub-Category, Product Name
Segment (Consumer / Corporate / Home Office)
State, Region, Order Date


📈 Dashboard Features
VisualWhat it ShowsKPI CardsTotal Sales (₹2.30M), Profit Margin (12.47%), Return Rate (5.91%)Sales by Category% contribution of Technology (36.4%), Furniture (32.3%), Office Supplies (31.3%)Sales by Sub-CategoryBar chart of all 17 sub-categories — Phones and Chairs leadSales by State (Map)Geographic heatmap — California leads with ₹457,688Sales by SegmentDonut chart — Consumer (50.56%), Corporate (30.74%), Home Office (18.70%)Top 5 ProductsCanon imageCLASS 2200 Copier leads at ₹61,600Sales TrendMonthly sales trend from 2013–2018 with a growth trendline

🎯 Key Insights

📦 Technology is the top revenue category at 36.4% of total sales
📍 California is the highest-performing state with over ₹457K in sales
👥 Consumer segment drives the majority of business — 50.56% of total sales
📉 Profit margin of 12.47% indicates room to optimize discounting strategies
📈 Sales show an upward trend from 2013 to 2018, confirming business growth


👥 Stakeholder Benefits
StakeholderBenefitSales ManagerIdentify top-performing regions and products to allocate resources effectivelyCategory ManagerUnderstand which sub-categories need promotion or discontinuationFinance TeamMonitor profit margins and return rates to control costsMarketing TeamTarget the Consumer segment with personalized campaignsExecutive LeadershipGet a high-level snapshot of business health in one view

🛠️ Tools Used

Tableau Desktop — Dashboard design and visualization
Microsoft Excel — Data source (Superstore, Orders, Customers)
Mapbox / OpenStreetMap — Geographic map rendering




📂 Repository Structure
📦 superstore-tableau-dashboard
 ┣ 📊 Assignment__Tableau_Chetan_Nimwal_correct_version.twbx
 ┣ 📄 Superstore.xlsx
 ┣ 📄 Orders.xlsx
 ┣ 📄 Customers.xlsx
 ┣ 🖼️ dashboard_preview.png        ← Add your dashboard screenshot here
 ┗ 📝 README.md

👤 Author
Chetan Nimwal
Tableau Dashboard Developer

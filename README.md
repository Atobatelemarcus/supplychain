# supplychain
📊 Supply Chain Performance Analysis Report
Prepared Using: SQL & Power BI
Dataset Size: 100 Products
Data Columns: Product, Sales, Stock, Shipping, Manufacturing, Quality, Costs

✅ Problem Statement
The company is experiencing inefficiencies in its supply chain processes, such as stockouts, long lead times, high defect rates, and rising shipping/manufacturing costs. This report aims to uncover key issues and provide data-driven recommendations to improve operational efficiency and profitability.

🎯 Key Performance Indicators (KPIs)
Revenue per Product = Revenue Generated / SKU

Sell-through Rate = Products Sold / Availability

Average Stock Level = Mean of Stock Levels

Average Lead Time = Mean of Lead Times (order + manufacturing)

Defect Rate = Mean % of product defects

Average Manufacturing Cost per SKU

Shipping Time and Cost per Route and Carrier

📌 Key Insights
🔼 High Revenue SKUs:

Some low-selling items generate high revenue due to premium pricing (e.g., haircare product SKU2).

SKU0 and SKU4 also drive strong revenue with relatively high unit sales.

🛠️ Manufacturing Bottlenecks:

Average manufacturing lead time is ~18.6 days. Some products take up to 30 days, delaying delivery.

Supplier 1 and Supplier 5 are involved in SKUs with high production volume but also high defect rates.

📦 Inventory Concerns:

Stock levels vary dramatically — some products have excess inventory while others are nearly out-of-stock.

Sell-through rates for some SKUs are extremely low, indicating overproduction.

🚚 Shipping Inefficiencies:

Air transport is the costliest (avg > $800 per unit on some SKUs) but used frequently for low-selling products.

Route A is associated with high costs and longer delivery times.

Supplier 3 (Mumbai) has the most efficient shipping profile.

⚠️ Quality Control Issues:

Products with Pending or Failed inspection results also exhibit high defect rates (avg > 4%), especially those with Supplier 1 and Supplier 5.

Average defect rate across products is 2.9%, but several SKUs exceed 5%.

🧠 Recommendations
Optimize Supplier Mix:

Shift production away from Supplier 1 and Supplier 5 for products with high defect rates and long lead times.

Consider Supplier 3 for more consistent output and shipping.

Inventory Rebalancing:

Reduce production of low-performing SKUs with high stock levels.

Improve forecasting using historical sales and seasonality models in Power BI.

Logistics Cost Control:

Limit Air shipping to high-demand or perishable items only.

Reevaluate the cost-benefit of Route A and switch to Route B or C where feasible.

Improve Quality Assurance:

Automate and enforce quality checks before shipment.

Flag products with repeated inspection failures for review.

Data-Driven Decision Making:

Use Power BI dashboards to:

Monitor SKU-level performance in real time.

Alert management to rising lead times or defect spikes.

Correlate product pricing with sales and defect rates for pricing strategy.

Would you like me to generate a Power BI dashboard template or prepare this full report as a PDF file? 



📌 Key Performance Indicators (KPI) Results
KPI	Value
Revenue per Product	$5,776.05
Sell-through Rate (Avg. Units Sold ÷ Availability)	26.09x
Average Stock Level	47.77 units
Average Lead Time (Order + Manufacturing)	30.73 days
Average Defect Rate	2.28%
Average Manufacturing Cost per SKU	$47.27
Average Shipping Time	5.75 days
Average Shipping Cost	$5.55

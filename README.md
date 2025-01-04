Supply Chain Analytics Dashboard
Overview
This interactive Power BI dashboard provides a comprehensive view of supply chain performance across regions and product categories. The dashboard is designed to highlight key performance indicators (KPIs) such as on-time delivery rate, average delivery time, cost per unit shipped, and delivery performance. It enables stakeholders to identify inefficiencies, optimize logistics, and improve decision-making.

DAX Calculations Used in the Supply Chain Analytics Dashboard
On-Time Delivery Rate
This calculation determines the percentage of orders delivered on time by dividing the number of on-time deliveries by the total number of orders and multiplying by 100.

Formula:
OnTimeDeliveryRate = (Count of On-Time Deliveries / Total Deliveries) * 100
Average Delivery Time by Region
This calculates the average delivery time (in days) for each region by averaging the DeliveryTime field.

Formula:
AvgDeliveryTimeByRegion = Average(DeliveryTime) for each Region
Cost Per Unit Shipped
This measure calculates the shipping cost per unit by dividing the total shipping cost by the total order volume.

Formula:
CostPerUnitShipped = Total Shipping Cost / Total Order Volume
Delayed Shipments Percentage by Product
This calculation determines the percentage of delayed shipments for each product category by dividing the number of delayed shipments by the total number of shipments for that product and multiplying by 100.

Formula:
DelayedPercentageByProduct = (Count of Delayed Shipments for a Product / Total Shipments for that Product) * 100
Inventory Turnover Rate
This metric calculates how frequently inventory is replenished by dividing the total order volume by the average inventory level.

Formula:
InventoryTurnover = Total Order Volume / Average Inventory Level
Revenue Contribution by Region
This measure calculates the percentage of total revenue contributed by each region by dividing the revenue of a specific region by the total revenue and multiplying by 100.

Formula:
RevenueByRegion = (Region Revenue / Total Revenue) * 100
Cumulative Orders Over Time
Tracks the cumulative number of orders over time by summing the total orders up to a given date.

Formula:
CumulativeOrders = Total Orders up to a given Shipment Date
Delivery Performance Index
A composite KPI that combines on-time delivery rate and average delivery time to measure overall delivery efficiency.

Formula:
DeliveryPerformanceIndex = On-Time Delivery Rate / (Average Delivery Time + 1)


Dashboard Features
On-Time Delivery Rate by Region (Treemap):

Visualizes the percentage of on-time deliveries across different regions.
Insight: Regions like North America and Europe show better performance, while Africa and South America lag behind, highlighting areas for improvement.
Average Delivery Time by Product (Bar Chart):

Displays the average delivery time for each product category.
Insight: Products like Books and Clothing have shorter delivery times, while Furniture and Food take longer, indicating potential logistical challenges for these categories.
Cost Per Unit Shipped by Product (Bar Chart):

Shows the average shipping cost per unit for each product category.
Insight: Electronics and Automotive have higher shipping costs, suggesting opportunities for cost optimization in these categories.
Delivery Performance Index by Product (Line Chart):

Combines on-time delivery and average delivery time into a single performance metric for each product.
Insight: Toys and Books perform well, while Food and Furniture have lower indices, indicating areas needing improvement.
Cumulative Orders by Delivery Time and Product (Stacked Area Chart):

Tracks cumulative orders over time, segmented by product category.
Insight: Peaks in Electronics and Clothing orders highlight periods of high demand, helping optimize inventory and staffing.
Revenue by Region and Product (Clustered Bar Chart):

Shows revenue contribution by region and product category.
Insight: North America and Europe contribute the most revenue, with Electronics and Furniture being top-performing products.
Insights Gained
Regional Performance:

Africa and South America have lower on-time delivery rates, suggesting logistical challenges.
North America and Europe are leading regions in terms of delivery efficiency and revenue contribution.
Product-Specific Challenges:

High shipping costs for Automotive and Electronics suggest potential inefficiencies in transportation.
Food and Furniture consistently underperform in delivery metrics, indicating the need for supply chain improvements.
Order Trends:

Significant peaks in Cumulative Orders for products like Electronics and Clothing highlight demand surges, enabling better resource allocation.
Impact of the Dashboard
Operational Improvements:

Identified regions and products requiring attention, enabling targeted logistical improvements.
Highlighted high-performing areas, reinforcing best practices.
Cost Optimization:

Pinpointed products with high shipping costs, paving the way for renegotiating contracts or optimizing routes.
Strategic Decision-Making:

Provided actionable insights to optimize inventory, improve delivery times, and increase overall supply chain efficiency.
Future Enhancements
Implement real-time data tracking for live performance monitoring.
Introduce predictive analytics to forecast demand and delivery delays.
Expand KPIs to include environmental impact metrics, such as CO2 emissions per shipment.

#Adventure Works Sales Dashboard
Overview
The Adventure Works Sales Insights Dashboard is a Power BI visualisation tool designed to provide actionable insights into the sales performance, product trends, and customer purchasing behaviour of Adventure Works' product portfolio. This dashboard was created using data from an Excel file and offers a variety of visualisations and filters to support data-driven decision-making.
Objective
The primary objective of this dashboard is to enable business stakeholders to:
•	Monitor sales performance across product categories and products.
•	Understand customer purchasing trends and preferences.
•	Identify operational inefficiencies through order status tracking.
•	Optimize business strategies with data-driven insights
Data Source
The dataset used for this dashboard originates from an Excel file and includes the following fields:
•	Product Data: Product Name, Category, Subcategory, Price, Size, Weight.
•	Order Data: Order ID, Customer ID, Order Date, Status, Quantity, Total, Payment Method.
Purpose of slicers and filters
The dashboard includes slicers and filters to improve interactivity and user experience. These tools allow users to dynamically explore the data based on specific criteria:
Product Size (Slicers): Filter sales data by product sizes (Small, Medium, Large) are used in this dashboard. We can also add some slicers below depending on the problem we would like to address:
1.	Order Status (Slicers): View order quantities and sales based on order statuses (Shipped, Processing, Cancelled).
2.	Date Range (Filters): Narrow down sales trends over a specific period.
3.	Payment Method (Slicers): Analyze sales performance based on payment preferences (e.g., Credit Card, PayPal).
Findings 
1.	Top-Selling Categories and Revenue Breakdown:
•	The "Sum of Order Total by Product Category" bar chart shows that Mountain Bikes generated the highest revenue at $101,000, followed by Road Bikes at $96,000.
•	Categories like Touring Bikes, E-Bikes, and others contributed significantly less, with revenue as low as $1,000 for Kids Bikes.
•	This indicates that Adventure Works’ core revenue driver lies in the Mountain and Road Bike categories, which could inform inventory prioritisation and marketing strategies.
2.	Product Performance and Customer Preferences:
•	The "Sum of Order Total by Product Name" pie chart complements the category-level analysis by diving into individual product performance.
•	The AeroSpeed 1000 product alone accounted for $17,000 (22.28%) of total sales, followed by the E-TrailBlazer 1000 at $13,000 (16.98%).
•	These findings suggest that the success of specific products drives the broader success of their categories. Combining this with product category data gives a granular and high-level perspective on sales.
3.	Order Trends Over Time:
•	The "Sum of Order Total by Year, Quarter, Month, and Day" line chart reveals fluctuations in daily sales, with noticeable peaks in February and mid-March.
•	By overlaying time-based sales data with product-level performance, managers can correlate sales spikes with campaigns, seasonal trends, or promotions.
4.	Operational Insights – Order Status:
•	The "Sum of Order Quantity by Order Status" donut chart indicates that:
	72 orders (46.15%) were successfully shipped,
	48 orders (30.77%) are still in processing, and
	36 orders (23.08%) were canceled.
•	The significant proportion of "Processing" and "Cancelled" orders points to potential inefficiencies or areas for process improvement in the order management pipeline.
•	This insight connects to the time-based sales trends: delays in order processing might impact sales peaks.
5.	Payment Preferences and Customer Insights:
•	The "Sum of Order Total by Payment Method" bar chart reveals that customers overwhelmingly prefer using Credit Cards ($168,000) compared to PayPal ($127,000).
•	Combined with the Customer Demographics Table, we see that top customers (e.g., Customer ID 3083, contributing $16,800) might influence payment preferences. Identifying such patterns can help create customer-focused strategies.
6.	Interconnected Visualizations for Deeper Analysis:
•	Slicers, such as Order Status, allow users to filter across all visualizations, offering contextualized insights. For example, selecting “Processing” in the slicer reveals which products or categories are most affected by delays, as seen in the bar and pie charts.
•	Time-based filters on the line chart align daily or monthly trends with specific product performance, enhancing the narrative for decision-making.
Conclusion 
1.	Revenue Drivers:
•	The dashboard reveals that Mountain Bikes and Road Bikes are the most significant contributors to overall revenue, accounting for more than $197,000 (66.7%) of total sales.
•	Managers should focus on boosting inventory, promotions, and marketing around these categories to maximize revenue.
2.	Customer and Product Insights:
•	High-performing products like AeroSpeed 1000 and E-TrailBlazer 1000 indicate strong customer demand.
•	However, underperforming categories, such as Kids Bikes ($1,000) and Hybrid Bikes ($8,000), highlight areas where demand is low or marketing efforts need enhancement.
3.	Operational Efficiency:
•	The substantial number of Processing (30.77%) and Cancelled (23.08%) orders suggests inefficiencies in order management, which could lead to missed revenue opportunities.
•	Improving these processes, such as better stock management or quicker processing, can convert more orders to the “Shipped” status and reduce cancellations.
4.	Payment Preferences:
•	With Credit Cards dominating at 57% of total revenue, focusing on secure and seamless credit card payment systems is essential for customer retention.
•	Customers who prefer PayPal (accounting for 43%) can be targeted with PayPal-exclusive promotions to increase adoption.
5.	Integrated Insights for Strategic Planning:
•	The connections between visualizations, such as time-based trends (line chart) and product performance (bar and pie charts), provide a holistic view of sales.
•	By using slicers like Product Size or Order Status, managers can drill down into specific operational issues or seasonal patterns, tailoring solutions to real-time data.
6.	Future Directions:
•	Adventure Works can leverage these insights to enhance marketing strategies, streamline operations, and prioritize high-performing products.
•	Additionally, addressing operational bottlenecks, such as order processing delays, can lead to significant improvements in overall sales performance.
Future Enhencement
•	Add geographic visualizations for location-based insights.
•	Include predictive analytics using machine learning.
•	Develop an automated data update process for real-time insights.


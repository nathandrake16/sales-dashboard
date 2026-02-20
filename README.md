# sales-dashboard

## 🛍️ E-Commerce Sales Insights: India Retail Performance Dashboard
An interactive Power BI dashboard designed to track and analyze e-commerce sales across various states in India, focusing on profitability, customer segmentation, and regional performance.

## 2. Short Description / Purpose
The E-Commerce Sales Insights Dashboard is a comprehensive analytical tool built to monitor key performance indicators (KPIs) for an Indian retail dataset. It allows stakeholders to visualize sales trends, identify high-profit regions (like Maharashtra and Madhya Pradesh), and understand consumer behavior across different product categories (Clothing, Electronics, and Furniture) and payment methods.

## 3. Tech Stack
The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – Used for report authoring and creating the interactive canvas.

📂 Power Query – Utilized for cleaning and merging the Orders and Details datasets.

🧠 DAX (Data Analysis Expressions) – Implemented for calculated measures such as Total Profit, Total Quantity, and dynamic year-over-year filtering.

📝 Data Modeling – Established a 1-to-Many relationship between the Orders table (Order ID) and the Details table to enable seamless cross-filtering.

📁 File Format – .pbix for the development file and .png for the README preview.

## 4. Data Source
The data is derived from two primary internal datasets:

Orders.csv: Contains transaction headers including Order ID, Order Date, Customer Name, State, and City.

Details.csv: Contains line-item specifics including Amount, Profit, Quantity, Category, Sub-Category, and Payment Mode.

Geographic Scope: Covers major Indian states including Maharashtra, Madhya Pradesh, Uttar Pradesh, and Delhi.

## 5. Features / Highlights
• Business Problem
  Retail managers often struggle to identify which specific regions or product sub-categories are driving losses. Without a centralized view, it is difficult to determine if a dip    in performance is due to a specific payment method (like COD returns) or a lack of demand in certain states.

• Goal of the Dashboard
  To deliver an interactive visual tool that:

  Tracks monthly profit fluctuations.

  Identifies the most profitable customers and regions.

  Breaks down sales performance by product category and sub-category.

  Analyzes the preferred payment methods used by customers.

• Walkthrough of Key Visuals
  KPI Cards (Top Ribbon): Displays "Amount" (Sales), "Profit," "Quantity," and "Average Price" for an instant health check of the business.

  Profit by Month (Bar Chart): A monthly breakdown showing seasonal peaks (e.g., significant growth in the latter half of the year).

  Profit by State (Stacked Bar Chart): Compares states like Maharashtra and Madhya Pradesh to pinpoint high-value geographical markets.

  Sales by Customer (Horizontal Bar Chart): Lists top individual contributors to revenue (e.g., Harivansh, Madhav).

  Quantity by Category (Donut Chart): Shows the volume distribution across Clothing (63%), Electronics (21%), and Furniture (16%).

  Quantity by Payment Mode (Pie Chart): Visualizes the dominance of COD (Cash on Delivery) at 44%, followed by UPI and Credit Cards.

  Quantity by Sub-Category (Bar Chart): Drills down into specific items like Saree, Hankerchief, and Stoles to see what's moving fastest.

• Business Impact & Insights
  Inventory Optimization: Seeing that "Clothing" (specifically Sarees and Hankerchiefs) makes up the bulk of quantity allows for better stock planning.

  Regional Strategy: Maharashtra is identified as the leading profit generator; marketing spend can be doubled down here.

  Payment Trends: With 44% of orders being COD, the business can implement strategies to incentivize digital payments (UPI/Credit Card) to reduce RTO (Return to Origin) risks.

  Customer Loyalty: Identifying top customers allows for targeted "VIP" discount campaigns to improve retention.

## 6. Screenshots / Demos
(https://github.com/nathandrake16/sales-dashboard/blob/main/Sales%20Dashboard.png)

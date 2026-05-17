**Shopping Behaviour Analysis: Tablue**


Problem Statement
In the context of retail customer analytics, how can the utilization of Tableau Public facilitate a comprehensive examination of customer shopping behavior and purchasing trends?
This inquiry seeks to leverage Tableau Public’s visual analytics capabilities to uncover and illustrate the patterns, relationships, and business insights hidden within customer shopping data. Through effective dashboard design, this study aims to analyze customer demographics, product demand, purchasing frequency, seasonal trends, geographic sales patterns, and customer satisfaction, thereby enhancing the depth and insightfulness of the analysis.

Dataset Selection
For this Data Visualization project, we have chosen the Shopping Behavior Dataset. This dataset provides a comprehensive snapshot of various customer shopping attributes, including demographic details, purchasing behavior, product preferences, sales amounts, and customer review ratings.
The dataset is ideal for conducting an in-depth exploration of customer behavior and deriving actionable business insights through interactive dashboard visualizations.

Why Customer Shopping Behavior
Customer shopping behavior analysis is essential for understanding how customers interact with products and services, how they make purchasing decisions, and what factors influence overall business performance.

Understanding customer shopping behavior helps businesses:
Identify high-value customer segments
Understand purchasing differences across age and gender
Determine top-performing product categories
Analyze seasonal demand fluctuations
Evaluate geographic sales performance
Improve customer satisfaction and product quality
Support personalized marketing and strategic decision-making

Dataset Details
Dataset Name: Shopping Behavior Dataset
Tool Used: Tableau Public
Description: The dataset contains customer shopping behavior information, including customer demographics, product categories, purchase amount, purchase frequency, seasonal preferences, customer review ratings, subscription status, payment methods, and geographic location. Each record represents an individual customer transaction.

Key Attributes
Customer ID: Unique identifier for each customer
Age: Age of the customer
Gender: Gender of the customer
Product Category: Category of purchased product
Purchase Amount (USD): Amount spent on the purchase
Purchase Frequency: Frequency of customer purchases
Season: Season during which the purchase occurred
Review Rating: Customer satisfaction score
Subscription Status: Indicates active customer subscription
Payment Method: Method used for payment
Location: Geographic location of the customer

Problem Areas to Explore
What is the overall business performance?
Which customer groups contribute the most to revenue?
How do age and gender influence purchasing behavior?
Which product categories are purchased most frequently and contribute the most to total sales?
How does seasonal demand affect inventory planning?
Which geographic locations generate the highest revenue?
How satisfied are customers across different product categories?

Divide the visualization findings into 4 categories
Overview of Shopping Behavior
This section provides a high-level summary of overall business performance through KPI indicators.
The dashboard includes:
Total Sales, representing overall financial performance
Customer Count, indicating the size of the customer base
Average Rating, reflecting overall customer satisfaction
Together, these KPIs provide an immediate snapshot of business health and overall performance.

Customer and Product Analysis
Sales Trend by Age Group and Gender (Line Chart)
This visualization analyzes how sales vary across different age groups and between male and female customers.
The horizontal axis represents Age Groups, while the vertical axis shows Sales Amount, with separate colored lines used to distinguish gender.
Insights observed:
Male customers aged 45 to 50 generate the highest overall sales.
Female customers aged 25 to 30 contribute the highest sales among female customers.
These findings can support targeted marketing strategies aimed at high-value customer segments.

Category-wise Purchase Frequency (Stacked Bar Chart)
This visualization compares purchase frequency and sales amount across product categories.
The horizontal axis represents Purchase Frequency, while the vertical axis shows Sales Amount, with bars segmented by Product Category.
Insights observed:
Clothing has the highest purchase frequency.
Clothing also generates the highest sales amount.
Customers purchasing every three months contribute significantly to this demand.
This indicates strong and consistent customer demand, making Clothing the most important product category for the business.

Category-wise Sales Contribution (Pie Chart)
This visualization shows the proportional contribution of each product category to total revenue.
Insight observed:
Clothing contributes 44.73% of total sales, making it the primary revenue-driving category.
This reinforces the importance of prioritizing this category for business growth.

Pricing and Seasonal Analysis
Seasonal Restocking Analysis (Bar Chart)
This visualization examines purchasing behavior across seasons and helps identify restocking priorities.
The horizontal axis represents Season, while the vertical axis shows Purchase Count.
Insights observed:
Accessories peak during Fall
Clothing peaks during Spring
Footwear shows highest demand during Spring
Outerwear peaks during Fall
These patterns help businesses improve demand forecasting and optimize stock levels throughout the year.

Geographic and Customer Satisfaction Analysis
Location-wise Sales Performance (Geographic Map)
This map visualizes sales distribution across different locations and helps identify high-performing regions.
Insight observed:
California generates the highest sales, with a sales amount of 5605.
This information can support regional marketing decisions and resource allocation.

Customer Satisfaction by Category (Treemap)
This treemap compares average review ratings across product categories using a blue color gradient.
Darker blue indicates higher customer satisfaction, while lighter blue indicates lower ratings.
Insights observed:
Footwear has the highest customer satisfaction
Clothing has the lowest average rating
This finding is significant because Clothing generates the highest sales but receives the lowest ratings, suggesting an opportunity to improve product quality and customer experience.

How to proceed with the dashboard
1. Data Cleaning
Begin by reviewing and preparing the raw dataset in Tableau Public.
The following steps were performed:
Connected the Excel dataset
Reviewed and cleaned all available fields
Renamed columns for better clarity
Verified data consistency and formatting
These steps ensured the dataset was accurate and ready for visualization.

2. Data Transformation
Generate supplementary calculated fields using existing data attributes.
The extra columns created include:
Total Sales
Customer Count
Average Review Rating
Additionally, Tableau initially interpreted Age as a continuous numerical measure. To improve age-based analysis, Age Group bins were created, allowing more meaningful comparisons across grouped age ranges.
These transformed fields provided better analytical depth and improved visualization effectiveness.

3. Tableau Desktop/Tableau Public/PowerBI
Employ Tableau Public to build an interactive and user-friendly dashboard.
The dashboard includes the following visualizations and features:
KPI Cards
Line Chart
Stacked Bar Chart
Pie Chart
Bar Chart
Geographic Map
Treemap
Interactive Filters
Highlight Actions
Dashboard Interactivity
Additional interactive filters implemented include:
Sales Amount Range Filter for dynamic sales range analysis
Highlight Category Filter for focused category analysis
Location Filter for location-specific insights
These features transform the dashboard into an interactive decision-support tool rather than a static report.



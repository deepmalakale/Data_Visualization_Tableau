# 🛍️ Shopping Behavior Analysis Dashboard using Tableau Public

## 📌 Project Overview

This project presents an **interactive Shopping Behavior Analysis Dashboard** developed using **Tableau Public** to analyze customer purchasing patterns and uncover actionable business insights.

The dashboard transforms raw customer shopping data into meaningful visual stories, helping businesses understand customer demographics, product demand, seasonal trends, geographic sales performance, and customer satisfaction.

Through this project, I analyzed purchasing trends, product performance, seasonal demand, geographic sales patterns, and customer satisfaction. The dashboard was visually designed to communicate business insights effectively through interactive data storytelling.

Some of the key business questions this project aims to answer include:

- What is the overall business performance?
- Which customer group contributes the most?
- How do age and gender influence purchasing behavior?
- Which product category generates the highest sales?
- How does seasonal demand affect inventory planning?
- Which locations perform best?
- How satisfied are customers across product categories?

Answering these questions can help businesses improve customer targeting, optimize inventory management, refine marketing strategies, and enhance the overall customer experience.

---

## 📊 Tableau Dashboard Link

🔗 **View Interactive Dashboard on Tableau Public**

<a href="https://public.tableau.com/views/ShoppingBehaviourAnalysis_17706361812850/ShoppingBehaviourAnalysis?:language=en-US&:sid=&:display_count=n&:origin=viz_share_link" target="_blank">
  <img src="https://cdn.worldvectorlogo.com/logos/tableau-software.svg" alt="Tableau Logo" width="35"/> Open Tableau Dashboard
</a>

---

## 🎥 Project Walkthrough Video

Watch the complete explanation and demonstration of the Tableau dashboard here:

🔗 **Project Presentation Video**

<a href="https://drive.google.com/file/d/1OGu9GYvqvHBY-vkZaIC_YnR0zzEPkDxO/view?usp=sharing" target="_blank">
📹 Watch Dashboard Explanation Video
</a>

---

# 🎯 Problem Statement

In the context of retail customer analytics, how can **Tableau Public** facilitate a comprehensive examination of customer shopping behavior and purchasing trends?

This project leverages Tableau’s visual analytics capabilities to uncover hidden patterns, relationships, and business insights within customer shopping data through effective and interactive dashboard design.

---

# 📂 Dataset Information

### **Dataset Name:** Shopping Behavior Dataset

This dataset contains detailed customer shopping information, including:

- 👤 Customer demographics
- 🛒 Product categories
- 💰 Purchase amount
- 🔁 Purchase frequency
- 🌤️ Seasonal preferences
- ⭐ Customer review ratings
- 💳 Payment methods
- 📍 Geographic locations
- 🔔 Subscription status

Each row represents an individual customer transaction.

The dataset contains detailed shopping behavior information such as customer ID, age, gender, product category, purchase amount, purchase frequency, season, review rating, subscription status, payment method, and location, providing a comprehensive foundation for customer behavior analysis.

---

# ❓ Why Customer Shopping Behavior Analysis?

Understanding customer shopping behavior helps businesses:

✅ Identify high-value customer segments  
✅ Analyze purchasing differences across age and gender  
✅ Determine top-performing product categories  
✅ Understand seasonal demand fluctuations  
✅ Evaluate regional sales performance  
✅ Improve customer satisfaction and product quality  
✅ Support personalized marketing strategies  

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|---------|
| 📊 Tableau Public | Dashboard creation & visualization |
| 📁 Excel Dataset | Data source |
| 🧹 Data Cleaning | Field validation and formatting |
| 🔄 Data Transformation | Calculated fields & age grouping |

---

# ⚙️ Project Workflow

## 1️⃣ Data Cleaning

The following preprocessing steps were performed:

- Connected the Excel dataset
- Reviewed all fields
- Cleaned inconsistent values
- Renamed columns for clarity
- Verified data formatting

As part of data preparation, I reviewed and cleaned all fields, renamed columns for better clarity—for example, changing **“Amount in USD”** to **“Sales Amount”** for improved readability. I also verified that all data types were correctly assigned to their respective fields and checked for the presence of null values to ensure data consistency and accuracy before visualization.

---

## 2️⃣ Data Transformation

Additional calculated fields were created:

- **Total Sales**
- **Customer Count**
- **Average Review Rating**

### 📌 Age Group Binning

Since Tableau initially interpreted **Age** as a numerical measure, age bins were created for better grouped analysis and clearer visualization.

These preparation steps ensured that the dataset was properly organized and ready for analysis. The calculated fields were created to support overall business performance measurement and improve analytical capabilities across different visualizations.

---

## 3️⃣ Dashboard Development

The interactive dashboard includes:

- 📈 KPI Cards
- 📉 Line Chart
- 📊 Stacked Bar Chart
- 🥧 Pie Chart
- 📅 Seasonal Bar Chart
- 🗺️ Geographic Map
- 🌳 Treemap
- 🎛️ Interactive Filters
- ✨ Highlight Actions

To make the dashboard more interactive and user-friendly, several Tableau interactive features were implemented:

- **Sales Amount Range Filter** – allows users to adjust minimum and maximum sales values using a range slider, dynamically updating all visualizations.
- **Highlight Category Filter** – enables users to select a specific category and highlight it across all charts for focused analysis.
- **Location Filter** – a dropdown filter allowing users to select a specific state and view location-specific insights.

These features transform the dashboard into an interactive decision-support tool.

---

# 🔍 Dashboard Insights

## 1. Overview of Shopping Behavior 📌

High-level business performance indicators:

- 💰 **Total Sales** → Overall financial performance
- 👥 **Customer Count** → Size of customer base
- ⭐ **Average Rating** → Customer satisfaction level

The dashboard begins with **three key KPI indicators** that provide a quick summary of overall business performance.

- **Customer Count** shows the size of the customer base.
- **Total Sales** reflects the overall financial performance of the business.
- **Average Rating** indicates overall customer satisfaction.

Together, these KPI indicators provide a quick overview of overall business health, showing that the business serves approximately **4,000 customers**, generates total sales of around **₹2,33,000**, and maintains a strong average customer rating of **4 out of 5**.

These KPIs help users immediately understand the scale of the business, its financial success, and customer satisfaction levels before exploring deeper analytical insights.

---

## 2. Customer & Product Analysis 👤🛍️

### 📈 Sales Trend by Age Group and Gender

**Insights:**

- Male customers aged **45–50** generate the highest sales
- Female customers aged **25–30** generate the highest female sales

A **line chart** was selected for this analysis because it is ideal for identifying trends across ordered age groups.

The horizontal axis represents **Age Groups**, while the vertical axis represents **Sales Amount**, with separate lines representing male and female customers for easy comparison.

These insights can support targeted marketing strategies focused on high-value customer segments.

---

### 📊 Category-wise Purchase Frequency

**Insights:**

- 👕 Clothing has the highest purchase frequency
- 💰 Clothing generates the highest sales
- 🔁 Customers purchasing every **3 months** contribute significantly

A **stacked bar chart** was chosen because it effectively displays two trends simultaneously—purchase frequency and product category contribution.

The analysis also shows that **bi-weekly purchase frequency generates higher sales compared to weekly purchases**, indicating that customers purchasing at bi-weekly intervals contribute significantly to revenue.

These insights can help improve inventory planning and focus targeted marketing on frequently purchased and highest-revenue products.

---

### 🥧 Category-wise Sales Contribution

**Insight:**

- 👕 **Clothing contributes 44.73%** of total sales

A **pie chart** was used because it is ideal for showing proportional contribution of each product category to total revenue.

Additionally, interactive hover functionality allows users to view detailed information such as category name, percentage contribution, and total sales amount, making the visualization more informative and user-friendly.

Since Clothing contributes the highest proportion of total sales, inventory planning for this category should be strongly prioritized to maximize revenue.

---

## 3. Pricing & Seasonal Analysis 🌤️📦

### 📅 Seasonal Restocking Analysis

**Insights:**

- 🎒 Accessories peak during **Fall**
- 👕 Clothing peaks during **Spring**
- 👟 Footwear demand peaks during **Spring**
- 🧥 Outerwear peaks during **Fall**

A **bar chart** was selected for this analysis because it provides a clear comparison of purchase volumes across different seasons and product categories.

The horizontal axis represents product categories further divided by seasons, while the vertical axis represents purchase count.

These insights can support more accurate demand forecasting and smarter inventory planning by allowing businesses to increase stock availability just before peak seasons and reduce stock during lower-demand periods.

---

## 4. Geographic & Customer Satisfaction Analysis 🌍⭐

### 🗺️ Location-wise Sales Performance

**Insight:**

- 📍 **California** generates the highest sales (**5605**)

A **geographic map** was used because it is the most effective way to visualize sales distribution across regions.

The chart includes interactive features such as **zoom in/zoom out** and hover details that display state names along with sales amounts for better regional analysis.

These insights can help businesses optimize regional marketing strategies, improve resource allocation, and identify opportunities for expansion in lower-performing states.

---

### 🌳 Customer Satisfaction by Category

**Insights:**

- 👟 **Footwear** has the highest customer satisfaction
- 👕 **Clothing** has the lowest average rating

⚠️ Clothing generates the highest sales but receives the lowest ratings, highlighting an opportunity for product quality improvement.

A **treemap** was selected because it effectively compares product popularity and product quality in a single view.

The size of each block represents product popularity, while color intensity reflects average customer review ratings—darker shades indicate higher satisfaction, while lighter shades indicate lower satisfaction.

This contrast between Clothing’s high sales and low ratings highlights an important opportunity for improvement in product quality and customer experience.

---

# 💡 Key Business Takeaways

✔️ Identify high-value customer segments  
✔️ Prioritize top-performing product categories  
✔️ Improve inventory planning through seasonal analysis  
✔️ Optimize regional marketing efforts  
✔️ Enhance customer satisfaction in low-rated categories  

---

# 🚀 Conclusion

This Tableau dashboard transforms raw shopping data into meaningful business intelligence.

By combining multiple visualizations with interactive filters and highlight actions, the dashboard serves as an effective **decision-support tool**, enabling smarter, data-driven business decisions.

This project demonstrates how data visualization can transform raw data into meaningful business intelligence.

It strengthened my technical Tableau skills as well as my ability to communicate insights effectively through data visualization and storytelling.

By combining multiple visualizations, interactive filters, and analytical techniques, this dashboard provides valuable support for smarter, data-driven business decisions.

---

## 🙌 Thank You

Thank you for reviewing this project!  
If you found it interesting, feel free to ⭐ the repository.

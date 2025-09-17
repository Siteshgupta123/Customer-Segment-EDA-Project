# Sales & Customer Analytics Dashboard
#### 📊 Project Overview
**This project transforms a raw, unstructured sales dataset into a powerful and insightful business intelligence tool. The objective was to design a comprehensive dashboard that provides actionable insights into sales performance and customer behavior. The final dashboard, built in Power BI, serves as a single source of truth for key metrics, enabling a data-driven approach to strategic planning and decision-making.**

-------------------
## Key Metrics & Impact:

- **Total Revenue**: Identified over **$8.5 million** in total sales revenue.
- **Customer Base**: Analyzed data for over **4,000 unique customers**.
- **Transactions**: The analysis was performed on a dataset containing **363,119** sales transactions.
- **Top Product Performance**: Pinpointed the **top 10 products**, which accounted for a significant portion of total revenue, with the top product alone generating over **$168,000**.

## 💡 Problem Solved & Business Objective:
**The Problem**: The business was operating with a raw, unstructured sales dataset of over **363,000** rows that contained data quality issues, inconsistent data types, and lacked calculated metrics. This made it impossible to get a clear picture of business health, track performance over time, or understand customer dynamics.

### The Objective:
- **Data Quality**: Clean and prepare the raw data for reliable analysis.
- **KPI Development**: Create key performance indicators (KPIs) and metrics from the ground up to measure success.
- **Dashboard Design**: Build a dynamic, two-page dashboard in Power BI that is easy to navigate and understand.
- **Actionable Insights**: Deliver clear, actionable insights to help stakeholders make informed decisions on sales, marketing, and customer strategy.
------------------------
## 🛠️ Data Engineering & Transformation
A rigorous data cleaning and transformation process was undertaken to ensure accuracy and prepare the data for visualization.
- **Data Cleaning**: The redundant Unnamed: 0 index column was identified and removed.
- **Data Type Correction**: The InvoiceDate column was converted from a text format to a datetime data type for time-series analysis. The CustomerID column was correctly formatted from a float to an integer.
- **Calculated Metrics**: New columns and measures were created using DAX (Data Analysis Expressions) to enrich the data and provide deeper insights:
  - **Average Order Value (AOV)**: Calculated as total sales divided by the number of unique orders.
  - **Sales Growth Rate %**: A critical measure for tracking month-over-month business momentum.
  - **Customer Lifetime Value (CLV)**: A forward-looking metric that estimates the total value a customer will bring to the business over time.
  - **Descriptive Customer Segments**: The existing numerical segments (e.g., 0, 1, 2) were mapped to business-friendly names like "Champions," "At-Risk," and "Lost Customers" to enable targeted marketing.
---------------

## Dashboard Features
### Navigation
The dashboard is designed with two distinct pages:
- **Sales Performance Overview**: A landing page with high-level KPIs and trends.
- **Customer & Product Deep Dive**: A secondary page for in-depth analysis.
This is supported by clear navigation buttons that allow users to move between the pages easily.

### Dynamic Slicers
Slicers are included to allow users to filter data and customize their views.
- **Date Slicer**: Filter all visuals by Year, Quarter, and Month using a hierarchical dropdown.
- **Country & Product Slicers**: Allow users to focus on sales performance in a specific country or for a particular product.
- **Segment Slicer**: Filter the dashboard by customer segments (e.g., "Champions," "At-Risk").

### User-Friendly Controls
- **Reset Button**: A dedicated "Clear All Filters" button is included to reset the dashboard to its original state, ensuring accurate reporting and a smooth user experience.
- **Interactive Tooltips**: Users can hover over any visual to see additional details without cluttering the screen. This adds another layer of depth to the data.

## 📊 Dashboard Visualizations & Insights
The final dashboard is a two-page report designed for a comprehensive analytical experience.

### Page 1: Executive Sales & Performance Dashboard
This page provides a high-level overview of the business's health.
#### Preview:
<img width="1531" height="863" alt="image" src="https://github.com/user-attachments/assets/d11ce258-09fc-4114-bf81-e93b06f3b2a3" />

- **Core KPIs**: Four prominent KPI cards instantly display:
  - Total Sales
  - Total Orders
  - Total Customers
  - Average Order Value (AOV)
- **Sales Trends**: A line chart visualizes the Monthly Sales Trend, identifying a significant sales peak in November 2011, which helps in future forecasting and planning.
- **Geographic Analysis**: A bar chart of Sales by Country reveals that the United Kingdom is the dominant market, generating over $6.6 million in sales.
- **Product Analysis**: A bar chart displays the Top 10 Selling Products, with the top product, PAPER CRAFT, LITTLE BIRDIE, generating over $168,000 in revenue, a key insight for inventory management.
-------------------------
### Page 2: Customer & Product Deep Dive
This page offers granular, actionable insights for strategic decision-making.
 #### **Preview**:
<img width="1537" height="861" alt="image" src="https://github.com/user-attachments/assets/edd45b71-9e01-47bb-8f55-53116ecbb0f6" />

- **Customer Segmentation**: A visual displays the distribution of customers across our descriptive segments, enabling highly targeted marketing campaigns.
- **Time-Based Analysis**: Bar charts of Sales by Weekday and Sales by Hour pinpoint peak sales times, revealing that Thursdays and 12 PM are the busiest periods, which is invaluable for optimizing staffing and marketing schedules.
- **Product Performance Matrix**: A scatter plot of Quantity Sold vs. Unit Price reveals which products are high-volume, low-margin versus low-volume, high-margin, guiding inventory and pricing strategies.
- **Top Customer Analysis**: A bar chart lists the Top 10 Customers by Revenue, allowing for the identification of high-value clients.

----------------------
## Thank You! 💙

Thanks for checking out my project! If you found it useful, please consider:  
[![GitHub stars](https://github.com/Siteshgupta123)] 
⭐ **Starring** the repo  
🐛 **Reporting** issues  
🛠 **Contributing** improvements  

Coded with ❤️ by **Sitesh Gupta**  
🔗 www.linkedin.com/in/guptasitesh | 💌 Email-guptasitesh05@email.com

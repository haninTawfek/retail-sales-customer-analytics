# 🛍️ Retail Sales & Customer Analytics Dashboard

## 📌 Project Overview

This project presents an end-to-end **Retail Sales and Customer Analytics solution** developed entirely using **Microsoft Excel**, leveraging **Power Query** for data preparation and transformation, **Power Pivot** for data modeling, **DAX** for analytical calculations, and interactive dashboards for business intelligence and decision-making.

The main objective of the project is to analyze **sales performance, profitability, customer behavior, product performance, store performance, geographic trends, inventory efficiency, and membership patterns** to identify key business opportunities and provide actionable strategic recommendations.

## 🛠️ Tools & Technologies

* **Microsoft Excel**
* **Power Query** – Data Cleaning & Transformation
* **Power Pivot** – Data Modeling & Relationships
* **DAX** – Calculated Measures & KPIs
* **Pivot Tables & Pivot Charts**
* **Interactive Dashboards**
* **Data Visualization & Business Intelligence**

# 🔄 Project Workflow

The project was developed through the following stages:

## 1️⃣ Data Preparation & Cleaning

The raw data was prepared and transformed using **Power Query** to ensure data quality and consistency before analysis.

The main data preparation and transformation tasks included:

* Cleaning and transforming the raw datasets.
* Handling missing and inconsistent values.
* Creating a **Full Name** column by combining **First Name** and **Last Name**.
* Calculating **Age** from the customer's **Birth Date**.
* Creating **Age Groups** to segment customers based on their age.
* Analyzing customer income by identifying:
  * Minimum Income
  * Maximum Income
  * Average Income
* Creating the **Cost-to-Price Ratio** to evaluate product pricing and cost efficiency.
* Creating **Weight Groups** based on product weight.
  
* Calculating **Unit Profit**:
`Unit Profit = Product Retail Price - Product Cost`

* Calculating **Days to Sell**:
`Days to Sell = Transaction Date - Store Date`

* Calculating **Sales Amount**:
`Sales Amount = Quantity × Product Retail Price`

* Calculating **Profit Amount**:
`Profit Amount = Unit Profit × Quantity`

* Creating additional calculated fields and categories required for analysis and visualization.

## 2️⃣ Data Modeling

After preparing and cleaning the data, a data model was created using **Power Pivot**.

The modeling process included:

* Establishing relationships between relevant tables.
* Creating calculated columns and measures using **DAX**.
* Building KPIs to monitor overall business performance.
* Creating measures to analyze sales, profitability, customer behavior, product performance, and inventory efficiency.

The final data model was used as the foundation for the interactive dashboards and business analysis.

# 📊 Dashboard Preview

The project includes interactive dashboards designed to provide a comprehensive view of business performance across different analytical perspectives.

### 🏠 Overall Business Performance

This dashboard provides a high-level overview of the company's performance, including key strategic insights, sales trends, product profitability, store performance, and future sales forecasts.

<img width="1032" height="556" alt="Screenshot 2026-07-26 203542" src="https://github.com/user-attachments/assets/eac17139-8acb-44cc-9ca3-626b4e4d9af9" />

### 👥 Customer Analysis

This dashboard focuses on customer behavior and purchasing patterns, analyzing membership tiers, customer occupations, customer acquisition trends, and identifying the highest-value customers.
<img width="1317" height="620" alt="Screenshot 2026-07-26 203410" src="https://github.com/user-attachments/assets/ebdbe157-df04-4814-8ba7-0d24f23d4e62" />


### 🌍 Geographic Analysis

This dashboard analyzes sales and profitability across different countries, regions, and states, helping identify the company's strongest geographic markets.
<img width="1007" height="612" alt="Screenshot 2026-07-26 203501" src="https://github.com/user-attachments/assets/3226792d-e390-4f9c-b36a-acfc15682f56" />


### 📦 Product Analysis

This dashboard evaluates product categories and individual products based on profitability, inventory holding time, days to sell, and recyclability.

<img width="1401" height="615" alt="Screenshot 2026-07-26 203517" src="https://github.com/user-attachments/assets/e2fbe9cb-5f37-4cd9-9fd4-0329c7a36f71" />


### 📈 Sales & Customer Insights

This dashboard combines key performance indicators with sales trends, customer demographics, store type performance, and membership behavior.
<img width="1140" height="620" alt="Screenshot 2026-07-26 202712" src="https://github.com/user-attachments/assets/7ea48824-f16b-4a9f-a2a8-4deea86428e2" />

# 🔍 Key Insights

### 📈 1. Strong Year-End Revenue Surge

Sales and profits experienced a significant increase during **November and December**, indicating strong seasonal demand toward the end of the year.

This suggests that the business should prepare inventory and marketing campaigns ahead of the year-end peak season.

### 📦 2. Heavy Products Drive Profitability

The **Heavy product category** generated the largest share of total profit, contributing approximately **37% of total profits**.

**Hermanos Green Pepper** was identified as one of the strongest individual products in terms of profitability.

### 🏪 3. Supermarkets Are the Main Revenue Drivers

**Supermarket and Deluxe Supermarket** store types generated the majority of overall sales.

This indicates that these channels play a critical role in the company's revenue generation and should remain a key focus for future growth strategies.

### 🇺🇸 4. USA Is the Primary Market

The **USA** significantly outperformed Mexico and Canada in terms of sales volume, making it the company's primary geographic market.

Within the regional analysis, **North West** generated the highest profit among the analyzed regions.

### 👥 5. Bronze Members Represent the Largest Customer Segment

**Bronze cardholders** account for the largest share of customer sales volume, with relatively balanced contributions from male and female customers.

This suggests that the Bronze membership tier represents a significant opportunity for customer retention and upselling.

### 💼 6. Professional & Skilled Manual Customers Are High-Value Segments

**Professional and Skilled Manual** customer groups contribute more than **60% of total sales and profits**, making them highly valuable customer segments.

### 👤 7. High-Value Customers

The analysis identified the highest-value customers based on total purchase value.

**Ida Rodriguez** was identified as the top customer by overall purchases, followed closely by **James Horvat**.

This highlights the importance of identifying and retaining high-value customers through targeted loyalty strategies.


### ⏳ 8. Inventory Holding Time

Products in the **Heavy category** tend to remain in inventory for longer periods, with an average inventory retention time of approximately **7 days**.

This may indicate an opportunity to optimize inventory planning and supply chain efficiency.

### 📊 9. Customer Acquisition Fluctuation

New customer acquisition increased significantly between **1991 and 1993**, followed by a noticeable decline in **1994**.

This indicates a potential need to strengthen customer acquisition and marketing strategies.


### 💰 10. Income Does Not Directly Predict Sales

The analysis suggests that **higher customer income does not necessarily lead to higher sales volume**.

Therefore, income alone should not be used as the primary factor for customer targeting and segmentation.

# 🎯 Strategic Recommendations

### 📦 1. Optimize Inventory Planning

Increase stock levels for high-performing **Heavy category products** before the expected year-end demand surge.

Use historical sales trends to plan inventory purchases ahead of **November and December**.

### 🔄 2. Improve Inventory Turnover

Focus on improving supply chain efficiency for Heavy category products to reduce inventory holding time.

Monitor slow-moving products and optimize stock levels to minimize unnecessary inventory costs.

### 💎 3. Strengthen Customer Loyalty Programs

Develop targeted upgrade incentives to encourage **Bronze members** to move toward higher membership tiers.

Offer personalized benefits and rewards based on customer purchasing behavior.

### 👥 4. Use Balanced Demographic Targeting

Since customer profitability is relatively balanced across genders, marketing campaigns should maintain **gender-neutral targeting** instead of focusing heavily on one gender.

### 🏪 5. Focus on High-Performing Store Types

Prioritize **Supermarket and Deluxe Supermarket** channels because they generate the majority of sales.

Invest in these channels through better product availability, promotions, and customer experience initiatives.

### 🌍 6. Prioritize the USA Market

Since the USA is the primary revenue-generating market, the company should focus on:

* Expanding market presence.
* Improving customer retention.
* Increasing product availability.
* Launching targeted marketing campaigns.

### 💼 7. Target High-Value Customer Segments

Develop personalized marketing campaigns for **Professional and Skilled Manual** customer segments, as they contribute significantly to overall sales and profits.

### 📈 8. Improve Customer Acquisition

The decline in new customer acquisition after 1993 indicates the need for new customer acquisition strategies, including:

* Targeted digital marketing.
* Referral programs.
* Promotional campaigns.
* Membership incentives.

### ⭐ 9. Retain High-Value Customers

Create VIP or loyalty strategies for customers with high purchase values.

Personalized offers and exclusive rewards can help increase customer retention and customer lifetime value.

# 📌 Key Business KPIs

| KPI                            |          Value | Business Insight                                                                                                                    |
| ------------------------------ | -------------: | ----------------------------------------------------------------------------------------------------------------------------------- |
| **Total Sales**                |     **$1.76M** | Indicates a strong overall revenue base generated across products, stores, and geographic markets.                                  |
| **Total Profit**               |     **$1.05M** | Shows strong profitability and highlights the business's ability to convert sales into profit.                                      |
| **Profit Margin**              |     **59.67%** | A high margin indicates strong overall profitability and effective cost management.                                                 |
| **Total Transactions**         |    **269,711** | Reflects a high volume of customer transactions and strong business activity.                                                       |
| **Total Customers**            |     **10,281** | Represents the size of the analyzed customer base and provides a foundation for customer segmentation and loyalty strategies.       |
| **Average Spend per Customer** |    **$171.63** | Indicates the average customer value and helps evaluate customer purchasing behavior.                                               |
| **Average Sales per Store**    | **$73,520.62** | Shows the average revenue contribution of each store and helps compare overall store productivity.                                  |
| **Average Days to Sell**       |  **3.94 days** | Indicates relatively fast product movement, although Heavy products may require additional inventory optimization.                  |
| **Return Rate**                |      **0.29%** | A very low return rate suggests strong customer satisfaction and/or effective product quality.                                      |
| **Recyclable Percentage**      |     **55.96%** | More than half of the analyzed products/materials are recyclable, indicating a positive opportunity for sustainability initiatives. |


# 📂 Project Structure

```text
Retail-Sales-Analytics/
│
├── Final.xlsx
│
├── Screenshots/
│   ├── Overview.png
│   ├── Customer.png
│   ├── Geographic.png
│   ├── Products.png
│   └── Insights.png
│
└── README.md

# 🚀 Conclusion

This project demonstrates an end-to-end **Business Intelligence and Data Analytics workflow using Microsoft Excel**.

By combining **Power Query for data preparation, Power Pivot for data modeling, DAX for analytical calculations, and interactive dashboards for visualization**, the project transforms raw retail data into meaningful business insights.

The analysis provides a comprehensive view of **sales performance, profitability, customer behavior, product performance, inventory efficiency, and geographic trends**, helping decision-makers identify growth opportunities and improve overall business performance.


### 👩‍💻 Skills Demonstrated

**Data Cleaning | Data Transformation | Power Query | Power Pivot | Data Modeling | DAX | KPI Development | Data Visualization | Business Intelligence | Customer Analytics | Sales Analytics | Profitability Analysis | Inventory Analysis | Dashboard Design**

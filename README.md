# 🛒 E-Commerce Business Intelligence Project
### Project Overview

#### 📌 Project Overview
This project was completed as part of a business case where I was hired as a data analyst by XYZ, supporting one of India’s leading online marketplaces. The client wanted to measure, manage, and analyse their business performance with a focus on customer behaviour, seller trends, product popularity, and payment channel insights.

I conducted comprehensive data cleaning, SQL analysis, and interactive dashboarding in Power BI, validated through Excel pivot tables and Power Query.

## Tablem of Contents
- [Dataset](#Dataset)
- [🎯 Business Objectives](#-Business-Objectives)
- [🧰 Tools & Technologies](#-Tools-&-Technologies)
- [📊 Dashboard Overview (Power BI)](#-Dashboard-Overview-(Power-BI))
- [🧮 SQL Analysis Highlights](#-SQL-Analysis-Highlights)
- [🔍 Key Insights](#-Key-Insights)
- [📝 Recommendations](#-Recommendations)
- [🙋‍♂️ About Me](#-About-Me)


### Dataset
 The dataset have 8 tables
  - 1. Customers
  - 2. Orders
  - 3. Products
  - 4. Sellers.
  - 5. Order_Items.
  - 6. Order_review_rating.
  - 7. Order_Payments.  
  - 8. Geo_Locations
   - <a href= "https://github.com/Ansarulh/E-Commerce-Business-Intelligence-Project/blob/main/E-Commerce%20dataset.zip" >Download Dataset


#### 🎯 Business Objectives
The client shared a set of core business questions to address, including (but not limited to):
- How is the business performing in terms of sales, customers, and products?
-	What’s the trend in customer acquisition and retention?
-	Which products/categories are most and least popular?
-	How are customers paying, and what’s their satisfaction level?
-	Can we segment customers and sellers based on revenue?


#### 💼 My Role
As the analyst, I was responsible for turning raw data into actionable insights across SQL Server, Power BI, and Excel. I built an end-to-end solution with clear visuals, KPIs, and business storytelling.


#### 🧰 Tools & Technologies
Tools	
- SQL Server -	Data cleaning, exploratory analysis
  - [Download here](https://www.microsoft.com)
- Power BI - Dashboarding and visual storytelling
   - [Download here](https://www.microsoft.com)
- Excel -	Validation using Pivot Tables, Formulas & Power Query
  - [Download here](https://www.microsoft.com)

### 📊 Dashboard Overview (Power BI)
- <a href = "https://github.com/Ansarulh/E-Commerce-Business-Intelligence-Project/commit/68bdec865228508bc78629670b4002edce852d47" > Download Power BI Dashboard
#### 🟦 Page 1: Executive Summary
##### Key Metrics & Visuals:
•	Revenue by State, Day, Month, Payment Type, Hour.

•	KPIs: Total Revenue (₹13.6M), Quantity, Products, Categories, Locations, AOV, Avg. Rating, Delivery Days.

##### •	💡 Insight: Andhra Pradesh alone contributes ~60% of revenue; most orders are paid via Credit Card.

![Executive Summary ](https://github.com/user-attachments/assets/f9bcc694-b70f-4350-b2ac-24443a1be6a0)

#### 🟨 Page 2: Customer Behaviour Analysis
-	New Customers by Month/Quarter/Year.
-	Revenue by Customer Segment.
-	Avg. Instalments by Segment.
-	Top Product Categories by State.

##### 	💡 Insight: Most customers fall into the <₹1K segment; peak customer acquisition happens in November.

![Customer Behaviour Analysis](https://github.com/user-attachments/assets/999b67e0-a89f-4696-b18c-6468bcddd994)

#### 🟩 Page 3: Product & Seller Insights
-	Product Listings by Category.
-	Revenue & Quantity by Category.
-	Top/Least Rated Categories.
-	Seller Segmentation by Revenue.

##### •	💡 Insight: “bed_bath_table” is the most listed & sold category; 82% of sellers are low performers.
![Product   Seller Insights](https://github.com/user-attachments/assets/45399479-e6bd-478c-a691-19e5e0d0b6aa)


### 🧮 SQL Analysis Highlights
The full SQL work covered:

#### ✅ Data Cleaning
-	Handled nulls, blanks, placeholder values across Customers, Products, Sellers, Orders, Reviews, etc.
-	Replaced #N/A, computed averages and modes for imputation.


#### ✅ Exploratory Analysis
-	High-level metrics (Revenue, Quantity, Products, Categories, Sellers, Locations, Payment Types)
-	Repeat customer behavior, monthly retention
-	Revenue trends by date, day of week, hour, location, category.


#### ✅ Business Questions Addressed
-	Most/least performing products, sellers, and payment types.
-	Segmentation of customers/sellers based on revenue.
-	Customer satisfaction by rating, location, product, category.

 - <a href = "https://github.com/Ansarulh/E-Commerce-Business-Intelligence-Project/commit/5d6e6f33cf42a283d4001e27dcbd0148cc1254e3" >Download SQL File

### 🔍 Key Insights
-	💸 60% revenue comes from Andhra Pradesh.
-	🕒 Orders spike between 10 AM – 11 PM.
-	💳 78% of payments are via Credit Card.
-	📈 November is the peak month for revenue and new customers.
- 🧺 "bed_bath_table" is the top-selling category.
-	📉 82% sellers earn less than ₹5K revenue.



### 📝 Recommendations
#### Based on the insights from this analysis, here are some strategic recommendations for the business:
##### 1.	Expand Operations in High-Revenue States
Andhra Pradesh contributes nearly 60% of total revenue. Focus marketing efforts, promotions, and inventory expansion in this region, while exploring why other states like Goa have low engagement.
##### 2.	Target High-Converting Time Slots
Peak sales occur between 10 AM – 11 PM. Run promotions or time-limited deals during these hours to maximize conversions.
##### 3.	Simplify and Promote Credit Card Payments
Since 78% of customers use credit cards, offering exclusive card-based discounts or cashback could improve retention and boost revenue further.
##### 4.	Customer Segmentation Strategy
###### With over 90% of customers in the <₹1K revenue segment, consider:

-	Upselling/cross-selling strategies
-	Personalized offers for the ₹1K–₹5K segment
-	Loyalty programs to increase lifetime value

##### 5.	Seller Development Program
###### Since 82% of sellers are low performers:

-	Offer seller training on product visibility, pricing, and customer service
-	Introduce a “Seller Success Toolkit” to help them scale revenue
-	Create tiered seller incentives

##### 6.	Improve Low-Rated Categories
###### Address poor ratings in "security_and_services" and "office_furniture" by:

-	Gathering more granular customer feedback
-	Vetting sellers in these categories
-	Improving product descriptions and quality control

##### 7.	Leverage Power BI Dashboards for Ongoing Monitoring
The dashboards created in this project can serve as templates for real-time monitoring by teams across sales, marketing, product, and operations.


### 🙋‍♂️ About Me
Hi, I'm Ansarul – a final-year Computer Science and Data Science student passionate about data analytics, storytelling with visuals, and building smart solutions that drive decisions.
#####  Let’s connect:
- [LinkedIn](www.linkedin.com/in/ansarulhoque)


### ⭐ If You Found This Useful...
Feel free to fork this repo, give it a ⭐, or share it with someone looking to learn Business Intelligence from scratch!






# 🛒 E-Commerce Business Intelligence Project


## Table of Contents
- [📌 Project Overview](-Project-Overview)
- [Dataset](#Dataset)
- [🎯 Business Objectives](#-Business-Objectives)
- [🧰 Tools](#-Tools)
- [📊 Dashboard Overview (Power BI)](#-Dashboard-Overview-Power-BI))
- [🧮 SQL Analysis Highlights](#-SQL-Analysis-Highlights)
- [🔍 Key Insights](#-Key-Insights)
- [📝 Recommendations](#-Recommendations)
- [🙋‍♂️ About Me](#-About-Me)


### 📌 Project Overview
- This project was developed as part of a simulated business case for a leading Indian e-commerce platform. The objective was to help the business measure, 
  manage, and optimize performance through data-driven insights focused on customer behavior, seller activity, product trends, and payment channel usage.

- As a Data Analyst, I handled the project end-to-end — from data cleaning and transformation in SQL Server, to data validation in Excel (Pivot Tables & Power 
  Query), and finally, building an interactive Power BI dashboard to communicate key business insights effectively

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

![Relationship](https://github.com/user-attachments/assets/23f7e651-a5fe-48e2-9d37-8202a37ba519)



### 🎯 Business Objectives
The client shared a set of core business questions to address, including (but not limited to):
- How is the business performing in terms of sales, customers, and products?
-	What’s the trend in customer acquisition and retention?
-	Which products/categories are most and least popular?
-	How are customers paying, and what’s their satisfaction level?
-	Can we segment customers and sellers based on revenue?


### 🧰 Tools
Tools	
- SQL Server -	Data cleaning, exploratory analysis
  - [Download here](https://www.microsoft.com)
- Power BI - Dashboarding and visual storytelling.
   - [Download here](https://www.microsoft.com)
- Excel -	Validation using Pivot Tables, Power Query.
  - [Download here](https://www.microsoft.com)

### 📊 Dashboard Overview (Power BI)
- <a href = "https://github.com/Ansarulh/E-Commerce-Business-Intelligence-Project/commit/68bdec865228508bc78629670b4002edce852d47" > Download Power BI Dashboard
####  Page 1: Executive Summary
##### Key Metrics & Visuals:
- Revenue by State, Month, Day,Hour, Payment Types.
- KPIs: Total Revenue, Quantity, Products, Categories, Locations, AOV, Avg. Rating, Delivery Days.

##### •	💡 Insight: Andhra Pradesh alone contributes ~60% of revenue; most orders are paid via Credit Card.

![Executive Summary ](https://github.com/user-attachments/assets/f9bcc694-b70f-4350-b2ac-24443a1be6a0)

#### Page 2: Customer Behaviour Analysis
-	New Customers by Month/Quarter/Year.
-	Revenue by Customer Segment.
-	Avg. Instalments by Segment.
-	Top Product Categories by State.

##### 💡 Insight: Most customers fall into the <₹1K segment; peak customer acquisition happens in November.

![Customer Behaviour Analysis](https://github.com/user-attachments/assets/999b67e0-a89f-4696-b18c-6468bcddd994)

#### Page 3: Product & Seller Insights
-	Product Listings by Category.
-	Revenue & Quantity by Category.
-	Top/Least Rated Categories.
-	Seller Segmentation by Revenue.

##### 💡 Insight: “bed_bath_table” is the most listed & sold category; 82% of sellers are low performers.
![Product   Seller Insights](https://github.com/user-attachments/assets/45399479-e6bd-478c-a691-19e5e0d0b6aa)


### 🧮 SQL Analysis Highlights
The full SQL work covered:

#### ✅ Data Cleaning
-	Handled nulls, blanks values across Customers, Products, Sellers, Orders, Reviews, etc.
-	Replaced #N/A, null, computed averages and modes for imputation.


#### ✅ Exploratory Analysis
-	High-level metrics (Revenue, Quantity, Products, Categories, Sellers, Locations, Payment Types)
-	Repeat customer behavior, monthly retention
-	Revenue trends by date, day of week, hour


#### ✅ Business Questions Addressed
-	Most/least performing products, sellers, and payment types.
-	Segmentation of customers/sellers based on revenue.

 - <a href = "https://github.com/Ansarulh/E-Commerce-Business-Intelligence-Project/commit/5d6e6f33cf42a283d4001e27dcbd0148cc1254e3" >Download SQL File

### 🔍 Key Insights
-	💸 60% revenue comes from one State that is Andhra Pradesh.
-	🕒 Orders spike between 10 AM – 11 PM.
-	💳 78% of payments are via Credit Card.
-	📈 November is the peak month for revenue and new customers.
- 🧺 "bed_bath_table" is the top-selling category.
-	📉 82% sellers make less than ₹5K revenue.



### 📝 Recommendations
#### Based on the insights from this analysis, here are some strategic recommendations for the business:
##### 1.	Expand Operations in High-Revenue States
Andhra Pradesh contributes nearly 60% of total revenue. Focus marketing efforts, promotions, and inventory expansion in this region, while exploring why other states have low engagement.
##### 2.	Target High-Converting Time Slots
Peak sales occur between 10 AM – 11 PM. Run promotions or time-limited deals during these hours to maximize conversions.
##### 3.	Simplify and Promote Credit Card Payments
Since 78% of customers use credit cards, offering exclusive card-based discounts or cashback could improve retention and boost revenue further.
##### 4.	Customer Segmentation Strategy
##### With over 90% of customers in the <₹1K revenue segment, consider:

-	Upselling/cross-selling strategies
-	Personalized offers for the ₹1K–₹5K segment
-	Loyalty programs to increase lifetime value

##### 5.	Seller Development Program
##### Since 82% of sellers are low performers:

-	Offer seller training on product visibility, pricing, and customer service
-	Introduce a “Seller Success programme” to help them scale revenue
-	Create tiered seller incentives

##### 6.	Improve Low-Rated Categories
##### Address poor ratings in "security_and_services" and "office_furniture" by:

-	Gathering more detailed customer feedback
-	Vetting sellers in these categories
-	Improving product descriptions and quality control

##### 7.	Leverage Power BI Dashboards for Ongoing Monitoring
The dashboards created in this project can serve as templates for real-time monitoring by teams across sales, marketing, product, and operations.


### 🙋‍♂ About Me
- Hi, I'm Ansarul – a final-year B.Tech CSE (Data Science) student and an aspiring Business Analyst.
- I'm passionate about turning data into insights, storytelling through visuals, and building smart, data-driven solutions that support better decision-making.
#### Let’s connect: [LinkedIn](www.linkedin.com/in/ansarulhoque)


### ⭐ If You Found This Useful...
Feel free to fork this repo, give it a ⭐, or share it with someone looking to learn Business Intelligence from scratch!






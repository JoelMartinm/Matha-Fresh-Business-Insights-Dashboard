# Matha Fresh Business Insights Dashboard

---

## Introduction

At Matha Fresh, we believe data isn’t just numbers—it’s the story of our customers, our products, and our growth. To bring these stories to life, I developed an end-to-end analytics pipeline and Power BI dashboard that reveals exactly what’s driving our success. This project integrates data from our e-commerce platform ([mathafresh.com](https://mathafresh.com/)) using SQL, Python, Excel, and Power BI, and translates it into clear, actionable business insights for our team.

---

## Data Collection & Preparation

### 1. Data Extraction (SQL)
- Exported all sales, product, customer, and payment data (2024–2025) directly from our website database.
- Ensured completeness by joining relevant tables and pulling granular transactional details.
 
### 2. Data Cleaning & Merging (Python Excel & PowerBI)
- Combined and harmonized datasets using Python (pandas) Excel and PowerBI.
- Standardized product names, dates, and payment methods, ensuring consistency and accuracy for analysis.
- Dealt with missing, duplicate, or incorrect entries to guarantee trustworthy reporting.

### 3. Data Structuring (PowerBI)
- Created summary tables and grouped key features (product, postcode, date, payment).
- Explored early trends—such as top-selling items and busiest order days—to guide deeper Power BI modeling.

---

## Data Modeling & Power BI Analysis

### 4. Data Import and Modeling
- Imported the cleansed data into Power BI and built relationships between sales, customers, products, and geography.
- Designed a flexible data model enabling quick breakdowns by product, location, time, and payment method.

### 5. KPI & DAX Measures
- Developed dynamic KPIs for revenue, transactions, product performance, product combinations, customer locations, and payment analysis.
- Used DAX for advanced calculations, such as year-over-year growth, average order value, and frequently bought-together analysis.

---

## Visualizations

### Dashboard Features
- **Sales Over Time:** Highlights revenue trends, seasonality, and key periods of growth.
- **Top-Selling Products:** Ranks seafood products by revenue and volume.
- **Product Pair Matrix:** Reveals the most popular combinations purchased together.
- **Customer Geography:** Displays top-performing postcodes.
- **Payment Method Analysis:** Breaks down sales by cash vs. online payments, aiding operational strategy.

![image](https://github.com/user-attachments/assets/9c3dc2f5-6694-4e50-993d-e92c7750384d)

## Insights & Actions

### 1. Sales Growth and Transaction Volume
- **Insight:**  
  Over $ 20.5 million in revenue from 34,000+ transactions in one year reveals strong market demand and effective customer acquisition.
- **Actions:**  
  - Invest in scaling operations to meet growing demand.
  - Implement loyalty programs or referral incentives to maintain customer growth momentum.
    
![image](https://github.com/user-attachments/assets/8686cec1-485a-4609-a12d-65dea6ef64e2)

---

### 2. Top-Selling Products Drive Majority of Revenue
- **Insight:**  
  King Fish, Prawns (BIG), Sardine (Big), and Indian Mackerel consistently outperform other products in both sales volume and value.
- **Actions:**  
  - Ensure high stock levels and priority sourcing for these items to prevent lost sales.
  - Feature these products in digital marketing, homepage banners, and festival promotions to further boost sales.
  
![image](https://github.com/user-attachments/assets/b8c02fec-0a88-4349-98e0-568b945288d4)


---

### 3. Popular Product Pairings
- **Insight:**  
  Product combinations like Indian Mackerel & Big Prawns are frequently bought together, indicating natural cross-sell opportunities.
- **Actions:**  
  - Create bundled offers or combo deals based on these popular pairings to increase average order value.
  - Suggest “Frequently Bought Together” products at checkout on the website.
  
![image](https://github.com/user-attachments/assets/121b0d42-1bf0-4fed-a4b5-9a07ac089429)

---

### 4. Geographical Sales Concentration
- **Insight:**  
  The top three postcodes account for over 3,200 orders, showing clear hotspots in customer demand.
- **Actions:**  
  - Target hyper-local campaigns and delivery offers in these areas for maximum impact.
  - Optimize delivery routes and schedules to these postcodes to save costs and improve customer satisfaction.
![Screenshot 2025-07-09 084016](https://github.com/user-attachments/assets/d8edb1d3-0afa-4d86-8d40-f749c918b8d2)


---

### 5. Payment Preferences and Trends
- **Insight:**  
  A significant share of sales is split between Cash on Delivery and Online Payment, with both showing strong adoption.
- **Actions:**  
  - Promote online payments with limited-time discounts or loyalty points to encourage digital adoption (reducing cash handling risks).
  - Ensure reliable Cash on Delivery service for customers who prefer it, retaining a broader customer base.

---

### 6. Sales Seasonality and Promotional Timing
- **Insight:**  
  Sales trends reveal distinct peaks in certain months, likely aligned with festivals, holidays, or local events.
- **Actions:**  
  - Plan inventory and staffing ahead of high-demand periods.
  - Launch major marketing campaigns and new product introductions around peak sales seasons.

---


## Conclusion

The Matha Fresh Data Intelligence Dashboard bridges the gap between raw numbers and business strategy. By leveraging **SQL for robust data extraction**, **Python and Excel for seamless integration and cleaning**, and **Power BI for powerful, interactive analysis**, we’ve created a tool that empowers the entire company.

The insights gained aren’t just informative—they’re actionable, leading to better stock management, targeted marketing, optimized delivery, and ultimately, a stronger connection with our customers. This dashboard will continue to evolve, supporting Matha Fresh’s vision for smart, scalable, and customer-centric growth in the fresh food industry.

---

**Tools & Technologies Used:**  
- **SQL**: Data Extraction  
- **Python (pandas)**: Merging  
- **Excel**: Data Structuring  
- **Power BI**: Data Modeling, DAX, and Visualization

---

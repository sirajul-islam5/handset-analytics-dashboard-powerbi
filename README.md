# 📱 Handset Analytics Dashboard — Power BI Project

An interactive business intelligence dashboard built in Microsoft Power BI, designed to analyze mobile handset sales performance across models, brands, payment methods, cities, and customer satisfaction. This is a guided project completed as part of my data analytics learning journey.

---

## 📌 Project Overview

This dashboard provides a comprehensive view of handset sales data across a full 12-month period. It is designed to help answer key business questions around which products sell best, how customers prefer to pay, which cities drive the most sales, and how satisfied customers are overall.

The dataset covers 5 major mobile brands — Apple, OnePlus, Samsung, Vivo, and Xiaomi — across multiple cities in India.

---

## 📊 Dashboard KPIs

| Metric | Value |
|--------|-------|
| Total Sales | 769M |
| Total Quantity Sold | 19K |
| Total Transactions | 4K |
| Average Sale Value | 40K |

---

## 🔍 Dashboard Sections

**1. Total Quantity by Month**
- Line chart tracking units sold across all 12 months
- January recorded the highest quantity (1,686) while February saw the lowest (1,493)
- Helps identify seasonal demand patterns throughout the year

**2. Total Sales by Mobile Model**
- Bar chart comparing revenue across top 3 models
- iPhone SE leads at 60M, followed by OnePlus Nord (58M) and Galaxy Note 20 (56M)

**3. Transactions by Payment Method**
- Pie chart breaking down how customers prefer to pay
- Credit Card leads at 26.25%, followed by Cash (25.89%), Debit Card (25.03%), and UPI (22.83%)
- Fairly even distribution across all four payment methods

**4. Customer Ratings**
- Horizontal bar chart showing rating distribution (1 to 5 stars)
- Majority of customers rated 5 stars (311 ratings), indicating strong overall satisfaction

**5. Total Sales by City (Map Visual)**
- Geographic map visual plotting sales across major Indian cities including Delhi, Mumbai, Bangalore, Hyderabad, Kolkata, Chennai, and more
- Gives a quick regional overview of where sales are concentrated

**6. Total Sales by Day Name**
- Line/area chart showing sales performance by day of the week
- Monday and Friday tied for the highest sales (26.4M each), with Thursday recording the lowest (23.2M)

**7. Brand Performance Summary Table**
- Table visual comparing Apple, OnePlus, Samsung, Vivo, and Xiaomi side by side
- Metrics shown: Total Sales, Total Quantity, and Transactions
- Apple leads in transactions (783) while Samsung leads in total quantity (3,923)

---

## 🎛️ Slicers / Filters

This dashboard includes **3 interactive slicers**:

| Slicer | Status |
|--------|--------| 
| Mobile Model | ✅ Working |
| Payment Method | ✅ Working | 
| Month (January – December) | ⚠️ Not Working |

---

## 🛠️ Tools & Features Used

- Microsoft Power BI Desktop
- Data Modeling & Relationships
- DAX (basic measures)
- KPI Cards
- Line Chart
- Bar Chart
- Pie Chart
- Map Visual (Bing Maps)
- Slicers for interactivity
- Summary Table Visual
- Dashboard Layout & Design

---

## 💡 Key Learnings

- How to connect and model data tables in Power BI
- Building a multi-section dashboard that tells a complete business story
- Using DAX to create calculated KPI measures
- Understanding how slicers interact with visuals through data relationships
- Designing a clean, professional dashboard layout
- Debugging slicer and relationship issues in Power BI

---

## ⚠️ Known Issues

- The **Month slicer** (January – December) is not currently filtering visuals correctly. When a month is selected, the visuals do not respond as expected. This is likely due to a missing or incorrect relationship between the Date/Month field and the data model in Power BI. 

---

## 👤 Author

**Md. Sirajul Islam**
Data Aspirant | Power BI Enthusiast 

---

> *This is a guided project completed for learning purpose.* 

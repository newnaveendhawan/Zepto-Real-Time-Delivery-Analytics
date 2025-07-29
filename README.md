# 📊 Zepto-Real-Time-Delivery-Analytics
A Power BI dashboard that tracks Zepto’s 10-minute grocery delivery performance across sales, customers, transactions, and delivery partners. It highlights key trends, top products, customer behaviour, and service quality — all in one place. Built for fast insights and smarter decisions.
This project enables stakeholders to track critical metrics related to **sales, customer retention, delivery performance, product demand**, and **transaction efficiency** using interactive visuals, advanced DAX measures, and a well-modelled dataset.

---
## 📌 2. Project Overview
###### This Power BI solution delivers a 5-page analytics dashboard focused on real-time delivery performance and customer analytics. The dashboard integrates data from 6 different tables:
- **Sales**
- **Customers**
- **Transactions**
- **Products**
- **Overall**

###### 🔹 The goal is to offer business users, analysts, and operations managers the ability to:
###### 🔹 Track sales, revenue, and customer behaviour
###### 🔹 Identify issues with transactions or deliveries
###### 🔹 Evaluate discount effectiveness
###### 🔹 Improve customer retention and delivery partner performance

---

## 📁 Project Structure
###### ├── Zepto_DAX_Measures_Complete.txt # Full list of DAX measures used
###### ├── Images (All projects related images dashboards, icons, cover, dax, etc.)
###### ├── Zepto_Complete_Dataset.xlsx # Source data tables for Orders, Customers, etc.
###### ├── README.md # Project overview and instructions (this file)
###### ├──PDFs (all dashboard PDFs)
###### ├── Main Zepto Dashboard. pbix # Power BI dashboard with 6 interactive pages (in this readme file)

---

## 🧭 Project Overview

###### This dashboard offers an end-to-end view of Zepto’s business, covering:

- 📦 **Order Analytics**
- 👥 **Customer Behaviour and Segmentation**
- 💳 **Transaction Success & Failure**
- 🚚 **Delivery Partner Performance**
- 🧾 **Product Performance**

The solution is ideal for **business analysts, marketing teams, and operations managers** who want to gain insights and make data-driven decisions quickly.

---

## 📊 Dashboard Pages Overview

| Page | Focus Area | Key Insights |
|------|------------|--------------|
| **1. Overview** | Sales & Customer KPIs | MoM growth, repeat/churned customer share |
| **2. Product Performance** | Top/slow products, low margin items | 12 slow-moving products, 4 top SKUs |
| **3. Discount Analysis** | Coupons, discount effectiveness | 53% orders with coupons, avg 16.3% discount |
| **4. Delivery Performance** | Ratings, partners | Avg rating: 4.1, ~6.4% poor delivery rate |
| **5. Transactions** | Success/failure % by mode | COD has 3x failure rate vs UPI |
| **6. Segmentation** | CLTV, churn, top 20% | Top 20% customers generate ~44% revenue |

---

## 💡 Key Business Insights (Validated)

- **Revenue grows steadily MoM**
- **28% of customers are repeat buyers**, ~17% churned
- **Top 20% of customers contribute ~44% revenue**
- **Average Order Value:** ~₹296
- **Coupon Usage:** 53%, avg discount 16.3%
- **Low-margin products correlate with high coupon use**
- **COD failure rate ~11%**, UPI ~4%
- **Delivery rating avg = 4.1**, ~6.4% rated poorly

---
## 🛠️ Built With

- [Power BI Desktop](https://powerbi.microsoft.com/)
- DAX (Data Analysis Expressions)
- Microsoft Excel (data source)
- Relational Data Modelling

---

## 📦 Dataset Summary

| Table | Description |
|-------|-------------|
| `Orders` | Order transactions with date, product, quantity, discount |
| `Customers` | Customer demographic info |
| `Products` | Product catalog and pricing |
| `Transactions` | Transaction status (Success/Failed) and mode |
| `Ratings` | Customer-provided service and product ratings |
| `Delivery` | Delivery partner information |

> All data is simulated for project/demo purposes.

---

## 🚀 Features

- 80+ Advanced DAX Measures
- YOY & MOM Growth Analysis
- Coupon Impact Visualization
- Customer Lifetime Value (CLTV)
- Dynamic Segmentation (New, Repeat, Churned)
- Transaction Mode Performance
- Delivery Partner Ratings & Insights

---

## 📈 Target Users

- **Business Analysts**
- **Operations Managers**
- **Marketing Teams**
- **Product Managers**
- **Power BI Developers**

---

## 📌 How to Use

1. Download the `.pbix` file
2. Open it in Power BI Desktop
3. Explore the 6 dashboard pages using slicers and filters
4. Optional: Replace sample data with real-time SQL or cloud data

---

## 🔮 Future Improvements

- Live data refresh via Power BI Service
- RFM Segmentation model
- Integration with Azure ML for churn prediction
- Row-level security for city managers
- Mobile layout optimisation

---

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute it for personal or professional use with attribution.

---

## 📬 Contact

For questions, improvements, or collaborations:  
**[Your Name]**  
Email: [your.email@example.com]  
LinkedIn: [linkedin.com/in/yourprofile]

---

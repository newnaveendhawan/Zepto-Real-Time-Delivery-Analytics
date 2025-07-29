# 📊 Zepto-Real-Time-Delivery-Analytics
<img width="4560" height="2565" alt="Cover Zepto (1)" src="https://github.com/user-attachments/assets/60851d2b-3dd6-4ce7-9402-aef1172eee88" />


A Power BI dashboard that tracks Zepto’s 10-minute grocery delivery performance across sales, customers, transactions, and delivery partners. It highlights key trends, top products, customer behaviour, and service quality — all in one place. Built for fast insights and smarter decisions.
This project enables stakeholders to track critical metrics related to **sales, customer retention, delivery performance, product demand**, and **transaction efficiency** using interactive visuals, advanced DAX measures, and a well-modelled dataset.

---
## 🧭 Project Overview

##### This Power BI solution delivers a 5-page analytics dashboard focused on real-time delivery performance and customer analytics. The dashboard integrates data from 6 different tables:
- Customers
- Orders
- Products
- Transactions
- Ratings
- Delivery Partners

##### This dashboard offers an end-to-end view of Zepto’s business, covering:

- 📦 **Order Analytics**
- 👥 **Customer Behaviour and Segmentation**
- 💳 **Transaction Success & Failure**
- 🚚 **Delivery Partner Performance**
- 🧾 **Product Performance**

The solution is ideal for **business analysts, marketing teams, and operations managers** who want to gain insights and make data-driven decisions quickly.

---

## 📁 Project Structure
###### ├── Zepto_DAX_Measures_Complete.txt # Full list of DAX measures used
###### ├── Images (All projects related images dashboards, icons, cover, dax, etc.)
###### ├── Zepto_Complete_Dataset.xlsx # Source data tables for Orders, Customers, etc.
###### ├── README.md # Project overview and instructions (this file)
###### ├──PDFs (all dashboard PDFs)
###### ├── Main Zepto Dashboard. pbix # Power BI dashboard with 6 interactive pages (in this readme file)

---

## 📊 Dashboard Pages Overview

| Page | Focus Area | Key Insights |
|------|------------|--------------|
| **1. Sales Analysis** | Sales, Orders & Customer KPIs | Growing MoM growth is inconsistent |
| **2. Customer Analysis** | Customer CLTV, Customer Revenue, Repeated Orders | ~28% repeat, ~17% churned|
| **3. Transaction Analysis** | Success Transactions %, Failed % | Wallet failure = 24% higer as compared to all  |
| **4. Product Performance** | Revenue per Product, Rating |sold <3 units in 60+ days|
| **5. Overall Analysis** | CLTV, churn, top 20% | Avg Discount Rate (16.3%), Top 20% drive 44% revenue |

---

## 💡 Key Business Insights (Validated)

- **Revenue grows steadily MoM**
- **28% of customers are repeat buyers**, ~17% churned
- **Top 20% of customers contribute ~44% revenue**
- **Avg Product Price:** ₹508
- **Coupon Usage:** 53%, avg discount 16.3%
- **Low-margin products correlate with high coupon use**
- **COD failure rate ~11%**, UPI ~4%
- **Delivery rating avg = 3.1**
- **Revenue Without Coupons: ₹10,38,000**

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

## 🌐 Glimpse of Dashboard
<img width="1156" height="649" alt="Overall Dashboard 2" src="https://github.com/user-attachments/assets/71c2111f-7214-4614-bf79-06cab7610929" />

---

## 📥 Data Source
> You can download Dashboard from the [Google Drive](https://drive.google.com/drive/folders/1g7ZeETXVEeyHCXDPhXrX9jWTJ3WlYsq0?usp=drive_link)   
> Original Dataset of this project [click here](https://drive.google.com/drive/folders/1Yyz848rLJicpaJlq08iCWdWuaOqh5iNi?usp=drive_link)
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

This project is licensed under the [**MIT License**.](https://github.com/newnaveendhawan/Zepto-Real-Time-Delivery-Analytics/blob/main/LICENSE)  
You are free to use, modify, and distribute it for personal or professional use with attribution.

---

## 👨‍💻 About the Author
### Naveen Dhawan
###### 🎓 BTech – NIT Warangal | Data Analyst | ML Enthusiast | Power BI & Python
---

## 📬 Contact

For questions, improvements, or collaborations:  
###### 📧 newnaveendhawan@gmail.com
###### [💼 LinkedIn](https://www.linkedin.com/in/newnaveendhawan/) 
###### [📁 Portfolio](https://naveendhawanportfolio.blogspot.com/) 

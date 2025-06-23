# Beyond-the-Numbers
Uncovering Consumer Habits, Profit Trends, and Market Shifts (2023–2024); An Interactive Analysis of Revenue, Customer Behavior, and Operational KPIs Across U.S. Markets
# 📊 Financial Insights Dashboard — Revenue, Customers & Sales Trends (2023–2024)

_“Beyond the Numbers: Uncovering Consumer Habits, Profit Trends, and Market Shifts”_  
**An Interactive Power BI Dashboard project analyzing Revenue, Customers, and Units Sold over a two-year period (2023–2024).**

---

## 📌 Project Overview

This project tells the story of how an organization’s performance metrics evolved across two years. The analysis is built around key KPIs (Revenue, Customers, Units Sold), using interactive storytelling to uncover behavioral patterns, performance issues, and untapped market opportunities, particularly focusing on **gender representation** and **seasonal revenue fluctuations**.

---

## 🧠 Hypotheses

1. **Gender Bias Hypothesis**  
   The organization is not female-friendly and may be missing out on revenue by not targeting women effectively.

2. **Seasonal Sales Hypothesis**  
   Revenue should experience significant spikes during festive seasons (e.g. Christmas, Halloween, Black Friday).

---

## 🧰 Tools Used

- **Python** (for data cleaning, feature engineering, and clustering)
- **Power BI** (for dashboard creation, DAX measures, data modeling using starr schema and visual storytelling)
- **K-Means Clustering** (customer segmentation)

---

## 📈 Key Features

- Dynamic KPI selector (Revenue, Customers, Sales)
- 12-month Moving Average and Month-over-Month Growth
- Gender-based behavior analysis
- Product and shipping preference insights
- Subscription & payment behavior visualization
- Interactive slicers and filters (e.g., category, discounts, dates)

---

## 🧪 Methodology

- Data cleaned in **Python**: removed missing values, engineered features.
- Performed **K-Means Clustering** for customer segmentation: Luxury Buyers, Budget Buyers, Cheap Buyers.
- Created a **custom date table** (Year, Month, Month Number, Month Start) to enable time intelligence in Power BI.
- Structured the model using a **Star Schema** with fact and dimension tables.
- Built dynamic DAX measures to support:
  - Total Revenue
  - Total Customers
  - Units Sold
  - 12-month moving average (per selected KPI)
  - MoM % change

---

## 📊 Findings

### ✅ Hypothesis 1: Accepted  
- **100% of subscribers were male.** There was no female subscriber
- Women showed limited engagement across KPIs.
- Indicates significant untapped potential in the female market.

### ❌ Hypothesis 2: Rejected  
- **Revenue peaks did not align with major holidays.**
- April (non-festive) had the highest growth.
- December (holiday season) showed a sharp revenue decline.

---

## 🔍 A/B Testing Suggestion (for future analysis)

To validate new holiday marketing strategies:

1. **Objective:** Increase conversions and revenue during festive periods.
2. **Create variants:** Test different promotions (discount %, visual layout, CTAs).
3. **Split audience randomly:** Half see Version A, half see Version B.
4. **Measure:** CTR, Conversion Rate, Average Order Value.
5. **Analyze results:** Identify statistically significant improvements.
6. **Iterate:** Apply winning strategy in future campaigns.

---

## 📌 Insights

- The business is overly reliant on male customers and lacks inclusive engagement.
- Customer behavior shows preference for **standard/free shipping**, especially among women.
- Majority of revenue comes from **older adults and luxury buyers**, offering stability but highlighting the need to diversify.

---

## 📁 Project Files

| File | Description |
|------|-------------|
| `CUSTOMER SUBSCRIBTION.pbix` | Main Power BI file with dynamic visuals |
| `CUSTOMER SUBSCRIPTION` | Python notebook for preprocessing & clustering |
| `SB.csv` | Dataset worked on|
| `README.md` | Project documentation |

---

## 📎 Screenshots

| 📈 Trends Page | 📍 Overview Page |
|---|---|
| ![Trends](![image](https://github.com/user-attachments/assets/11e51538-c185-454e-aea4-dac3bfb91fa1)
) | ![Overview](![image](https://github.com/user-attachments/assets/c370eeb9-4e76-4358-a768-b147a1a2ee8a)
) |

---

## ✅ To Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/financial-insights-dashboard.git

# Orders Performance Dashboard – Insights

## 📌 Project Overview
The **Orders Performance Dashboard** presents a full analytical view of order trends, discount impact, and profitability behavior.  
It is built using **Power BI**, with custom DAX measures to model profit improvement if discounts are reduced below 20%.

---

## 🔍 Key Insights

### 1. Orders Distribution by Discount
- Most orders occur in the **0–10%** discount range.  
- Higher discount categories (40%+) appear less frequently but are strongly associated with **negative profit**.

---

### 2. Impact of Discount on Profitability
- There is a clear negative relationship between discounts and profit.
- Many orders with discounts **above 40%** fall into loss.
- Bubble size represents total orders contributing to each loss cluster.

---

### 3. Target Profit with Discount ≤ 20%
A custom DAX model was developed using:

- **Current Profit:** 283K  
- **Target Profit (if discount ≤ 20%):** 340K  

This shows a measurable opportunity to **increase profit** by controlling excessive discounting.

---

### 4. Monthly Orders Trend
- Clear seasonality pattern:
  - Peak in **September**.
  - Stable activity between **February–July**.
  - Growth recovery toward **December**.

---

### 5. Regional Order Performance
- **Central region** shows the highest activity across Consumer, Corporate, and Home Office segments.
- North and South perform consistently but with lower total volume.

---

### 6. Monthly Orders vs Profit
- Some months show high orders but low total profit.
- Confirms that **profitability is driven more by discount strategy** than order volume.

---

## 🛠 Technical Work
### Data Cleaning & Shaping
### DAX Measures 

---

## 🧠 Business Value
This dashboard helps stakeholders understand:

- Optimal discount thresholds  
- Profit leakage caused by heavy discounting  
- Regional and segment performance differences  
- Seasonality and monthly demand fluctuations  
- Whether order growth translates into profit growth  

---

## 🚀 Future Enhancements
- Forecasting model for monthly orders  
- Discount What-If parameter as a slicer  
- Deep-dives for customer profitability  
- Adding region × product category performance pages  

---

## 🖼 Dashboard Preview
(./Dashboard3.png)











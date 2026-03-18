## 📌 Project Overview
This project focuses on analyzing vendor performance, profitability, and inventory efficiency using data analytics techniques. The goal is to generate insights that help improve business decisions, reduce costs, and increase profitability.

---

## 🎯 Objectives
- Analyze vendor contribution to total purchases  
- Identify high-profit but low-sales brands  
- Detect unsold and slow-moving inventory  
- Evaluate pricing and profit margin patterns  
- Provide actionable business recommendations  

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy)  
- Matplotlib & Seaborn (Visualization)  
- Power BI *(optional)*  
- Microsoft Excel  

---

## 📂 Project Structure

Vendor-Analysis/
│── data/
│── notebooks/
│── dashboard/
│── README.md


---

## 🔍 Exploratory Data Analysis (EDA)

### Key Observations:
- Some transactions show **negative gross profit**, indicating losses  
- Profit margin becomes extremely negative when sales are zero  
- Presence of **outliers** in pricing (premium products)  
- High variation in freight cost indicates logistics inefficiency  
- Stock turnover varies significantly (0 to 274)  

---

## 📊 Correlation Insights

- Purchase Price & Actual Price → **0.99 (Strong Positive)**  
- Sales Revenue & Gross Profit → **0.98 (Very Strong)**  
- Purchase Quantity & Sales Quantity → **0.67 (Moderate)**  
- Profit Margin & Stock Turnover → **0.40 (Moderate)**  
- Freight Cost shows weak correlation with other variables  

---

## 💡 Key Insights

### 🟢 High Profit, Low Sales Brands
- 198 brands identified  
- Belong to premium/niche segments  
- Opportunity to increase sales while maintaining margins  

---

### 🟡 Vendor Contribution
- Top 10 vendors contribute **65.69%** of total purchases  
- Indicates high dependency on limited vendors  

---

### 🔵 Bulk Purchasing Impact
- Bulk orders reduce unit cost by **~72%**  
- Helps improve overall profitability  

---

### 🔴 Unsold Inventory
- Around **$1.75M inventory unsold**  
- Mostly concentrated among top vendors  

---

### ⚖️ Profit Margin Comparison

| Vendor Type | Profit Margin | Insight |
|------------|--------------|--------|
| Top Vendors | ~31% | High sales, low margin |
| Low Vendors | ~41% | Low sales, high margin |

---

## 📈 Business Recommendations
- Optimize pricing strategies  
- Improve marketing for low-sales brands  
- Reduce dependency on top vendors  
- Use bulk purchasing effectively  
- Manage slow-moving inventory using promotions  
- Improve logistics to control freight cost  

---

## 🚀 Conclusion
This project highlights the trade-off between **sales volume and profitability**. By applying data-driven strategies, businesses can improve efficiency, reduce risks, and increase overall performance.

---

## 🔮 Future Scope
- Machine Learning for demand prediction  
- Real-time dashboard integration  
- Automated inventory management system  

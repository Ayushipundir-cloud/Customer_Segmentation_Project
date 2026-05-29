# 📊 Electronics Sales Analytics Dashboard

> A multi-dashboard Power BI analytics project analyzing **20,000 transactions** across a consumer electronics retailer — covering revenue performance, cancellation/revenue leakage, and customer segmentation from **September 2023 to September 2024**.

---

## 📁 Dataset

| Field | Detail |
|---|---|
| **Source** | `Electronic_sales_Sep2023-Sep2024.csv` |
| **Records** | 20,000 transactions |
| **Period** | Sep 2023 – Sep 2024 |
| **Products** | Smartphone, Tablet, Laptop, Smartwatch, Headphones |
| **Order Statuses** | Completed, Cancelled |

**Columns:** `Customer ID`, `Age`, `Gender`, `Loyalty Member`, `Product Type`, `SKU`, `Rating`, `Order Status`, `Payment Method`, `Total Price`, `Unit Price`, `Quantity`, `Purchase Date`, `Shipping Type`, `Add-ons Purchased`, `Add-on Total`

---

## 📌 Dashboards Preview :
-[View Dashboard](https://github.com/Ayushipundir-cloud/Customer_Segmentation_Project/blob/main/Customer%20Segmentation%20Dashboard.png)
-[View Dashboard](https://github.com/Ayushipundir-cloud/Customer_Segmentation_Project/blob/main/Customer%20Segmentation%20Dashboard.png)
-[View Dashboard](https://github.com/Ayushipundir-cloud/Customer_Segmentation_Project/blob/main/Customer%20Segmentation%20Dashboard.png)

### 1. 🛒 Electronics Sales Dashboard

High-level performance overview across all products, payment methods, and shipping types.

**Key Metrics:**
- **Total Revenue:** $48.18M
- **Total Quantity Sold:** 83K
- **Total Orders:** 10K
- **Average Order Value:** $4.69K

**Key Insights:**
- Smartphones dominate product revenue at **$16.2M**, followed by Smartwatches ($10.8M) and Laptops ($9.3M)
- PayPal ($14.19M) and Credit Card ($14.41M) are the top payment methods, together accounting for ~59% of revenue
- Standard shipping is the most used method at **$16.4M** in revenue
- Revenue shows a **sharp declining trend** from ~$5.1M/month (Aug–Sep 2024) to $0.4M by September 2023, reflecting business growth over the period

---

### 2. 🚨 Revenue Leakage Analysis

Focuses on cancelled orders and the revenue lost as a result.

**Key Metrics:**
- **Cancelled Orders:** 4,987K
- **Cancellation Rate:** 48.57%
- **Lost Revenue Due to Cancellations:** $16.07M

**Key Insights:**
- Nearly **1 in 2 orders** is cancelled — a critical area for operational improvement
- Credit Card (30.63%) and PayPal (29.13%) account for the most lost revenue by payment method
- Smartphones alone account for **$5.41M** in lost revenue, the highest of any product category
- Cancellation rates are relatively uniform across product types, ranging from **34.94% (Headphones)** to **37.51% (Smartphones)**
- Standard shipping carries the highest cancellation-linked loss at **$5.4M**

---

### 3. 👥 Customer Segmentation Analysis

Breaks down customer behavior by age group, gender, and loyalty membership.

**Key Metrics:**
- **Non-Loyalty Revenue:** $37.81M
- **Loyalty Member Revenue:** $10.38M
- **Loyalty % of Revenue:** 21.53%

**Key Insights:**
- The **55+ age group** is the largest customer segment (41.02% of customers) and the top revenue contributor at **$19.8M** combined across genders
- **Loyalty members consistently show lower Average Order Values** across all age groups ($3.4K–$3.5K) compared to non-members ($4.2K–$4.4K)
- Loyalty members account for just **21.5% of total revenue**, suggesting an opportunity to either grow the program or reassess its value proposition
- Smartphone purchases lead both loyalty ($3.4M) and non-loyalty ($12.7M) segments

---

## 🛠️ Tools & Technologies

- **Power BI** — Dashboard development & interactive visualizations
- **DAX** — Calculated measures and KPIs
- **Python / Pandas** *(optional EDA)* — Data profiling and validation
- **CSV** — Raw data source

---

## 📂 Repository Structure

```
📦 electronics-sales-analytics
 ┣ 📄 Electronic_sales_Sep2023-Sep2024.csv
 ┣ 📊 Electronic_Sales_Dashboard.png
 ┣ 📊 Revenue_Leakage_Dashboard.png
 ┣ 📊 Customer_Segmentation_Dashboard.png
 ┣ 📄 README.md
 ┗ 📁 pbix/
    ┗ Electronics_Sales_Analysis.pbix
```

---

## 💡 Key Takeaways

1. **Revenue is growing** — monthly figures rise sharply from late 2023 into mid-2024
2. **Cancellation rate (~49%) is alarmingly high** and represents over $16M in lost revenue — the single biggest opportunity for improvement
3. **Loyalty program underperforms** — loyalty members spend less per order and represent only 21.5% of revenue despite being a defined segment
4. **Older customers (55+) are the core demographic** — marketing and product strategy should reflect this
5. **Smartphones are the star product** — highest revenue, highest cancellations, highest loyalty purchases.

   <img width="876" height="478" alt="Electronic Sales Dashboard" src="https://github.com/user-attachments/assets/ab676e71-24fe-434c-bfc9-e42f09cb783a" />
   <img width="872" height="476" alt="Customer Segmentation Dashboard" src="https://github.com/user-attachments/assets/739b6a67-c50c-4528-ba2f-f22e9a5ea374" />
   <img width="867" height="484" alt="Revenue Leakage Dashboard" src="https://github.com/user-attachments/assets/81a995c4-0b0c-42c0-acd3-2a05137e65f5" />

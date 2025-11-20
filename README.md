# 📊 Walmart Sales Analysis — SQL Project  
### **Data Analytics | Business Insights | SQL Portfolio Project**

This project showcases my ability to work with real-world retail transaction data using SQL.  
I performed end-to-end analysis involving data exploration, sales insights, customer segmentation, time-based trends, and advanced business intelligence queries.

📄 **Full SQL Script:** [📄 walmart_sales_analysis.sql](./walmart_sales_analysis.sql)


---

## 🚀 Project Objectives

The purpose of this analysis is to extract meaningful business insights from Walmart’s sales data.  
The project focuses on:

- Store & branch performance  
- Product category profitability  
- Customer purchasing behavior  
- Rating patterns  
- Time-based demand (hourly, daily, monthly)  
- VAT and revenue analysis  
- Gender & membership insights  

---

## 🧠 Skills Demonstrated

### **🔹 SQL Skills**
- Aggregations: `SUM`, `AVG`, `COUNT`
- Conditional filtering: `WHERE`, `HAVING`
- Grouping & segmentation: `GROUP BY`, `ORDER BY`
- Working with dates & time:  
  `EXTRACT()`, `TO_CHAR()`
- Conditional logic using `CASE WHEN`
- CTEs with `WITH` clause  
- Multi-level business insights  
- Clean, optimized SQL writing

### **🔹 Analytics & BI Skills**
- Translating business problems into SQL  
- KPI creation  
- Trend analysis  
- Customer segmentation  
- Product & category performance  
- Retail industry understanding  
- Insight-based storytelling

---

## 📁 Dataset Overview

| Column | Description |
|--------|-------------|
| `branch` | Store branch (A, B, C…) |
| `city` | Location of branch |
| `customer_type` | Member/Normal |
| `gender` | Male/Female |
| `product_line` | Product category |
| `unit_price` | Price per item |
| `quantity` | Units purchased |
| `vat` | Tax charged |
| `total` | Final bill amount |
| `date` | Purchase date |
| `time` | Purchase time |
| `payment_method` | Cash / Ewallet / Credit Card |
| `rating` | Customer satisfaction rating |

---

## 📝 Business Questions Solved (20 total)

### **🔹 Basic Level**
- Total sales per branch  
- Average customer rating per city  
- Count of transactions per customer type  
- Total quantity sold per product line  
- VAT collected per payment method  

### **🔹 Medium Level**
- Sales by city × gender  
- Avg quantity sold (male customers)  
- Member transactions per branch  
- Day-wise total sales  

### **🔹 Advanced Level**
- Hour-wise and month-wise sales  
- Branch rating-based filtering  
- VAT analysis on high-value items  
- Gender-wise average sales per branch  
- Day-of-week transaction insights  
- City × customer-type sales (transaction > 50)  
- Unit price analysis by payment method  
- Branch × hour segmentation  
- Product lines with high sales (>1000)  
- Sales by Morning / Afternoon / Evening (CTE + CASE)

---

## 📊 Highlight Query Example

```sql
SELECT
    product_line,
    SUM(total) AS total_sales,
    AVG(rating) AS avg_rating
FROM walmart_sales
GROUP BY product_line
HAVING SUM(total) > 1000;
```

---

## 🏆 Key Insights (Sample)

- Afternoon shows highest sales traffic in most branches  
- Member customers generate more revenue than normal customers  
- Certain product lines outperform consistently  
- Ratings differ significantly by branch and product type  
- High-value transactions contribute more to VAT collection  
- Weekend traffic patterns differ from weekdays  

---

## 📂 File Included

- **[📄 walmart_sales_analysis.sql](./walmart_sales_analysis.sql)** — contains all 20 business queries + schema creation
- **[📂 walmart_sales_csv](./walmart_sales_csv.csv)** — raw csv file


---

## 🎯 Why This Project Matters to Recruiters

This project demonstrates:

- Strong SQL problem-solving  
- Real business understanding  
- Ability to work with transactional datasets  
- Analytical thinking  
- Clean coding standards  
- KPI-focused insights  
- Retail domain familiarity  

Useful for roles like:

- **Data Analyst**  
- **Business Analyst**  
- **SQL Analyst / BI Analyst**  
- **Reporting Analyst**  
- **Analytics Consultant**

---

## 📬 Connect With Me
## 📜 Author

**👤 Chandrasekhar Panda**\
💼 MBA Business Analytics | Passionate about Data Analytics, SQL Development & Business Intelligence\
📧 [chandrasekharpanda304@gmail.com](mailto:chandrasekharpanda304@gmail.com)\
🔗 [LinkedIn Profile](https://www.linkedin.com/in/chandrasekharpanda)

------------------------------------------------------------------------



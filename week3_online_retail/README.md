# Week 3 – Window Functions & Ranking

**Dataset:** Online Retail II (UCI Machine Learning Repository)

## 🔑 Key Concepts
- `RANK()`, `DENSE_RANK()`, `ROW_NUMBER()`  
- `LAG()` and `LEAD()` for temporal analysis  
- Running totals and moving averages  
- Partitioning and window frames

## 🎓 Learning Objectives
1. Use window functions to create rankings and growth metrics  
2. Compute time-based statistics within SQL  
3. Detect patterns in customer retention and purchase behavior

## 💻 Practice Tasks
- Rank products by monthly sales within each country  
- Find average purchase interval per customer using `LAG()`  
- Build a 3-month rolling average of revenue

## 📈 Project Deliverable
**Customer Purchase Behavior Report** in `/project/Customer_Purchase_Behavior_Report.md`  
Highlights repeat purchase intervals and monthly revenue trends.

## 🧠 Reflection Prompt
How do window functions differ from GROUP BY aggregations?  
Which insight was only possible once you used `LAG()` or `RANK()`?

# Supply Chain Performance 

## Project Overview

This project analyzes the DataCo Supply Chain dataset using Tableau to evaluate shipment, delivery, and sales performance. The analysis focuses on shipping delays, late deliveries, revenue, profit, customer segments, markets, and product categories to identify key operational issues and business opportunities through an interactive dashboard.

---

## Business Questions

1.	How does actual shipping time compare with scheduled shipping time?
2.	Which shipping mode handles the most orders?
3.	Which shipping mode has the highest average shipment delay?
4.	Which countries have higher shipment delays? 
5.	What is the overall distribution of orders by delivery status?
6.	How does the late delivery rate vary by month throughout the year?
7.	Which shipping mode has the highest late delivery rate?
8.	Which countries have the highest late delivery rates?
9.	How does revenue change throughout the year?
10.	Which customer segment generates the most revenue and profit?
11.	Which market contributes the most revenue?
12.	Which product categories generate the highest revenue?

---

## Tools Used

Tableau

---

## Dataset

- Total Records: 180,520 
- Total Columns: 53
- Source: Kaggle DataCo Supply Chain 

---

## Dashboard Preview

![Dashboard](dashboard1 1.png)
(dashboard1 2.png)
(dashboard1 3.png)

---

## Tableau Dashboard

🔗 **Dashboard Link:** https://public.tableau.com/views/Supply_Chain_Dashboard_17870710640650/SHIPMENT?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

## Key Insights

- The average actual shipping time is 3.5 days, compared with 2.9 days of scheduled shipping time, resulting in a gap of approximately 0.6 days. 
- Standard Class handles the highest number of orders, with approximately 39.3K orders, followed by Second Class and First Class. 
- Second Class has the highest average shipment delay at approximately 1.99 days. 
- South Sudan, Eritrea, and Western Sahara record some of the highest average shipment delays, at approximately 2 days. 
- The overall late delivery rate is 54.83%, with late delivery representing the largest delivery status at approximately 36.0K orders. 
- The late delivery rate remains relatively stable throughout the year, ranging between approximately 54%–56%. 
- First Class has the highest late delivery rate at 95.32%, followed by Second Class at 76.63%. 
- Total revenue reaches approximately $36.8M, while total profit reaches approximately $4.0M. 
- January records the highest monthly revenue at approximately $3.46M, while revenue decreases to approximately $2.60M in December. 
- The Consumer segment generates the highest revenue and profit, contributing approximately $19.10M in revenue and $2.07M in profit. 
- Europe contributes the highest revenue among markets at approximately $10.87M, followed by LATAM at $10.28M. 
- Fishing is the highest-revenue product category, generating approximately $6.93M.

---

## Business Recommendations

- Monitor the gap between actual and scheduled shipping time to evaluate delivery performance and establish more realistic shipping time estimates.
- Closely monitor Standard Class because it handles the largest order volume. Maintaining stable performance is important to prevent high order volume from contributing to increased shipping delays.
- Review the shipping process and delivery targets for Second Class, which has the highest average shipment delay. Shipping estimates can be adjusted when they do not reflect actual delivery conditions.
- Monitor countries with consistently high shipment delays and review whether their estimated shipping times accurately reflect actual conditions.
- Prioritize improvements in delivery reliability because more than half of orders experience late delivery. The company can establish a target for reducing late deliveries and monitor performance regularly.
- Evaluate the delivery targets for First Class and Second Class, which have relatively high late delivery rates. For orders requiring greater delivery reliability, alternative shipping modes with lower late delivery rates can be considered.
- Maintain sales performance during high-revenue periods while strengthening promotional activities during lower-performing periods to support more consistent revenue throughout the year.
- Continue prioritizing the Consumer segment because it generates the highest revenue and profit. Retention strategies such as repeat-purchase incentives, targeted promotions, and customer reward programs can be considered.
- Maintain the performance of high-revenue markets, particularly Europe, while identifying opportunities to improve sales in lower-performing markets.
- Prioritize high-revenue product categories such as Fishing in inventory and sales planning while also considering product-level profitability before increasing inventory or promotional activities.

---

## Repository Contents

| File | Description |
| --- | --- |
| `README.md` | Project documentation and summary |
| `Supply_Chain_Dashboard.twbx` | Tableau packaged workbook |
| `dashboard.png` | Tableau dashboard preview |

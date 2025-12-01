# Uncovering Hidden Risks in $55M Revenue: A Sales Performance Investigation Using SQL & Power BI

> From seemingly strong growth to stagnant customers and over-reliance on a few heroes – an end-to-end analytics story using the Wide World Importers dataset.

![Dashboard Preview](images/dashboard.png)

## Business Problem
At first glance, Wide World Importers looked healthy: **$55.82M in sales**, **23K orders**, and consistent YoY growth.

But the deeper I analyzed the data, the more concerning the real story became:
- 0% customer base growth despite rising revenue
- Extreme dependence on a handful of cities and salespeople
- Severe monthly volatility hidden beneath yearly gains

This wasn't just a sales dashboard.  
It was an early warning system.

## Key Insights Discovered
- Customer base grew **0%** while revenue increased → heavy reliance on existing customers
- Just **3 cities** and **3 sales reps** drove the majority of performance
- Monthly sales trend showed dangerous volatility masked by strong yearly numbers
- Underperforming regions and reps represent millions in untapped potential

## Recommendations Delivered
1. **Launch urgent customer acquisition initiatives** – 0% growth is unsustainable
2. **Investigate & revive underperforming cities** – reduce geographic concentration risk
3. **Implement sales training & territory optimization** – close the gap between top and bottom performers
4. **Stabilize monthly performance** – address root causes of volatility (inventory, promotions, coverage)

## Technical Implementation (End-to-End)
- Extracted and transformed data using **complex SQL** (CTEs, window functions, date dimension logic)
- Built a clean **star schema** in Power BI with proper relationships
- Created **DAX measures** for YoY growth, running totals, and dynamic comparisons
- Designed an **interactive dashboard** with drill-throughs and clear visual hierarchy

## Tools Used
- SQL Server (SSMS)
- Power BI Desktop
- DAX
- Data Modeling (Star Schema)

## Project Files
- `SQL_Queries/`  <img width="1366" height="720" alt="Screenshot 2025-11-23 235003" src="https://github.com/user-attachments/assets/3c650614-6dc5-4ed7-bae4-157092346cdc" />
- `Modelling` <img width="941" height="451" alt="Screenshot 2025-11-24 221752" src="https://github.com/user-attachments/assets/1fb28b55-36e1-4c80-8353-5385f03d4f23" />

- `WideWorldImporters_Sales_Dashboard`  <img width="869" height="489" alt="WideWorldImposters Sales Performance Dashboard" src="https://github.com/user-attachments/assets/27337e63-f90c-44f2-97be-0d3c8aa57b2c" />

- `Report_Presentation` <img width="815" height="458" alt="Screenshot 2025-11-28 210110" src="https://github.com/user-attachments/assets/fe04005b-3687-4d66-b009-207bbbdd2b6a" />
<img width="813" height="457" alt="Screenshot 2025-11-28 210207" src="https://github.com/user-attachments/assets/920f2719-3cb1-494a-9978-998115436a04" />
<img width="812" height="458" alt="Screenshot 2025-11-28 210227" src="https://github.com/user-attachments/assets/954fd05d-cff9-4711-97bd-867c33fce19f" />
<img width="806" height="460" alt="Screenshot 2025-11-28 210250" src="https://github.com/user-attachments/assets/c640f2b2-97fd-4f79-9cd9-e6e140568a3b" />



---
Built from scratch as my first complete end-to-end data analytics project  : #*All me,no tutorials*.

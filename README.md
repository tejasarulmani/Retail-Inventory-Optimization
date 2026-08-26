# Retail Inventory Optimization: ABC Analysis & EOQ Modeling

## Executive Summary
This project applies Operations Research methodologies to raw retail transaction data to optimize inventory management. By conducting an ABC (Pareto) analysis and applying the Economic Order Quantity (EOQ) model, this project simulated a **77.92%** reduction in annual inventory costs, identifying exactly **$539,297.35** in potential savings.

## Business Problem
The company currently orders inventory on a standard monthly schedule. This creates inefficiencies: ordering low-volume items too frequently (incurring unnecessary administrative/shipping costs) and ordering high-volume items in suboptimal batches (incurring excess holding costs). 

## Methodology
1. **Data Engineering (Python/Pandas):** Processed a raw Kaggle dataset of over 130,000 retail transactions. 
2. **ABC Analysis:** Calculated cumulative revenue to identify the "Class A" items. The analysis revealed that **21.6% of the SKUs (1,136 items) drove 80% of total sales volume**. The optimization scope was restricted to these high-value items.
3. **Mathematical Modeling:** Calculated the Annual Demand and Daily Demand Volatility for all Class A items. 
4. **Prescriptive Analytics:** Applied the EOQ formula and Safety Stock formulas (assuming a 95% service level and 14-day lead time) to generate dynamic, SKU-specific order quantities and reorder points.

## Key Results
* **Total Current Annual Cost:** $692,142.36
* **Optimized Annual Cost:** $152,845.01
* **Total Savings:** $539,297.35
<img width="789" height="590" alt="image" src="https://github.com/user-attachments/assets/1198b96f-2861-4bdf-9641-2f516a0ded7d" />

## Technical Skills Demonstrated
* Data Wrangling & Aggregation (`pandas`)
* Statistical Analysis (`numpy`)
* Data Visualization & Formatting (`matplotlib`, `pandas.style`)
* Operations Research (EOQ, Safety Stock, Reorder Point, Pareto Analysis)

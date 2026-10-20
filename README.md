# Retail Inventory Optimization: ABC Analysis & EOQ Modeling

## Executive Summary
This project applies Operational Research methodologies to raw retail transaction data to optimize inventory management. By conducting an ABC (Pareto) analysis and applying the Economic Order Quantity (EOQ) model, this project simulated a **77.92%** reduction in annual inventory costs ($539,297.35 in savings) while drastically reducing the procurement team's administrative workload.

## Business Problem
The company currently orders inventory on a standard monthly schedule (12 orders/year per SKU). This creates dual inefficiencies: ordering low-volume items too frequently (incurring unnecessary administrative and shipping costs) and ordering high-volume items in suboptimal batches (incurring excess holding costs).

## Methodology
1. **Data Engineering:** Processed a raw dataset of over 130,000 retail transactions using Python/Pandas to calculate annualized demand, unit economics, and daily demand variance.
2. **ABC Analysis:** Calculated cumulative revenue to identify "Class A" items. The analysis revealed that 21.6% of the SKUs (1,136 items) drove 80% of total sales volume. The optimization scope was restricted to these high-value items.
3. **Prescriptive Analytics (EOQ & Safety Stock):** Applied the EOQ formula and Safety Stock models (assuming a 95% service level and 14-day lead time) to generate dynamic, SKU-specific order quantities, reorder points, and optimized order cycle days.

## Key Results & Operational Impact
* **Financial Savings:** Reduced total projected annual inventory costs from $692,142.36 to $152,845.01 (a $539,297.35 / 77.9% reduction).
* **Workload Reduction:** Replaced static 30-day replenishment schedules with dynamic EOQ cycles, significantly reducing total annual purchase orders and freeing up procurement bandwidth.

*<img width="1790" height="690" alt="image" src="https://github.com/user-attachments/assets/15058548-c3ed-4ad8-accf-657fbb005393" />*

## Top 10 Optimized SKUs

*<img width="1605" height="467" alt="image" src="https://github.com/user-attachments/assets/f9656975-bd55-43cf-83f8-51f173315d79" />*

## Technical Skills Demonstrated
* Data Wrangling & Aggregation (`pandas`)
* Statistical Analysis (`numpy`)
* Data Visualization (`matplotlib`, `pandas.style`)
* Operations Research (EOQ, Safety Stock, Reorder Point, Pareto Analysis)

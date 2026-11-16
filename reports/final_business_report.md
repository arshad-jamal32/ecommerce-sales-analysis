
# E-Commerce Sales Analysis – Business Report

## 1. Executive Summary

This project focuses on analyzing an e-commerce retail dataset to understand sales performance, profitability, customer behavior, product performance, and shipping operations.

The analysis was performed using Python, Pandas, NumPy, Matplotlib, and Seaborn.

The dataset contains 9,994 records and 21 columns, covering order details, products, customers, sales, discounts, profits, and shipping information.

### Key Business Metrics

| Metric | Value |
|---|---:|
| Total Sales | 2,297,200.86 |
| Total Profit | 286,397.02 |
| Total Quantity Sold | 37,873 |
| Total Orders | 5,009 |
| Average Order Value | 458.61 |
| Profit Margin | 12.47% |

### Project Objective

The main objective is to identify business trends, understand profitable and loss-making areas, evaluate customer and product performance, and provide data-driven recommendations to improve business performance.

## 2. Category Performance Analysis

The category-wise analysis shows that Technology generated the highest sales of 836,154.03 and the highest profit of 145,454.95.

Office Supplies recorded the highest quantity sold, with 22,906 units, and generated a profit of 122,490.80.

Furniture generated sales of 741,999.80 but earned only 18,451.27 in profit, indicating relatively weak profitability compared with the other categories.

### Key Insights

- Technology is the strongest category in terms of sales and profit.
- Office Supplies has the highest sales volume by quantity.
- Furniture requires further investigation to identify profitability issues.

## 3. Regional Performance Analysis

The regional analysis indicates that the West region performed best, generating sales of 725,457.82 and profit of 108,418.45 across 1,611 orders.

The East region ranked second in profitability, with 91,522.78 in profit.

The South region recorded the lowest sales of 391,721.90 and the lowest order count of 822. The Central region generated the lowest profit of 39,706.36.

### Key Insights

- West is the strongest region in sales, profit, and order count.
- East is another major contributor to business profitability.
- South has the lowest sales and order volume.
- Central requires attention because of its comparatively low profit.

### Business Recommendations

1. Maintain and strengthen the Technology category because of its strong sales and profit contribution.
2. Explore opportunities to increase Office Supplies sales through its high-volume customer demand.
3. Investigate Furniture pricing, discounting, and product costs to improve profitability.
4. Study successful strategies in the West region and identify opportunities to apply them in the South and Central regions.
5. Develop targeted marketing campaigns to improve sales in weaker-performing regions.

## 4. Product Performance Analysis

The product-level analysis identified the top-performing products based on total sales and total profit.

The Canon imageCLASS 2200 Advanced Copier emerged as the best-performing product in both metrics, generating 61,599.82 in sales and 25,199.93 in profit.

The Fellowes PB500 Electric Punch Plastic Comb Binding Machine ranked second in both sales and profit.

Other strong-performing products included Hewlett Packard LaserJet 3310 Copier and HP Designjet T520 Inkjet Large Format Printer.

### Key Insights

- Canon imageCLASS 2200 Advanced Copier is the leading product in both sales and profitability.
- Some products contribute significantly to overall business profit.
- Monitoring product-level sales and profit can help improve inventory and sales planning.

## 5. Customer Performance Analysis

The customer analysis identified the most valuable customers based on their total sales and profit contributions.

Sean Miller generated the highest sales of 25,043.05, making him the top customer by sales.

Tamara Chand generated the highest profit of 8,981.32, making her the most profitable customer.

Raymond Buch and Sanjit Chand also appeared among the top customers in both sales and profit rankings.

### Key Insights

- Sean Miller is the highest revenue-generating customer.
- Tamara Chand is the highest profit-generating customer.
- High sales contribution does not necessarily mean the highest profit contribution.
- Customer-level analysis helps identify valuable customers and opportunities for customer retention.

### Business Recommendations

1. Maintain adequate inventory of high-performing products.
2. Analyze product costs and discounts to understand profitability differences.
3. Develop customer retention strategies for high-value customers.
4. Offer personalized promotions based on customer purchasing behavior.
5. Track both customer sales and profit instead of relying only on revenue.

## 6. Loss-Making Product Analysis

The loss-making product analysis identified products that generated negative total profit.

The Cubify CubeX 3D Printer Double Head Print recorded the highest loss of -8,879.97, followed by the Lexmark MX611dhe Monochrome Laser Printer with a loss of -4,589.97.

Other loss-making products included the Cubify CubeX 3D Printer Triple Head Print and several conference table products.

### Key Insights

- Certain products generate losses despite contributing to sales.
- The Cubify CubeX 3D Printer Double Head Print is the biggest loss-making product.
- Product-level profitability should be monitored regularly.

## 7. Discount vs Profit Analysis

The discount analysis revealed a strong relationship between discount levels and business profitability.

At 0% discount, the business generated the highest total profit of 320,987.60.

At a 20% discount, the business remained profitable, generating 90,337.31 in total profit.

However, discount levels from 30% to 80% recorded negative total profits.

The highest total loss occurred at the 70% discount level, with a negative profit of -40,075.36.

### Key Insights

- Higher discount levels are associated with negative total profit in this dataset.
- Discounts of 30% or more require careful evaluation.
- Excessive discounting may reduce business profitability.

### Business Recommendations

1. Review pricing and discount policies for loss-making products.
2. Investigate the cost structure of the Cubify CubeX 3D Printer Double Head Print.
3. Establish discount approval limits for high-discount transactions.
4. Evaluate discounts based on product margins rather than sales volume alone.
5. Monitor profitability at each discount level regularly.

## 8. Shipping Performance Analysis

The shipping analysis evaluated different shipping modes based on sales, profit, order volume, and average shipping duration.

Standard Class handled the highest number of orders, with 2,994 orders, generating total profit of 164,088.79. Its average shipping duration was 5.01 days.

Same Day shipping was the fastest mode, with an average shipping duration of 0.04 days, while First Class averaged 2.18 days.

Second Class recorded 964 orders and generated total profit of 57,446.64.

### Key Insights

- Standard Class is the most widely used shipping mode.
- Standard Class generates the highest total profit.
- Same Day provides the fastest delivery.
- First Class and Second Class offer intermediate delivery durations.

### Business Recommendations

1. Maintain Standard Class as an important shipping option because of its high order volume.
2. Monitor Same Day shipping costs to evaluate its financial efficiency.
3. Compare shipping costs and customer satisfaction across delivery modes.
4. Evaluate delivery performance regularly to improve customer experience.

**Note:** Average shipping duration is calculated using the difference between Ship Date and Order Date.

## 9. State-wise Performance Analysis

The state-wise analysis evaluated sales and profitability across different states.

California generated the highest sales of 457,687.63, followed by New York with 310,876.27.

Texas ranked third in sales, generating 170,188.05. However, it recorded the largest state-level loss of 25,729.36.

Ohio and Pennsylvania also reported significant negative profits of 16,971.38 and 15,559.96, respectively.

### Key Insights

- California is the highest sales-generating state.
- New York is the second-largest contributor to sales.
- Texas has high sales but the largest overall loss.
- Ohio and Pennsylvania are also major loss-making states.
- High sales do not necessarily indicate high profitability.

### Business Recommendations

1. Investigate pricing, discounting, and operating costs in Texas.
2. Review loss-making products and customer segments in Ohio and Pennsylvania.
3. Identify successful sales and profitability strategies in California and New York.
4. Monitor state-wise profit margins to identify potential business risks.
5. Develop targeted strategies for improving profitability in loss-making states.

## 10. Overall Business Insights

Based on the exploratory data analysis, the following major business insights were identified:

1. **Strong Technology Performance:** Technology generated the highest category sales of 836,154.03 and profit of 145,454.95.

2. **Regional Performance:** The West region recorded the highest sales of 725,457.82 and profit of 108,418.45.

3. **Product Performance:** Canon imageCLASS 2200 Advanced Copier was the leading product in both sales and profit.

4. **Customer Performance:** Sean Miller generated the highest customer sales, while Tamara Chand generated the highest customer profit.

5. **Loss-Making Products:** Cubify CubeX 3D Printer Double Head Print recorded the largest product-level loss of 8,879.97.

6. **Discount Impact:** Discount levels of 30% and above recorded negative total profits in the aggregated analysis.

7. **Shipping Performance:** Standard Class handled the highest order volume and generated the highest total profit.

8. **State-wise Profitability:** Texas recorded the largest state-level loss of 25,729.36 despite generating 170,188.05 in sales.

## 11. Overall Business Recommendations

Based on the findings, the following actions are recommended:

- Strengthen sales and inventory planning for high-performing products and categories.
- Investigate loss-making products and review their pricing and cost structures.
- Evaluate discount policies to reduce excessive discounting.
- Focus on improving profitability in Texas, Ohio, and Pennsylvania.
- Study successful regional strategies from the West region.
- Develop customer retention strategies for high-value customers.
- Monitor shipping costs and delivery performance across shipping modes.
- Build regular dashboards to track sales, profit, orders, and business performance.

## 12. Conclusion

This project demonstrates how exploratory data analysis can help businesses understand sales performance, product profitability, customer behavior, regional trends, discount patterns, and shipping operations.

Using Python and its data analysis and visualization libraries, meaningful business insights were extracted from 9,994 records.

The analysis highlights opportunities to improve profitability, optimize discount strategies, strengthen regional performance, and support data-driven business decisions.

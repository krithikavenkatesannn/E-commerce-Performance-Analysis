# E-commerce Performance Analysis

## 🎯 Overview

NovaCart Electronics is an online retailer specializing in consumer electronics and accessories across global markets. This analysis explores transactional data from **2019–2022 (100K+ orders)** to understand how sales performance, product mix, logistics, loyalty initiatives, and refunds evolved over time.

The analysis is organized around five business areas:

1. **Sales Trends**: Understanding how revenue, AOV, and order volume changed over time using month-over-month (MoM) and year-over-year (YoY) growth patterns.
2. **Product Performance**: Evaluating which product lines drive revenue versus order volume, and identifying underperforming products.
3. **Marketing & Loyalty Program**: Measuring how loyalty program participation relates to revenue contribution and customer value.
4. **Refund Analysis**: Examining refund rates, high-refund products, and regional refund concentration.

## Entity Relationship Diagram (ERD)
The following diagram illustrates the structure of the transactional dataset, including relationships between orders, customers, products, and purchase attributes.


# Insights Deep Dive
## Sales 
• The business generated approximately $28M in revenue from over 108K orders between 2019 and 2022, with an overall AOV of about $260.

• 2020 was the strongest growth year, with revenue reaching ~$10M and increasing by more than 160% year-over-year, supported by both higher order volume and increased AOV.

• In 2021, order volume continued to grow (≈35K orders), but revenue declined to ~$9M as AOV dropped, indicating a shift toward lower-value purchases.

• Sales declined significantly in 2022 across both revenue and orders, signaling reduced demand compared to the previous two years.

• Sales show consistent seasonality across years, with stronger performance toward the end of the year and lower activity during the February–June period.

 
## Seasonality
• Sales follow a recurring seasonal pattern across all years, with stronger performance in September, November, and December.

• Q4 consistently contributes a disproportionate share of annual revenue compared to earlier months.

• Lower sales activity is observed between February and June across most years, indicating a recurring off-peak demand period.

• Monthly sales in 2022 remain below 2020 and 2021 levels across nearly the entire year, reinforcing the overall decline in demand.

• Late-2020 shows the strongest monthly revenue performance across the dataset, with multiple months exceeding prior-year levels.

## Product Performance & Refunds

• Revenue is concentrated in a small number of premium products. The 27-inch 4K gaming monitor contributes about 35% of total revenue, followed by Apple AirPods (≈28%) and MacBook Air laptops (≈22%).

• Apple AirPods generate the highest order volume, accounting for nearly 45% of all purchases, while gaming monitors contribute a larger share of revenue due to higher pricing.

• Laptop products have the highest average order value, with MacBook Air (~$1,590) and ThinkPad (~$1,100) significantly exceeding other product categories.

• Accessories such as charging cables and webcams generate high order counts but contribute relatively little to overall revenue due to low pricing.

• Refund rates are highest for laptop products, with ThinkPad (~11.7%) and MacBook Air (~11.4%) showing the largest proportion of returns. Apple AirPods have the highest number of refunds due to high purchase volume.

• Overall refund rate across all products is approximately 5%, indicating that most purchases are retained.


## Loyalty Program
• Non-loyalty customers contribute the majority of total revenue (≈61%), while loyalty members account for about 39% of overall sales.

• Loyalty program contribution increases significantly after 2020, with members generating over half of total sales in both 2021 and 2022.

• Order volume from loyalty members grows strongly between 2020 and 2021, indicating increased engagement from enrolled customers.

• Refund rates are slightly higher among loyalty members (~6.2%) compared to non-members (~4.1%), suggesting higher return activity among repeat customers.

• Refund data for 2022 shows zero values across both groups, which may indicate missing data or reporting gaps rather than an actual absence of returns.


## Marketing Channels
• The Direct channel dominates sales, contributing about 83% of total revenue and the majority of orders.

• Email is the second-largest channel, generating roughly 12% of revenue, while affiliate and social media contribute minimal sales.

• The website drives nearly all transactions (≈97% of revenue), with the mobile app contributing only a small share.

• Affiliate purchases show higher AOV, while mobile app orders have the lowest average order value.

## Recommendations

### Sales Performance
- Align inventory planning and promotional campaigns with recurring **Q4 demand peaks**, as late-year months consistently generate higher revenue.
- Monitor the **post-2021 decline in order volume** and update forecasting assumptions to reflect lower demand levels.
- Introduce **bundling or upsell strategies** to improve AOV, which declined after 2020.


### Product Performance
- Continue prioritizing **gaming monitors, AirPods, and laptop products**, which drive the majority of revenue.
- Bundle **low-price accessories** (charging cables, webcams) with high-value products to increase basket size.
- Evaluate **pricing or positioning strategies** for low-revenue products to improve contribution.



### Refund Reduction
- Investigate **higher refund rates for laptop products**, particularly MacBook Air and ThinkPad, to identify potential product or expectation issues.
- Monitor **high refund volume products like AirPods**, which generate the largest number of returns.
- Validate the **absence of refund records in 2022**, as this may indicate incomplete reporting.



### Loyalty Program
- Expand loyalty program adoption, as **loyalty members contribute an increasing share of revenue after 2020**.
- Encourage **higher-value purchases among loyalty members** through tiered rewards or targeted promotions.
- Analyze **return behavior differences between loyalty and non-loyalty customers**.



### Marketing Channels
- Continue investing in **direct and website channels**, which generate the majority of sales.
- Improve **mobile app engagement**, as it contributes a small share of revenue with lower AOV.
- Strengthen **email marketing campaigns**, which remain the second-largest revenue contributor.
- Evaluate **affiliate partnerships**, which generate relatively high AOV purchases.



# 📊 E-commerce Performance Analysis: NovaCart Electronics (2019–2022)


## 📌 Overview

NovaCart Electronics is an online retailer specializing in consumer electronics across global markets. This analysis explores transactional data from **2019–2022** across **108K+ orders** to understand how sales, product mix, loyalty, and refunds evolved over time.

The analysis is organized around four business areas:

1. **Sales Trends**
2. **Product Performance**
3. **Marketing & Loyalty Program**
4. **Refund Analysis**

## 🧩 Entity Relationship Diagram

The diagram below illustrates the structure of the transactional dataset, including relationships between orders, customers, products, and purchase attributes.

![ERD](https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/68c642bc4d94a17c0de5d3a45fd46cf8b485d51d/images/ecommerce_ERD.webp)



## 📊 Executive Summary

![ERD](https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/68c642bc4d94a17c0de5d3a45fd46cf8b485d51d/images/Overall.png)

Between 2019 and 2022, NovaCart generated **$28M in revenue** from **108K orders** with an average order value of **$260**.


**Six key findings:**

1. **Revenue is highly concentrated** — Three products (gaming monitor, AirPods, MacBook) drive **85% of total revenue**. A single product issue would materially impact the business.

2. **2020 spike, 2022 decline** — Revenue peaked in 2020 at approximately **$10M** (+160% YoY), then declined by an estimated **$4-5M by 2022**. The decline spans nearly all premium categories.

3. **Laptop refunds are a cost center** — ThinkPad (**11.7%**) and MacBook Air (**11.4%**) refund rates are double the **5%** company average. At current volume, this represents a significant annual cost requiring investigation.

4. **Loyalty program is gaining traction** — Members grew from **11% of revenue (2019)** to **55% (2022)**. However, members show slightly higher refund rates (**6.2%** vs **4.1%**), warranting further analysis.

5. **Q4 drives the year** — September through December consistently outperform other months. February through June is a recurring off-peak period.

6. **Channel concentration risk** — Direct and Website channels drive **83% of revenue**. Mobile app contributes only **3%** with significantly lower AOV (**$47** vs **$305** for website).




## 🔍 Deep Dive: Sales Performance
![ERD](https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/cf3e0ac88092cc55cf309a0e9123162a3c795b05/images/yoy.png)


The business generated **$28M** in revenue from over **108K orders** between 2019 and 2022, with an overall AOV of **$260**.

* **2020 was the breakout year.** Revenue reached approximately **$10M**, growing more than **160%** year-over-year. Both order volume and AOV contributed to this growth.

* **2021 showed a shift.** Order volume continued to grow to approximately **35K orders**, but revenue declined to **$9M** as AOV dropped from **$300 to $255**. This suggests a shift toward lower-value purchases, driven by AirPods (low AOV) growing to **45%** of order volume while laptop share declined.

* **2022 saw significant decline.** Revenue dropped across nearly all major product categories. Gaming monitor revenue fell from peak levels above **$300K** per month to nearly half by mid-2022. The estimated revenue loss compared to 2021 is **$4-5M**.

* **Seasonality is consistent.** Sales follow a recurring pattern across all years, with stronger performance in September, November, and December. Q4 consistently contributes a disproportionate share of annual revenue. Lower sales activity occurs between February and June — a recurring off-peak period.



## 🔍 Deep Dive: Product Performance & Refunds
![ERD](https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/cf3e0ac88092cc55cf309a0e9123162a3c795b05/images/Product%20Performance.png)


* **Revenue concentration is extreme.** The 27-inch 4K gaming monitor contributes **35%** of total revenue. Apple AirPods follow at **28%**, and MacBook Air laptops at **22%**. Together, these three products drive **85%** of all revenue.

* **Volume tells a different story.** Apple AirPods generate the highest order volume, accounting for nearly **45%** of all purchases. Gaming monitors contribute a larger share of revenue despite lower volume due to higher pricing (**$421** AOV vs **$160** for AirPods).

* **Laptops drive high value but high risk.** MacBook Air (**$1,591** AOV) and ThinkPad (**$1,101** AOV) have the highest average order values. However, they also have the highest refund rates — **11.4%** for MacBook Air and **11.7%** for ThinkPad — double the company average of **5%**.

* **Accessories are low impact.** Products like Samsung charging cable packs (**$20** AOV) and webcams (**$50** AOV) generate high order counts but contribute little to overall revenue.

* **Overall refund rate is manageable.** At approximately **5%**, most purchases are retained. But laptop refunds represent a clear cost center requiring investigation.




## 🔍 Deep Dive: Loyalty Program
![ERD](https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/68c79b3cfd492e761330fa25c553892bb9346292/images/Loyalty%20Program.png)


* **Loyalty adoption grew significantly.** In 2019, loyalty members contributed only **11%** of revenue. By 2022, that share had grown to **55%**. Members now drive more than half of all sales.

* **Order volume from members grew strongly** between 2020 and 2021, indicating increased engagement from enrolled customers.

* **Refund rates differ by segment.** Loyalty members show slightly higher refund rates (**6.2%**) compared to non-members (**4.1%**). This may reflect higher engagement (more orders = more return opportunities) rather than product issues. Further analysis on refunds per order, not just per customer, is needed.

* **2022 refund data is incomplete.** Refund records show zero values across both groups for 2022. This is likely missing data rather than an actual absence of returns.




## 🔍 Deep Dive: Marketing Channels
![ERD](https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/68c79b3cfd492e761330fa25c553892bb9346292/images/Marketing.png)


* **Direct channel dominates.** Direct contributes **83%** of total revenue and the majority of orders. Email is the second-largest channel, generating roughly **12%** of revenue. Affiliate and social media contribute minimal sales.

* **Website vs mobile app.** The website drives nearly **97%** of revenue with an AOV of **$305**. The mobile app contributes only **3%** of revenue with an AOV of just **$47** — a significant underperformance.

* **Affiliate shows higher AOV.** Affiliate purchases have an AOV of **$305**, matching website performance, but volume is low.

* **Email remains the only meaningful secondary channel** at **12%** revenue share. This represents an opportunity for increased investment.



## 📏 Metrics Definition

1. **Revenue:** Total sales in USD across all products and years.

2. **Average Order Value (AOV):** Total revenue divided by number of orders. Measures purchase intensity.

3. **Refund Rate:** Percentage of orders that were refunded. Measures product quality and customer satisfaction.

4. **Loyalty Share:** Percentage of revenue contributed by loyalty program members.


## ✅ Conclusion

* NovaCart experienced strong growth in 2020, driven by premium electronics demand. However, 2022 saw a significant decline of approximately **$4-5M** in revenue compared to peak levels.

* The business faces **concentration risk** — three products drive **85%** of revenue. Laptop refund rates at **11%** represent a clear cost center. The loyalty program is gaining traction, with members now driving over half of revenue, but channel concentration (Direct + Website at **83%**) leaves limited diversification.

* The 2022 decline and missing refund data require immediate investigation before forecasting 2023 performance.



## 📌 Recommendations

### Sales Performance
- Align inventory and promotions with **Q4 demand peaks** (September–December). The 2020 Q4 spike reached approximately **$350K** monthly for gaming monitors alone.
- Investigate **2022 decline drivers** — quantify whether this is demand, pricing, or competition before forecasting 2023.

### Product Performance
- **Diversify revenue concentration** — Test two mid-tier products (**$200-500** range) to reduce reliance on three SKUs representing **85%** of revenue.
- **Bundle specifically** — Attach Samsung charging cables (**$20**) to MacBook Air (**$1,590**) purchases. At **10%** attachment, this adds estimated annual revenue.

### Refund Reduction
- **Prioritize laptop refund investigation** — **11%** refund rate vs **5%** average. Review product descriptions, quality control, and customer expectations.
- **Validate 2022 refund data** before making return policy decisions.

### Loyalty Program
- **Expand program aggressively** — Members now drive over **55%** of revenue. Run Q3 sign-up campaign targeting high-value non-members.
- **Analyze member refund behavior** — Calculate refunds per order (not per customer) to determine if higher rates reflect engagement or product issues.

### Marketing Channels
- **Test mobile app push notifications** — Current **3%** revenue share with **$47** AOV is underperforming. A **2pp** lift would add estimated revenue.
- **Double down on email** — Second-largest channel at **12%** revenue. Test increased frequency before Q4.



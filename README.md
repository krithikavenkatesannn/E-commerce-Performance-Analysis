# 📊 E-commerce Performance Analysis: NovaCart Electronics 

## 📌 Overview
* NovaCart Electronics is an online retailer specializing in consumer electronics across global markets. This analysis examines transactional data from **2019–2022** across **108K+ orders** to understand how revenue drivers, product mix, loyalty adoption, and refund behavior evolved over time.

* The objective of this analysis is to identify **growth drivers, risks, and operational opportunities** to improve future commercial performance.

## 📊 Executive Summary
<p align="center">
  <img src="https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/06a416323df88e82abd1f532c1393b84b71106ab/images/z-mom.png" width="800"/>
</p>

* Between 2019 and 2022, NovaCart generated **$28M in revenue** from **108K orders**, with an average order value of **$260**.

**Key insights**

1. Revenue concentration risk — Three products (Gaming Monitor, AirPods, MacBook) generate **85% of total revenue**, creating dependency on a limited SKU set.
2. Pandemic-driven growth followed by correction — Revenue peaked in **2020 (~$10M)** and declined steadily through **2022**, indicating normalization of demand.
3. Laptop refunds are disproportionately high — ThinkPad (**11.7%**) and MacBook Air (**11.4%**) exceed the **~5% company average**.
4. Loyalty program became a major revenue driver — Loyalty share increased from **11% (2019)** to **55% (2022)**.
5. Strong seasonality pattern — Revenue peaks in **September–December**, while **February–June** represents recurring demand slowdown.
6. Channel concentration risk — Direct channel drives **83% of revenue** by acquisition source. Website accounts for **97% of revenue** by platform, while Mobile App contributes only **~3%** with a significantly lower AOV (**$47** vs **$305**).

Note: Refund data for 2022 appears incomplete (zero values), suggesting missing records rather than operational improvement.

## 🧩 Entity Relationship Diagram
<p align="center">
  <img src="https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/06a416323df88e82abd1f532c1393b84b71106ab/images/ecommerce_ERD.webp" width="800"/>
</p>

## 📈 Year-over-Year Insights
<p align="center">
  <img src="https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/06a416323df88e82abd1f532c1393b84b71106ab/images/z--yoy.png" width="800"/>
</p>

- 2020 represents the breakout year, with revenue increasing to approximately **$10M** and orders growing over **100% YoY**, likely driven by pandemic-related electronics demand.
- 2021 shows demand normalization where order volume increased but revenue declined due to lower AOV, indicating shift toward lower-priced products.
- 2022 experienced a broad-based decline across premium categories, suggesting contraction in overall demand.
- Order volume remained relatively stable despite revenue decline, indicating reduced purchase value rather than reduced customer activity.

## 📅 Seasonality Insights
<p align="center">
  <img src="https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/06a416323df88e82abd1f532c1393b84b71106ab/images/z-seasonality.png" width="800"/>
</p>

- Sales follow a consistent seasonal pattern with demand peaking between **September and December**.
- Q4 contributes a disproportionate share of annual revenue, highlighting importance of inventory and marketing alignment.
- February through June represents a recurring off-peak period across all years.
- Seasonal trend weakens in 2022, indicating structural demand slowdown beyond typical seasonality. October 2022 recorded the sharpest single-month decline across the entire dataset at **-55.2%**, confirming the 2022 contraction was not seasonal noise but a structural shift.

## 📦 Product Performance & Refund Insights
<p align="center">
  <img src="https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/06a416323df88e82abd1f532c1393b84b71106ab/images/z-product%20%26%20refund%20(2).png" width="800"/>
</p>

- Revenue concentration is significant, with Gaming Monitor (**35%**), AirPods (**28%**), and MacBook Air (**22%**) generating **85% of total revenue**.
- AirPods drive **45% of orders** but lower AOV, while laptops generate higher revenue per order.
- Laptops present high value but high risk, with refund rates above **11%**.
- Accessories contribute limited revenue impact despite moderate order volume.
- Overall refund rate remains manageable (~5%), but laptop returns represent disproportionate cost center.

## 🎯 Loyalty Program Insights
<p align="center">
  <img src="https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/06a416323df88e82abd1f532c1393b84b71106ab/images/z-loyalty%20(2).png" width="800"/>
</p>

- Loyalty adoption increased from **11% of revenue (2019)** to **55% (2022)**.
- Order volume from loyalty members increased steadily, indicating repeat purchase behavior.
- Loyalty members show slightly higher refund rates, likely due to higher engagement.
- 2022 refund data appears incomplete and requires validation.

## 📢 Marketing Channel Insights
<p align="center">
  <img src="https://github.com/krithikavenkatesannn/E-commerce-Performance-Analysis/blob/06a416323df88e82abd1f532c1393b84b71106ab/images/z-traffic..png" width="800"/>
</p>

- Direct channel dominates as the primary acquisition source, contributing **83% of revenue**.
- Website accounts for **97% of revenue** by platform, while Mobile App contributes only **~3%** with a significantly lower AOV (**$47** vs **$305** for website).
- Affiliate channel shows strong AOV but low volume.
- Email represents the strongest secondary acquisition channel (~12% revenue).

## 📌 Recommendations

## Sales

* **Account for post-pandemic demand normalization**  
Sales surged in 2020 due to increased demand for home office and entertainment electronics, but declined steadily through 2022. This suggests demand has returned to baseline levels. Inventory planning and forecasting should therefore avoid assuming continued high growth and instead align with stabilized demand.

* **Prioritize high-revenue products during peak months**  
Gaming monitors, AirPods, MacBook Air, and ThinkPad laptops generate the majority of revenue. These products should be prioritized in inventory allocation and promotional campaigns, particularly between September and December when seasonal demand consistently peaks.

* **Leverage high AOV laptop purchases**  
Laptops generate the highest average order values (≈$1300), making them strong revenue drivers. Bundling accessories, offering extended warranties, or introducing financing options can increase conversion rates and overall basket size.

* **Improve performance of underperforming products and off-peak months**  
Lower-performing products contribute a small share of revenue, and sales decline between February and June. Targeted promotions, bundle offers, or repositioning low-impact items as add-ons could help improve demand during these periods.

## Loyalty Program

* **Expand loyalty adoption to stabilize repeat revenue**  
Loyalty contribution increased from 11% to over 50% of revenue, indicating strong repeat purchase behavior. Expanding the program through incentives and exclusive benefits could create a more predictable revenue base.

* **Leverage increasing AOV among loyalty members**  
Loyalty members show rising AOV over time, suggesting higher engagement. Tiered rewards or spend-based incentives could further encourage larger purchases.

* **Convert high-value non-loyalty customers**  
Non-loyalty customers still contribute significant revenue. Offering signup incentives or personalized promotions could help convert these customers into repeat buyers.

## Refunds

* **Investigate high refund rates for laptops**  
ThinkPad (342 refunds × $1,101 AOV) and MacBook Air (453 refunds × $1,591 AOV) represent an estimated **~$1.1M in refunded revenue** — more than double the company average refund rate of 5%. Reviewing product descriptions, specifications, and customer expectations should be prioritized immediately.

* **Analyze high-volume refund products**  
AirPods and Gaming Monitors generate the largest number of refunds due to high sales volume. Improving product information, compatibility guidance, and post-purchase support could reduce return frequency.

* **Validate missing refund data in 2022**  
Refunds drop to zero in 2022, which likely indicates incomplete data rather than operational improvement. This should be verified before implementing policy changes.

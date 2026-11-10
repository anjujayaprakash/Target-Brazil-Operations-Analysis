# Target Brazil: E-Commerce Operations & Growth Analysis
### 📊 End-to-End SQL Case Study (100,000+ Orders)

## 📋 Project Overview
Target is a global retail giant. This project analyzes their Brazilian operations using a dataset of **100k orders** from **2016 to 2018**. 

**The Goal:** Extract actionable insights on sales growth, customer behavior, and logistics efficiency to provide recommendations for business expansion.

## 🔍 Key Business Insights

#### 📈 1. Explosive Revenue Growth
* Analyzed revenue from Jan-Aug 2017 vs. Jan-Aug 2018.
* **Result:** Discovered a **136.98% growth rate** in payment values year-over-year.

#### 2. Logistics & Shipping Efficiency
* **Top Performer:** **São Paulo (SP)** has the highest order volume and the lowest average freight cost ($15.15).
* **Speed Advantage:** The state of **Acre (AC)** delivers orders nearly **20 days faster** than the estimated delivery date.
* **Bottleneck:** States like **RR and AP** show the highest average delivery times.

#### 🕒 3. Consumer Behavior
* **Peak Hours:** Brazilian consumers are most active in the **Afternoon (1:00 PM - 6:00 PM)**.
* **Payment Habits:** **Credit Cards** are the dominant payment method, with a massive peak in November (Black Friday).

* ## 🛠️ Tech Stack & Skills
* **Tool:** Google BigQuery (Cloud SQL)
* **Data Cleaning:** Handled timestamp conversions and localized geographic data.
* **Advanced SQL:** CTEs, Subqueries, Window Functions, and Date Aggregations.

####    RECOMMENDATIONS WITH ANALYSIS

* #### 1. Demand and seasonality

  **Analysis:** Orders grew from 800 in Jan 2017 to a peak of 7,544 in Nov 2017, then dropped to 5,673 in Dec.
  **Comments:** Build inventory, staffing and logistics capacity ahead of Q4, especially November. Run campaigns in the weaker months (Jan to Apr) to smooth demand.

  #### 2. Time-of-day behaviour
    **Analysis:** Afternoon has 38,135 orders, then night (28,331), morning (27,733) and dawn (5,242).
**Comments:** Schedule push notifications, flash sales and email campaigns for the afternoon and evening. Staff customer support for those peaks. Dawn is a low-traffic window suited to maintenance or system updates.

  #### 3. Delivery and logistics
**Analysis: (1)** Northern states have the slowest deliveries (RR ~29 days, AP ~27, AM ~26), while SP takes ~8 days.
**Comments:** Partner with regional carriers or set up fulfillment hubs for the North and Northeast. Consider consolidating shipments to reduce transit time.
**Analysis: (2)** The states with the longest deliveries (AC, RO, AP, AM, RR) are also the ones delivered 16 to 20 days before the estimate.
**Comments:** Delivery estimates there are heavily padded. Tightening them would make the promise more competitive and improve conversion, as long as reliability holds.

 #### 4. Freight pricing
**Analysis:** Average freight is ~R$15 in SP versus R$39 to R$43 in RR, PB, RO, AC and PI.
**Comments:** Offer free-shipping thresholds or subsidized freight for high-cost states to reduce cart abandonment, and negotiate carrier rates in those regions. Compare freight to item price, since high freight on low-priced items hurts conversion most.
 
  #### 5. Geographic expansion
**Analysis:** RR, AP and AC have the fewest customers (46, 68, 81), but average order values there are among the highest (~R$230 in AC and AP).
**Comments:** Customers in remote states spend more per order when they do buy. Improving delivery speed and freight cost could unlock growth there. Meanwhile, keep prioritizing SP, RJ and MG, which drive most revenue.
 
  #### 6. Payments
**Analysis:** About 49,000 orders (roughly half) are paid in one installment, credit card dominates, and there is a noticeable bump at 10 installments (5,315 orders).
**Comments:** Promote interest-free installment plans (especially 6 and 10) on high-ticket items to lift basket size. Keep credit card and UPI as the primary options, and review whether voucher and debit payments deserve more promotion.
 
  #### 7. Growth
**Analysis:** Jan to Aug payment value rose ~137% from 2017 to 2018.
**Comments:** Treat this as a sign of strong momentum, and invest in the infrastructure above so service quality scales with volume.




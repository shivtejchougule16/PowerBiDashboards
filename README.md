# Power BI Dashboards

Five end-to-end Power BI dashboard projects covering data cleaning, data modeling, KPI design and business insights. Each project has its Power BI report (`.pbix`) and, where available, its source data.

**Tools:** Power BI Desktop, Excel, SQL, Python (Pandas, Matplotlib, Seaborn)

| # | Project | Domain | Data size | Report file |
|---|---------|--------|-----------|-------------|
| 1 | Diwali Sales Dashboard | Retail / E-commerce | 15,000 orders, 28 states | `Diwali_Data_Dashboard.pbix` |
| 2 | Cafe Sales Analysis | Food & Beverage | 200 orders (Jan-Jun 2025) | `Cafe_Dashboard.pbix` |
| 3 | E-Commerce Sales Dashboard | E-commerce | 200 orders, 150 customers | `E_Commerce_Dashboard.pbix` |
| 4 | AI Impact on Jobs | Labour market | 120 records, 6 industries | `AI_Impact_On_Job.pbix` |
| 5 | EV Bike Data Dashboard | Automotive | Brand and model level | `EV_Bike_Data_Dashboard.pbix` |

---

## 1. Diwali Sales Dashboard
**Data:** `Diwali_Dashboard_2.csv` | 15,000 orders, 7,259 customers, 28 states (2025)

**Business question:** How do sales vary across product categories, payment methods and delivery outcomes?

**Key findings**
- Total revenue of ₹111.8 Cr with an average order value of ₹74.5K.
- Revenue is spread almost evenly across the 5 categories (Beauty, Electronics, Books, Clothing, Home & Kitchen), each about 19-20%.
- 32.5% of orders are "Returned" and 33.6% are "Pending", an unusually high share that would need investigation in a real business.

**Dashboard:** total sales KPI, sales by category (column), payment-method donut, sales trend (line), review rating by category and delivery status, state slicer.

---

## 2. Cafe Sales Analysis
**Data:** `Cafesales.xlsx` | 200 orders, Jan-Jun 2025

**Business question:** Which products and times of day drive the most sales?

**Key findings**
- Total revenue of ₹1.11 lakh, average order value ₹556.
- **Evening** is the peak period with 38.6% of revenue (about ₹43K); Morning is the lowest at 17.1%.
- Fries, Pizza and Burger together contribute about 65% of revenue.
- Monthly revenue grew from ₹11.7K (Jan) to ₹30.4K (Jun), about 2.6x, with the sharpest rise in June.
- Cash is the most used payment method (41%); digital payments are present but underused.
- **Recommendation:** Morning and beverage sales have growth potential, for example through meal-plan promotions.

**Dashboard:** total sales KPI, sales trend (stacked area), sales by time of day (donut), payment method (treemap), product sales (funnel), decomposition tree, product slicer, price KPIs (average Pizza sale, max and min unit price). Page 2 contains the written analysis and business summary.

---

## 3. E-Commerce Sales Dashboard
**Data:** `ECommerce_dataset.xlsx` | 200 orders, 150 customers, 7 countries

**Business question:** Which categories, countries and customers generate the most revenue, and how healthy is order fulfilment?

**Key findings**
- Total revenue of 105.7K, average order value 528.
- **Home** (38.5%) and **Electronics** (27.9%) generate about 66% of revenue.
- **USA** is the top market with 36% of revenue; Credit Card is the most used payment method (55%).
- 85% of orders are delivered; only 1.6% are returned or cancelled; 98% of reviews are positive.

**Dashboard:** revenue KPI, category funnel, country combo chart, payment-method pie, gender donut, revenue trend (line), country slicer.

---

## 4. AI Impact on Jobs
**Data:** `AIjobimpact.xlsx` | 120 records, 6 industries, 39 locations

**Business question:** Which industries are most exposed to automation, and where are jobs growing?

**Key findings**
- **Manufacturing** has the highest average automation risk (about 75%) and is the only industry with a projected decline in job openings (-12% by 2030).
- **IT** shows the strongest growth (+59% openings by 2030), with a 70% average remote-work ratio and about $94K average salary.
- Total openings across all industries are projected to grow from 1.85M (2024) to 2.30M (2030), about +24%.

**Dashboard:** salary and projected-openings KPIs, salary by industry (donut), remote-work ratio (pie), projected openings 2030 (funnel), decomposition tree (industry, AI impact level, job status), location slicer.

---

## 5. EV Bike Data Dashboard
**Business question:** How do electric bike brands and models compare on sales, price, range and top speed?

**Dashboard:** sales units by brand (column), price, range (km) and top speed by model, total sales units KPI, brand slicer.

---

## How to open
1. Install [Power BI Desktop](https://powerbi.microsoft.com/desktop/) (free, Windows).
2. Download the `.pbix` file of the project you want to explore.
3. Open it in Power BI Desktop and use the slicers to filter the data.

## Screenshots
Add a screenshot of each dashboard here, for example:

```
![Cafe Sales Dashboard](screenshots/cafe_dashboard.png)
```

## About me
**Shivtej Chougule**, aspiring Data Analyst (SQL, Excel, Power BI, Python).
[LinkedIn](https://www.linkedin.com/in/shivtej-chougule-723360414) | shivtejchougule16@gmail.com

# Promo Impact Dashboard: Measuring Promotion Effectiveness

## Table of content

## Project Overview

This project presents an end-to-end marketing analytics solution designed to measure the effectiveness of promotional campaigns across various product categories, customer segments, and regions. It uses a comprehensive, business-like dataset (10,000+ rows) to simulate real-world promotional activities over a 12-month period and analyzes the return on investment (ROI), sales lift, discount impact, and customer behavior.

The final dashboard was built in Google Looker Studio and integrates insights from Excel-based data modeling


## Project Objectives

- Track and compare ROI of different promotions types
- Identify which product categories and promo types perform best
- Measure sales lift before, during, and after promotions
- Visualize performance across regions, sales channels, and customer types
- Present clear insights and business recommendations

## Tools used and their purpose

- Excel Data preparation, cleaning, and metric creation
- Google Sheets Hosting dataset for Looker Studio integration
- Looker Studio Visualization, dashboard, filtering, insights

## Dataset Description
- Total rows: 10,000+
- Duration: 12 months
- Simulated promotional data, including:
- Product Name, Category, Price
- Promo Type (e.g., 10% OFF, Flash Sale, BOGO)
- Promo Phase (Before, During, After, None)
- Promo Applied, Discount %, Promo Cost
- Revenue, Discount
- Customer Info: ID, Segment, Age Group, Gender
- Sales Channel: In-store or Online
- Location: Country
- Sales Rep ID, Inventory Level


## Metrics calculated in Excel and their formula
- Revenue = Unit Price × Units sold
- Discount % = discount/100
- Discounted Revenue = Revenue × (1 - discount %)
- Promo cost = Unit Price × Units sold × discount %


## Metrics calculated in looker Studio

- ROI = (Discounted Revenue - Promo Cost) / Promo Cost
- Sales Lift = Units During - Units Before
- Net Revenue = Discounted Revenue - Promo Cost


## Dashboard Features

The Looker Studio dashboard includes:

🔹 KPI Scorecards: Revenue, net revenue, Promo Cost, ROI, sales volumn

🔹 ROI by Promo Type: Bar chart comparing efficiency

🔹 Sales Volume by Product Category

🔹 Promo Phase Impact: Revenue before, during, after

🔹 Sales Lift Charts: Measures increase due to promo

🔹 ROI Over Time: Trend across the year

🔹 ROI by Country/Region: Geographic breakdown

🔹 Customer Segmentation Filters: Age group, gender, type

🔹 Sales Channel Comparison: Online vs In-Store



---

💡 Key Insights

10% OFF delivered the highest ROI (~600%), but also had the lowest sales volume

Flash Sale had strong ROI and moderate volume — a balanced promo

After-promo phase saw higher sales than “During”, indicating a delayed promo response

Hair Care & Fragrance categories performed best under promotions

Certain regions had high ROI but low volume — opportunity for scaling



---

🧠 How I Told This Story (Optional Narration)

🎯 The Business Problem

> Our marketing team regularly runs promotions — from discounts to flash sales — but there's been no structured way to measure which campaigns actually drive results. We needed a clear answer: "Which promos worked best, and were they worth the cost?"



🧾 The Dataset

> I worked with a realistic dataset of 10,000+ records, simulating 12 months of activity with variables like customer segmentation, promo type, revenue, and region.



📊 The Dashboard

> Built in Looker Studio, it includes KPIs, charts, filters, and calculated fields to analyze ROI, sales lift, and promo performance over time.



🔍 Discoveries

10% OFF = Highest ROI, lowest volume → profitable but niche

Flash Sale = Good balance between cost and engagement

After-phase = Shows strong post-promo performance

Hair Care = Most promo-responsive category

Some regions = High ROI but low volume → expansion potential


✅ Business Impact

Grace Sunday, [25/06/2025 22:03]
> This dashboard empowers the team to allocate budgets better, prioritize high-performing promotions, and target the right products and segments. It turns raw data into actionable marketing decisions.




---

📎 Conclusion

This project showcases both technical skill and business thinking — from preparing data in Excel, to modeling ROI and sales lift, to building a clean dashboard in Looker Studio, and finally to communicating results through meaningful insights.

Perfect for marketers, analysts, and decision-makers who want to measure the real impact of their campaigns.



✅ Your README is ready! It includes:

A professional project overview

Tools, dataset, formulas, and dashboard features

Key insights and business value

A full storytelling script as an optional “How I Told This Story” section

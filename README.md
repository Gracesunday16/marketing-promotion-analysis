# Promo Impact Dashboard: Measuring Promotion Effectiveness

## Table of content

## Project Overview

This project presents an end-to-end marketing analytics solution designed to measure the effectiveness of promotional campaigns across various product categories, customer segments, and regions. It uses a comprehensive, business-like dataset (10,000+ rows) to simulate real-world promotional activities over a 12-month period and analyzes the return on investment (ROI), sales lift, discount impact, and customer behavior.The final dashboard was built in Google Looker Studio and integrates insights from Excel-based data modeling   

## The Business Problem

Our marketing team regularly runs promotions — from discounts to flash sales — but there's been no structured way to measure which campaigns actually drive results. We needed a clear answer: "Which promos worked best, and were they worth the cost, which country should we increase promotional investment and what month of the year is best for promotion?"

## Project Objectives

- Track and compare ROI of different promotions types
- Identify which product categories and promo types perform best
- Measure sales lift before, during, and after promotions
- Visualize performance across regions, sales channels, and customer types
- Present clear insights and business recommendations
- 
## veiw live dashboard
https://lookerstudio.google.com/reporting/0023ec68-fadd-40c0-97a6-084b0cb528af

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

** The Looker Studio dashboard includes:**

- KPI Scorecards: Revenue, net revenue, Promo Cost, ROI, sales volumn
- ROI by Promo Type: Bar chart comparing efficiency
- Sales Volume by Product Category
- Promo Phase Impact: Revenue before, during, after
- Sales Lift Charts: Measures increase due to promo
- ROI Over Time: Trend across the year
- ROI by Country/Region: Geographic breakdowm
- Customer Segmentation Filters: Age group, gender, type
- Sales Channel Comparison: Online vs In-Store

## Key Insights

10% OFF delivered the highest ROI (~600%), but also had the lowest sales volume

20% OFF had strong ROI and moderate volume — a balanced promo

After-promo phase saw higher sales than “During”, indicating a delayed promo response

Hair Care & Fragrance categories performed best under promotions

Certain regions had high ROI but low volume — opportunity for scaling

Key Insights

10% OFF delivered the highest ROI (~600%), but also had the lowest sales volume

Flash Sale had strong ROI and moderate volume — a balanced promo

After-promo phase saw higher sales than “During”, indicating a delayed promo response

Hair Care & Fragrance categories performed best under promotions

Certain regions had high ROI but low volume — opportunity for scaling



---

🕵️‍♀️ Insights & Recommendations

🔹 1. Invest More in High-ROI Countries

Countries such as [insert top country from your dashboard] delivered strong ROI despite lower volume. These regions are ideal for increased promotional budget allocation to test for higher market response.

🔹 2. Rethink Low-Volume High-ROI Strategies

10% OFF promotions yielded excellent ROI but reached fewer customers. These promos are cost-efficient but may need stronger marketing or bundling to scale.

🔹 3. Maximize the “After” Phase Effect

Significant revenue was recorded in the post-promo period, suggesting that customers often buy after the official promo ends. This supports running post-promo reminders or limited-time extensions.

🔹 4. Double Down on Top Product Categories

Categories like Hair Care responded especially well to promos. Focusing campaigns on these categories can drive higher ROI with less experimentation.

🔹 5. Flash Sale = Best of Both Worlds

Flash Sale promos showed strong ROI and moderate volume. This balance makes them ideal for wide campaigns where both profit and engagement matter.

🔹 6. Use Data to Refine Strategy

Rather than applying a uniform promo strategy, results show the need to tailor promos by region, customer segment, and product type.

## Business Impact
This dashboard empowers the team to allocate budgets better, prioritize high-performing promotions, and target the right products and segments. It turns raw data into actionable marketing decisions.

## Conclusion

This project showcases both technical skill and business thinking — from preparing data in Excel, to modeling ROI and sales lift, to building a clean dashboard in Looker Studio, and finally to communicating results through meaningful insights.
Perfect for marketers, analysts, and decision-makers who want to measure the real impact of their campaigns.

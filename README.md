# 📊 Promo Impact Dashboard: Measuring Promotion Effectiveness using Excel and Looker studio

![Promo Dashboard](dashboard-overview.png)

🎯 [Click here to view the full interactive dashboard](https://lookerstudio.google.com/reporting/0023ec68-fadd-40c0-97a6-084b0cb528af)

## Table of content
- [Project Overview](#project-overview)
- [The Business Problem](#the-business-problem)
- [Why This Project Matters](#why-this-project-matters)
- [Project Objectives](#project-objectives)
- [Tools and Technologies ](#tools-and-technologies)
- [Dataset Description](#dataset-description)
- [Metrics calculated in Excel](#metrics-calculated-in-excel)
- [ Metrics calculated on looker Studio ](#metrics-calculated-on-looker-studio)
- [Dashboard Features](#dashboard-features)
- [Key Insights](#key-insights)
- [Recommendations](#recommendations)
- [Business Impact](#business-impact)
- [Conclusion](#conclusion)
- [Contact](#contact)
 
## Project Overview

This project presents an end-to-end marketing analytics solution designed to measure the effectiveness of promotional campaigns across various product categories, customer segments, and regions. It uses a comprehensive, business-like dataset (10,000+ rows) to simulate real-world promotional activities over a 12-month period and analyzes the return on investment (ROI), sales lift, discount impact, and customer behavior.The final dashboard was built in Google Looker Studio and integrates insights from Excel-based data modeling   

## The Business Problem

Our marketing team regularly runs promotions — from discounts to flash sales — but there's been no structured way to measure which campaigns actually drive results. We needed a clear answer: "Which promos worked best, and were they worth the cost, which country should we increase promotional investment and what month of the year is best for promotion?"


## 🌟 Why This Project Matters

Promotions are a major part of marketing budgets, but without proper analysis, companies can’t tell which campaigns are truly profitable. This project helps bridge that gap by using data to measure the real return on investment (ROI) and sales lift of different promotions across product categories, regions, and customer types.

By visualizing promo performance, this dashboard supports smarter decision-making — helping marketing and operations teams invest where it matters most.


## Project Objectives

- Track and compare ROI of different promotions types
- Identify which product categories and promo types perform best
- Measure sales lift before, during, and after promotions
- Visualize performance across regions, sales channels, and customer types
- Present clear insights and business recommendations

  
## Tools and Technologies

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


## Metrics calculated in Excel
I calculated the following metrics on Excel

- Revenue = Unit Price × Units sold
- Discount % = discount/100
- Discounted Revenue = Revenue × (1 - discount %)
- Promo cost = Unit Price × Units sold × discount %

## Metrics calculated on looker Studio
The following KPI's were calculated on looker studio
- ROI = (Discounted Revenue - Promo Cost) / Promo Cost
- Net Revenue = Discounted Revenue - Promo Cost


## The Looker Studio Dashboard Features

- KPI Scorecards: Net revenue, Promo Cost, ROI, sales volumn
- ROI by Promo Type: Bar chart comparing efficiency
- Sales Volume and ROI by Product Category
- ROI Over Time: Trend across the year
- Distribution of ROI by Promo Cost
- ROI by Country: Geographic breakdowm
- Insights

## Key Insights

- 10% OFF delivered the highest ROI (~600%), but also had the lowest sales volume

- 20% OFF had strong ROI and highest volume — a balanced promo

- Skin Care categories performed best under promotions with higest ROI and sales volumn

- Certain regions had high ROI but low volume — opportunity for scaling

- ROI peaked in January, April and October, showing strong promotional efficiency. ROI dropped to 0% in November and December, likely due to no campaign activity.
  Overall, ROI varied across months, suggesting that not all promos yielded strong returns and highlighting the need to identify what worked best in high-performing periods and implementing it 

**✅ Recommendations**

**1. Reconsider Low-Volume High-ROI Strategies**

10% OFF promotions yielded excellent ROI but reached fewer customers. These promos are cost-efficient but may need stronger and wider marketing to scale.

**2. 20% OFF = Best of Both Worlds**

20% OFF promos showed strong ROI and highest volume. This balance makes them ideal for wide campaigns where both profit and engagement matter.

**3. Double Down on Top Product Categories**
   
Categories like Skin Care responded very well to promos. Focusing campaigns on these categories can drive higher return on investment.

**4. Invest More in High-ROI Countries**
   
Countries such as (Brazil and Canada) are ideal for increased promotional budget allocation to get higher return on investment.

**5. Seasonal Strategy**
   
Future promotional campaigns should be strategically scheduled around January, April and October, as these periods delivered the highest ROI. Focus on replicating successful strategies used during these months to maximize efficiency and returns.


## Business Impact
This dashboard empowered the team to allocate budgets better, prioritize high-performing promotions, and target the right products. It turned raw data into actionable marketing decisions.

## Conclusion

This project showcases both technical skill and business thinking — from preparing data in Excel, to modeling ROI and sales lift, to building a clean dashboard in Looker Studio, and finally to communicating results through meaningful insights.
Perfect for marketers, analysts, and decision-makers who want to measure the real impact of their campaigns.

## ⚠️ Limitations

This project is based on a synthetic dataset. While the structure reflects real-world promotional scenarios, some results may not fully reflect real business conditions. These limitations were noted during analysis and offer opportunities for further refinement in future iterations.

## Contact
Grace Sunday

[LinkedIn](https://www.linkedin.com/in/grace-sunday-b2b0622a6)

gracesunday16@gmail.com



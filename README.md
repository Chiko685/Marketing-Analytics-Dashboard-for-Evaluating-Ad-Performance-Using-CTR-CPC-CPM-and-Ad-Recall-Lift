# Marketing Analytics Dashboard: Evaluating Ad Performance


<img width="1535" height="1151" alt="Dashboard 1" src="https://github.com/user-attachments/assets/4bffe4e6-cc74-4a1b-9e8e-298172baddf6" />



## 📌 Project Overview

This project focuses on analyzing and evaluating the effectiveness of digital marketing campaigns across various ad types. By utilizing key performance indicators (KPIs) such as CTR, CPC, CPM, and Ad Recall Lift, this dashboard provides deep insights into cost efficiency and the brand awareness impact of different advertising strategies.

View Dashboard on Tableau Public: [https://public.tableau.com/views/MarketingAnalyticsDashboard_17711404071840/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]

## 📊 Key Metrics & Glossary
To better understand the analysis, here are the definitions of the metrics used:

CTR (Click-Through Rate): The percentage of people who clicked on the ad after seeing it. It measures audience engagement.

CPC (Cost Per Click): The average cost paid for each individual click on the advertisement.

CPM (Cost Per Mille): The cost paid for every 1,000 impressions (views) of the advertisement.

Ad Recall Lift: The estimated number of people likely to remember the ad if asked within 2 hours.

## 🔍 Key Insights from Dashboard
Based on the data visualization provided in the dashboard:

Click Performance (CTR):

Type A is the most engaging ad type with the highest CTR of 4.97%.

Type D has the lowest CTR (2.76%), suggesting that the creative content or placement did not resonate well with the target audience.

Cost Efficiency (CPC & CPM):

Type A has the highest CPM ($47.56), meaning it is the most expensive ad type to display.

Type B & Type A offer the best click efficiency with the lowest CPC at $1.00.

Brand Awareness Impact (Ad Recall Lift):

Type E is exceptionally strong in building brand memory, achieving an Ad Recall Lift of 14.94%, significantly outperforming other types.

Trends (January - May):

Both Total Click Trend and Total Ad Recall Trend show consistent daily fluctuations around the benchmark, with notable performance spikes in February and April.

## 🛠️ Tools & Technology
Data Visualization: Tableau Desktop

Data Source: Marketing Campaign Dataset (CSV/Excel)

Analysis Focus: Marketing Performance, Cost Efficiency, Brand Impact Analysis.


## ⚙️ Technical Implementation1. 

1. Data Cleaning & Preparation

Before visualization, the dataset underwent a cleaning process to ensure accuracy:Handling Nulls: Missing values in the Cost and Click columns were handled to avoid skewing the average calculations.Data Formatting: Ensured that date fields were correctly parsed to allow for the January - May time-series analysis.Normalization: Calculated metrics were checked against raw data to ensure the consistency of $518,696$ total clicks and $912,981$ total ad recalls.

2. Tableau Calculated FieldsTo derive deeper insights, the following formulas were implemented within Tableau:

<img width="516" height="275" alt="Screenshot 2026-02-15 at 19 41 44" src="https://github.com/user-attachments/assets/9449442a-d472-4ae4-be45-75947d8223d4" />

3. Dashboard Design Logic
   
Color Palette: Used a professional slate-teal and blue theme to distinguish between engagement metrics (CTR/CPC) and brand awareness metrics (Recall/CPM).

Reference Lines: Added constant lines in the trend charts to represent the Average Benchmark, allowing for immediate identification of overperforming or underperforming days.

## 📈 Strategic Recommendations
Budget Optimization: Increase allocation for Type E if the primary goal is Brand Awareness, as it delivers the highest memory retention rate.

Creative Evaluation: Conduct A/B testing on Type D to improve its low CTR performance.

Cost Balancing: While Type A drives great engagement, its high CPM should be monitored to ensure the overall ROI (Return on Investment) remains sustainable.

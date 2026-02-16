# Marketing Analytics Dashboard: Evaluating Ad Performance

<img width="921" height="504" alt="Screenshot 2026-02-15 at 19 54 39" src="https://github.com/user-attachments/assets/720c51d0-c38f-4304-a6c0-edaba49fc519" />


<img width="1535" height="1151" alt="Dashboard 1" src="https://github.com/user-attachments/assets/4bffe4e6-cc74-4a1b-9e8e-298172baddf6" />

View Dashboard on Tableau Public: [https://public.tableau.com/views/MarketingAnalyticsDashboard_17711404071840/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]

## 📖 Project Background
Business Problem (2016): The company experienced a decline in brand awareness and traffic generation, resulting in stagnant sales conversions.

The Campaign (Jan - Apr 2017): Various ad types were launched to boost awareness and traffic. The company established a strict cost constraint: the Cost Per Mille (CPM) must not exceed $40.

The Objective: Develop a Marketing Analytics dashboard to identify top-performing ads in the Awareness and Consideration stages.

Goal: Provide data-driven recommendations on which ads to maintain or discontinue for May 2017 and beyond, while strictly adhering to cost limitations.


## 📊 Key Metrics & Glossary
To better understand the analysis, here are the definitions of the metrics used:

1. CTR (Click-Through Rate): The percentage of people who clicked on the ad after seeing it. It measures audience engagement.

2. CPC (Cost Per Click): The average cost paid for each individual click on the advertisement.

3. CPM (Cost Per Mille): The cost paid for every 1,000 impressions (views) of the advertisement.

4. Ad Recall Lift: The estimated number of people likely to remember the ad if asked within 2 hours.

## 🔍 Key Insights & Analysis
Based on the marketing dashboard analysis, here are the key findings regarding campaign performance across different ad types:

### 1. High-Level Performance Summary
   * Total Reach: The campaign generated a total of 518,696 clicks and achieved 912,981 total ad recalls over a 4-month period.

   * Total Investment: The total marketing cost across the four ad types was $551,788.00.

### 2. Engagement & Cost Efficiency (Awareness Stage)
   * Top Performer (CTR): Type A achieved the highest average Click-Through Rate (CTR) at 4.97%, indicating high creative resonance with the audience.

   * Most Cost-Effective: Type A and B share the lowest Cost Per Click (CPC) at $1.00, making them efficient drivers of traffic.

   * Awareness Strategy: While both Type A and B show strong performance at the awareness stage, only Type B maintains a sustainable cost-to-performance ratio in terms of CPM (Cost Per Mille).

### 3. Brand Impact & Retention (Consideration Stage)
   * Top Performer (Ad Recall): Type E leads significantly in brand memory with an average Ad Recall Lift of 14.94%.

   * Target Alignment: Ads Type D, E, and B were identified as meeting the target marketing cost thresholds.

   * Underperformer: Although Type D has the lowest CPM ($38.59), it also yields the lowest Ad Recall Lift (5.26%), suggesting that low cost does not translate to high brand impact in this case.

## 🚀 Strategic Recommendations (Action Plan)
Based on the data, the following specific actions are recommended to optimize future campaign ROI:

### ✅ Maintain & Scale
Retain Ad Type E: This type should be prioritized for the Consideration Stage because it aligns with cost targets and demonstrates superior performance in brand recall.

Retain Ad Type B: Continue utilizing Type B to maintain consistent performance at the Awareness Stage while keeping costs optimized.

### ❌ Discontinue or Re-evaluate
Terminate Ad Type A & C: These ads should be discontinued due to cost misalignment (high CPM for Type A and high CPC for Type C relative to performance).

Terminate Ad Type D: Despite its low cost, this type should be stopped as it delivers the lowest performance in Ad Recall Lift, offering poor value for brand building.


## ⚙️ Technical Implementation1. 

1. Data Cleaning & Preparation

Before visualization, the dataset underwent a cleaning process to ensure accuracy:Handling Nulls: Missing values in the Cost and Click columns were handled to avoid skewing the average calculations.Data Formatting: Ensured that date fields were correctly parsed to allow for the January - May time-series analysis.Normalization: Calculated metrics were checked against raw data to ensure the consistency of $518,696$ total clicks and $912,981$ total ad recalls.

2. Tableau Calculated FieldsTo derive deeper insights, the following formulas were implemented within Tableau:

<img width="516" height="275" alt="Screenshot 2026-02-15 at 19 41 44" src="https://github.com/user-attachments/assets/9449442a-d472-4ae4-be45-75947d8223d4" />

3. Dashboard Design Logic
   
Color Palette: Used a professional slate-teal and blue theme to distinguish between engagement metrics (CTR/CPC) and brand awareness metrics (Recall/CPM).

Reference Lines: Added constant lines in the trend charts to represent the Average Benchmark, allowing for immediate identification of overperforming or underperforming days.



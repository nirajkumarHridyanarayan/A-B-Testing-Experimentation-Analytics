<img width="1340" height="744" alt="Screenshot 2026-01-12 105358" src="https://github.com/user-attachments/assets/f70e5f4a-a62c-4dc0-9346-a3fcc627ad39" />
📊 A/B Testing & Experimentation Analytics
📌 Project Overview

This project demonstrates a real-world A/B Testing & Experimentation Analytics workflow used by product and growth teams to evaluate whether a new digital product feature (Variant B) improves user engagement compared to the existing feature (Control A).

The project covers end-to-end experimentation, including:

Experiment design

Metric definition

Data analysis

Statistical reasoning

Interactive Power BI dashboard

Business recommendations

🎯 Business Problem

Before rolling out a new product feature, businesses must ensure it positively impacts user engagement and conversions.

Key Question:

Does the new feature (Variant B) perform better than the existing feature (Control A)?

Releasing an untested feature can lead to:

Lower engagement

Reduced conversions

Revenue loss

This project uses A/B testing and analytics to make a data-driven decision.

🧪 Experiment Design
Groups

Group A (Control): Existing product feature

Group B (Variant): New product feature

Hypothesis

Null Hypothesis (H₀): No difference between Control and Variant

Alternative Hypothesis (H₁): Variant improves user engagement

📊 Metrics Used

The following user engagement metrics were analyzed:

Metric	Description
CTR (Click-Through Rate)	Measures user interaction
Conversion Rate	Measures goal completion
Avg Session Duration	Measures user engagement time
Funnel Drop-off	Tracks user journey
🛠 Tools & Technologies Used
Purpose	Tools
Data Generation	Python
Data Analysis	Python (Pandas, NumPy)
Statistics	SciPy, Statsmodels
Visualization & Dashboard	Power BI
Documentation	GitHub
Dataset Format	CSV
📂 Dataset

The dataset contains user-level experimental data.

Columns
Column	Description
user_id	Unique user identifier
group	A = Control, B = Variant
click	1 = Clicked, 0 = Not
session_duration_sec	Time spent (seconds)
converted	1 = Converted, 0 = Not
🔄 Project Workflow (Step-by-Step)
1️⃣ Data Preparation

Generated realistic A/B testing data using Python

Ensured balanced control and variant groups

Simulated uplift for Variant B to reflect real-world behavior

2️⃣ Data Cleaning & Validation

Checked for missing values

Removed duplicates

Verified correct group assignments

3️⃣ Metric Calculation

Calculated key KPIs:

Total Users

CTR

Conversion Rate

Average Session Duration

4️⃣ Power BI Data Modeling

Created DAX measures such as:

CTR

Conversion Rate

Funnel metrics

Average session duration

📈 Power BI Dashboard Overview
Dashboard Pages
📄 1. KPI Overview

Total Users

CTR

Conversion Rate

Avg Session Duration

Group filter (Control / Variant)

Purpose: Quick executive summary

📄 2. Control vs Variant Comparison

CTR comparison by group

Conversion rate comparison

Avg session duration comparison

Purpose: Performance comparison between variants

📄 3. Conversion Funnel

Total Users

Clicked Users

Converted Users

Funnel drop-off visualization

Purpose: Identify user drop-off points

📄 4. Statistical Significance Summary

Experiment outcome explanation

Clear indication of performance improvement

Business interpretation of results

Purpose: Decision confidence for stakeholders

📊 Key Insights

Variant B shows higher CTR than Control

Variant B improves conversion rate

Average session duration is higher for Variant B

Funnel analysis shows better retention in Variant B

✅ Business Recommendations

Roll out Variant B to all users

Conduct further experiments on:

Mobile vs Desktop users

CTA placement optimization

Monitor long-term retention and churn

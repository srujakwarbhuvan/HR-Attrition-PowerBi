# HR Attrition Analysis — Power BI Dashboard

## Problem Statement
IBM HR dataset analysis to identify key drivers of employee attrition 
and provide actionable retention recommendations.

## Tools Used
- Power BI Desktop (Dashboard + DAX)
- Dataset: IBM HR Analytics (Kaggle)

## Dataset
- 1,470 employees, 35 features
- Source: https://www.kaggle.com/datasets/pavansubhasht/ibm-hr-analytics-attrition-dataset

## Dashboard Pages
1. Executive Overview — KPI cards, attrition by department and job role
2. People Analysis — attrition by age, tenure, marital status
3. Compensation Analysis — salary slab, stock options, income comparison
4. Recommendations — key findings and business actions

## Key Findings
1. Overall attrition rate is 16.1% — 237 out of 1,470 employees
2. Sales Representatives churn at ~40%, nearly 3x company average
3. Employees with no stock options churn at 3x the rate of those with Level 3 options
4. Attrition spikes at Year 1 and Year 5 of tenure
5. Low salary slab (<$3k/month) accounts for majority of attrition cases

## Business Recommendations
1. Redesign Sales Rep compensation — highest ROI retention intervention
2. Extend stock option eligibility earlier in tenure
3. Build structured 90-day onboarding to address Year 1 spike

## Dashboard Preview
![Overview](screenshots/page1_overview.png)
![People Analysis](screenshots/page2_people.png)
![Compensation](screenshots/page3_compensation.png)
![Recommendations](screenshots/page4_recommendations.png)

## How to Run
1. Download the `.pbix` file from `/powerbi`
2. Open in Power BI Desktop (free)
3. Data is embedded — no additional setup needed

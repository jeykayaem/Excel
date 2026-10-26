# Call Center Performance Analysis

## Project Overview

This project analyzes call center performance using Microsoft Excel to understand customer experience, agent effectiveness, call resolution, and operational efficiency. The analysis uses call-level data and Excel summary tables to identify trends, performance gaps, and opportunities to improve service quality.

The goal is to turn raw operational data into actionable insights that a call center or operations manager can use to make informed decisions.

## Business Objectives

- Measure average customer wait time and call duration.
- Compare agent resolution rates and customer satisfaction scores.
- Identify peak call-volume hours and examine how wait times change throughout the day.
- Compare call types by duration, resolution performance, and satisfaction.
- Explore the relationship between waiting time and customer experience.
- Recommend practical improvements to service delivery and operational performance.

## Dataset

The workbook contains **500 call records** and analysis worksheets covering five business questions.

Key fields include:

- `Call_ID` — unique call identifier
- `Date` and `Time` — call date and time
- `Agent` — agent handling the call
- `Call_Type` — reason for the customer contact
- `Wait_Time_Seconds` — time spent waiting
- `Call_Duration_Seconds` — call duration
- `Resolution` — outcome or status of the call
- `Satisfaction_Score` — customer satisfaction rating
- `Resolved_Flag` — indicator used to calculate the resolution rate

## Tools and Excel Skills

**Tool:** Microsoft Excel

Skills demonstrated in this project include:

- Data review and preparation
- PivotTables and aggregated summaries
- Average, count, and rate calculations
- Performance comparison by agent and call type
- Time-based analysis of call volume and waiting time
- KPI interpretation and business recommendations
- Communicating findings in a business-focused format

## Key Findings

The following results are based on the workbook's 500 call records:

| KPI | Result |
|---|---:|
| Total calls analyzed | 500 |
| Average wait time | 33.4 seconds |
| Average call duration | 288.0 seconds (4.8 minutes) |
| Average satisfaction score | 3.77 out of 5 |
| Calls marked resolved | 66.8% |
| Highest-volume call type | Technical Support (169 calls) |

### Agent Performance

- **Lisa Martinez** had the highest resolution rate in the dataset, at approximately **73.1%**.
- Lisa Martinez also had the highest average satisfaction score, at approximately **3.96 out of 5**.
- **Chris Anderson** had the lowest resolution rate among the listed agents, at approximately **54.2%**, making this a useful area for further coaching and investigation.

These figures are descriptive findings from this dataset; they do not, by themselves, explain why agent results differ.

### Call-Type Performance

- **Complaints** had the lowest average satisfaction score, approximately **3.11 out of 5**, and a resolution rate of approximately **37.3%**.
- **Technical Support** represented the largest call category, with 169 calls, and had an average call duration of approximately **394 seconds**.
- **New Service** calls had the longest average duration among the call types, at approximately **340 seconds**.
- **General Inquiry** had the highest average satisfaction score among call types, at approximately **4.03 out of 5**.

### Peak Hours

The highest call volume occurred at **11 AM**, with 69 calls. Average wait time at that hour was approximately **46.6 seconds**. The 10 AM and 3 PM periods also showed relatively high average wait times in the dataset.

This suggests that staffing and queue management around busy periods deserve further review.

## Recommendations

1. **Review complaint handling:** Investigate common complaint themes, escalation reasons, and resolution barriers. Provide agents with clearer procedures and appropriate authority to resolve recurring issues.
2. **Plan staffing around demand:** Compare hourly call arrivals with staffing levels and schedule additional coverage during periods with high call volume and waiting times.
3. **Share effective practices:** Review how high-performing agents handle calls and share proven approaches through coaching and peer learning.
4. **Investigate longer calls:** Examine Technical Support and New Service calls to identify opportunities for better knowledge resources, call routing, or first-contact resolution.
5. **Monitor a balanced KPI set:** Track resolution rate, customer satisfaction, wait time, escalation rate, and call duration together. A shorter call is not necessarily a better call if the customer's issue remains unresolved.
6. **Validate findings over time:** Compare results across weeks or months before making staffing or performance decisions, and account for call complexity and volume differences between agents.

## Suggested Dashboard KPIs

A future Excel or Power BI dashboard could include:

- Total Calls
- Average Wait Time
- Average Call Duration
- Resolution Rate
- Average Satisfaction Score
- Call Volume by Hour
- Resolution Rate by Agent
- Satisfaction by Call Type
- Call Outcome Distribution

## Project Files

- `Call Center Performance Analysis.xls` — source Excel workbook containing the call records and analysis worksheets.
- `README.md` — project overview, findings, and business recommendations.

## Conclusion

This project demonstrates how Excel can be used to analyze operational performance, compare service outcomes, identify pressure points, and communicate recommendations. The analysis highlights complaint resolution, peak-hour waiting times, and agent-level variation as areas for further investigation.

**Note:** The results describe the supplied dataset and should not be treated as proof of causation. Definitions, data quality, and trends over a longer period should be validated before operational changes are made.

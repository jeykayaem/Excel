# Call Center Performance Analysis

## Project overview

This workbook analyzes 500 call records to explore service levels, customer satisfaction, call resolution, agent performance, and hourly demand. The analysis is organized as question-focused worksheets, with PivotTables, charts, and written observations to help interpret the results.

## Workbook contents

| Worksheet | Question or analysis |
| --- | --- |
| `Call Center Performance Analysis` | Source call records, including call date and time, agent, call type, wait and duration measures, resolution outcome, and satisfaction score. |
| `q1` | Reports the average wait time and average call duration across calls. |
| `q2` | Compares agent resolution rates and average customer satisfaction. |
| `q3` | Summarizes call volume and average wait time by hour to show busy periods. |
| `q4` | Compares call types by average satisfaction score and average call duration. |
| `q5` | Brings together operational summaries to support recommendations and examines the relationship between wait time and customer satisfaction. |

## Snapshot of the workbook findings

- The 500 calls have an average wait time of about 33.4 seconds and an average call duration of about 288 seconds (4.8 minutes).
- Average satisfaction across the dataset is about 3.77 out of 5, and about 66.8% of calls are marked resolved.
- Lisa Martinez has the highest agent resolution rate in the summary, at about 73%, and the highest average satisfaction score, at about 3.96.
- Complaint calls have the lowest average satisfaction score, at about 3.11. Technical Support calls have the longest average duration among the call types shown, at about 394 seconds.
- 11 AM is the busiest hour in the hourly summary, with 69 calls and an average wait of about 46.6 seconds.
- The workbook’s correlation summary describes little to no linear relationship between wait time and satisfaction in this dataset. This should not be read as evidence that wait time never affects customer experience.

## How to read the results

- Wait time and call duration are measured in seconds.
- Resolution rate is based on the workbook’s resolution indicator; satisfaction scores use the scale represented in the source data.
- Agent and call-type averages are descriptive. Differences may reflect call volume, issue complexity, or other factors not captured in the workbook.
- These results describe the supplied records and do not establish causes or predict future performance.

## Using and updating the workbook

Open `Call Center Performance Analysis.xls` in Excel. Review the source call records, then use `q1` through `q5` to follow the analysis. If source records change, ensure the PivotTable source ranges include the updated rows and select **Data > Refresh All**. Recheck summaries and charts after refreshing. The workbook is saved in the legacy `.xls` format and opens in Excel Compatibility Mode.

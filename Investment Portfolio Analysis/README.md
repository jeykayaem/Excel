# Investment Portfolio Analysis

## Project overview

This Excel workbook reviews a stock portfolio’s recorded buy and sell transactions. Its worksheets use PivotTables, charts, and supporting calculations to compare holdings, investment value, activity over time, sector exposure, and dividend yield.

## Workbook contents

| Worksheet | What it covers |
| --- | --- |
| `Investment Portfolio Analysis` | Portfolio transaction data used by the summaries. |
| `q1,2` | Sector-level portfolio analysis, including buy and sell value comparisons and charts. |
| `q3` | Compares companies by buy and sell quantity and value, including net shares and net investment value. It highlights the largest net holding. |
| `q4` | Summarizes monthly buy and sell quantities and investment values, with charts to compare activity over the year. |
| `q5` | Calculates a weighted average dividend yield using net investment value and the dividend yield recorded for each holding. |

## How to read the results

- Buy and sell totals represent transaction activity. Net shares and net investment value combine the two sides of that activity.
- A positive net value indicates a remaining position under the workbook’s calculation; a negative value indicates net selling.
- The weighted dividend-yield calculation weights each holding’s yield by its net investment value. Holdings with zero or negative net values can affect how that result should be interpreted.
- Values and yields reflect the workbook’s recorded data and assumptions. They are not live market prices or investment advice.

## Snapshot of the workbook

The workbook’s `q3` summary identifies UnitedHealth Group as the largest net holding, at approximately 435 net shares and 245.8K in net investment value. The `q5` worksheet reports an approximate portfolio weighted dividend yield of 1.57%.

## Using and updating the workbook

Open `Investment Portfolio Analysis.xls` in Excel. Review the source transactions first, then use `q1,2` through `q5` to explore the summaries. If you update the source records, make sure the PivotTable source ranges include the changed data and use **Data > Refresh All**. Review the charts and weighted-yield calculation after refreshing. The workbook is in the legacy `.xls` format and opens in Excel Compatibility Mode.

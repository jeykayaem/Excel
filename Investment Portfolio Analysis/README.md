# Investment Portfolio Analysis

## Overview

This Excel workbook analyzes a stock investment portfolio. It summarizes buy and sell activity, holdings by company and sector, investment value, and dividend yield. The analysis sheets use PivotTables and charts based on the workbook's transaction data.

## Worksheets

| Worksheet | What it contains |
| --- | --- |
| `Investment Portfolio Analysis` | Source transaction and portfolio data used by the analysis. |
| `q1,2` | Sector-level portfolio analysis, including a pie chart of buy value by sector. |
| `q3` | Company-level comparison of buy and sell quantities and values, with net shares and net investment value. The sheet highlights the largest holding. |
| `q4` | Month-by-month comparison of buy and sell quantities and investment value, with charts. |
| `q5` | Company-level dividend-yield summary and a weighted average dividend-yield calculation for current holdings. |

## How to use

1. Open the workbook in Excel and review the source data on `Investment Portfolio Analysis`.
2. Use the `q1,2` through `q5` tabs to review the prepared summaries and charts.
3. To analyze updated source records, add or update the source data, then refresh the PivotTables (Excel: **Data > Refresh All**). Confirm the PivotTable source range includes any newly added rows.
4. Recheck the charts and summary calculations after refreshing. The workbook is saved in the legacy `.xls` format and opens in Excel Compatibility Mode.

## Interpretation notes

- Buy and sell figures represent transaction activity; net shares and net investment value account for both sides of those transactions.
- The `q5` weighted dividend yield is intended to weight each holding's yield by its net investment value. Review the treatment of sold or negative-net holdings before using the result for reporting.
- Values and conclusions describe the data recorded in this workbook; they are not live market quotes or investment advice.

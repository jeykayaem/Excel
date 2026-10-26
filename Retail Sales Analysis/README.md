# Retail Sales Analysis

## Project overview

This workbook explores a retail transaction dataset and answers business questions using PivotTables and summary tables on separate worksheets. The source sheet contains 1,000 transactions from 2023. The analysis focuses on customer age and gender, sales timing, product categories, quantities, prices, and spending.

## Workbook contents

| Worksheet | Question or analysis |
| --- | --- |
| `retail sales analysis` | Source data: one row per transaction, with transaction and customer IDs, date, month, season, gender, age, product category, quantity, unit price, total amount, and age group. |
| `Q1,4` | Examines how age and gender relate to purchasing behavior, including average transaction amount and average quantity by age group and gender. |
| `Q2,6` | Summarizes sales by month and season to help identify timing trends. Season groupings are listed on the sheet. |
| `q3` | Compares total revenue and transaction count across product categories. |
| `q5` | Compares average quantity per transaction across product categories. |
| `q7` | Compares average unit price and average transaction amount across product categories. |

## How to read the results

- `Total Amount` is the recorded transaction spend; the workbook does not specify a currency.
- The category and demographic summaries show averages or totals as labeled. Transaction count is not the same as quantity sold.
- Seasonal totals group months as follows: Winter (December–February), Spring (March–May), Summer (June–August), and Fall (September–November).
- The source data includes a calculated `age_group` field used by the age-based analysis.

## Snapshot of the workbook totals

- 1,000 transactions are represented, totaling 456,000 in recorded sales amount.
- Electronics has the highest category revenue at 156,905.
- Clothing has the highest number of transactions at 351.
- Winter has the largest seasonal sales total at 125,730.

These figures describe the workbook data and should be interpreted as a historical exercise, not as live sales reporting.

## Using and updating the workbook

Open `retail sales analysis.xlsx` in Excel. Start with the source sheet, then use the question-numbered sheets to review each summary. If you add or change source rows, extend the relevant table or PivotTable source range and refresh the PivotTables (Excel: **Data > Refresh All**). Check the resulting summaries after refresh, especially if new categories, months, or age groups have been added.

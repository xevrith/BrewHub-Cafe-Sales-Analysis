# BrewHub Cafe Sales Analysis

An Excel-based sales analysis project for a fictional neighbourhood cafe. This project demonstrates a beginner-level data analysis workflow: reviewing raw sales records, cleaning data, calculating revenue, summarising performance, and translating results into business recommendations.

## Project at a Glance

| Detail | Description |
| --- | --- |
| Project | BrewHub Cafe Sales - Insights |
| Tool | Microsoft Excel |
| Data period | July–September 2026 |
| Raw data | 600 sales records, plus the header row |
| Workbook | [BrewHub_Cafe_Sales.xlsx](./BrewHub_Cafe_Sales.xlsx) |
| Data type | Synthetic practice data |

## Business Questions

The analysis is designed to explore:

- Which product categories contribute most to revenue?
- Which menu items generate the most sales?
- Which time slot and day of the week perform best?
- Which payment methods are most frequently used?
- What is the mix of new and returning customers?
- What practical actions could improve cafe sales?

## Workbook Guide

The workbook contains five worksheets:

| Worksheet | Purpose |
| --- | --- |
| **Data_Dictionary** | Explains the meaning of each source-data column. |
| **Data** | Original sales records. |
| **Clean_Data** | Cleaned records with calculated Revenue and Day_Name columns. |
| **Task_summary** | Summary calculations and pivot-table results. |
| **Insights** | Written findings and a business recommendation. |

**Data preservation:** The original Data worksheet is retained in the workbook. The analysis and cleaning steps are represented separately in Clean_Data.

## Analysis Workflow

1. **Inspect the source data** and review the field definitions.
2. **Clean the records** by removing duplicate order IDs and replacing missing payment methods with Unknown.
3. **Create calculated fields**, including revenue (quantity × unit price) and day name.
4. **Summarise performance** by category, time slot, payment method, customer type, and day.
5. **Communicate findings** through summary tables, a pivot table, and written recommendations.

## Excel Skills Demonstrated

- Data cleaning and duplicate handling
- Missing-value checks with COUNTBLANK
- Conditional aggregation with SUMIFS and COUNTIFS
- Basic calculations with SUM and AVERAGE
- Date formatting with TEXT
- Ranking values with LARGE
- PivotTables and charts
- Turning analysis into business recommendations

## Findings Recorded in the Workbook

The Insights worksheet records coffee as the leading revenue category and Sunday as the strongest day. It recommends maintaining coffee stock for the weekend and testing promotions to improve tea sales.

### Data-quality note

The Task_summary and Insights worksheets contain conflicting category-revenue figures, and some reported order counts do not align clearly with the cleaned record count. The workbook has intentionally **not been modified**. Reconcile those summary figures against Clean_Data before using exact numbers in a presentation or business decision.

## Repository Contents

- **BrewHub_Cafe_Sales.xlsx** — the original Excel project workbook.
- **README.md** — project overview, workbook guide, methodology, and data-quality note.
- **.gitignore** — ignores common temporary Excel and operating-system files.

## How to Review the Project

1. Download or open [the Excel workbook](./BrewHub_Cafe_Sales.xlsx).
2. Start with Data_Dictionary to understand the fields.
3. Compare Data with Clean_Data to review the cleaning process.
4. Review Task_summary and Insights to see the analysis and documented recommendations.

---

**Portfolio project:** Beginner Excel sales analysis focused on data cleaning, summary analysis, and business communication.
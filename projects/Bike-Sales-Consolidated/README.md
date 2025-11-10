# Bike Sales Consolidated Data (Excel - External Links & Summary)

## Objective
To link multiple worksheets from different workbooks and build a consolidated Excel file that updates automatically when the source data changes.

## Key Concepts Demonstrated
- External Workbook Linking
- Data Synchronization Between Sheets
- AVERAGE Function Across Multiple Workbooks
- Workbook Links & Refresh Operations

## Process Overview
1. Imported sales data from:
   - `BikeSales_2021.xlsx`
   - `BikeSales_2022.xlsx`
2. Used external references to link data into:
   - `BikeSales_Consolidated.xlsx`
3. Created summary calculations:
   - Average Cost (2021)
   - Average Revenue (2021)
4. Updated the source file to verify that the consolidated data refreshes correctly.

## Formulas Used
=AVERAGE([BikeSales_2021.xlsx]Sheet1!Q2:Q14)
=AVERAGE([BikeSales_2021.xlsx]Sheet1!R2:R14)


## Result Highlights
| Measure | Result (Before Update) | After Update (Q6 changed to 30000) |
|--------|------------------------|------------------------------------|
| Avg Cost 2021 | 26479.31 | 28495.92 |
| Avg Revenue 2021 | 43764.31 | (unchanged) |

## Files
- `BikeSales_Consolidated.xlsx`
- `BikeSales_2021.xlsx`
- `BikeSales_2022.xlsx`

(This project may contain only the consolidated workbook if the original datasets are proprietary.)

## Skills Demonstrated
- Excel Workbook Linking
- Data Refresh Controls
- Multi-sheet Consolidation
- Summary Analysis


# Sales Performance Analysis — Excel Portfolio Project

An Excel-based data analysis project built to demonstrate core data analyst skills: data
modeling, formula-driven analysis, and dashboard/reporting design.

## What's inside

**`Sales_Performance_Analysis.xlsx`** — a 3-sheet workbook:

| Sheet | Contents |
|---|---|
| **Raw Data** | 400 rows of synthetic transaction-level sales data (date, region, category, product, units, price, salesperson), formatted as an Excel Table |
| **Analysis** | Formula-driven summary tables: sales by region, sales by category, a product lookup tool, and salesperson performance/ranking |
| **Dashboard** | KPI cards (Revenue, Units Sold, Avg Order Value, Transactions) plus a bar chart, pie chart, and line chart — all fed live by the Analysis sheet |

## Skills demonstrated

- **Formulas:** `SUMIFS`, `COUNTIFS`, `COUNTA`, `AVERAGEIFS`-style logic, `INDEX`/`MATCH`,
  `IFERROR`, `RANK`, `TEXT` for date grouping
- **Data modeling:** structured Excel Table, calculated columns (`Total Sales`, `Month`)
- **Visualization:** KPI summary cards, bar/pie/line charts driven entirely by formulas
  (no hardcoded numbers — the whole workbook recalculates if the raw data changes)
- **Formatting:** conditional formatting (color scales) to highlight top/bottom performers

## How to use it

1. Download `Sales_Performance_Analysis.xlsx`
2. Open in Excel (or Google Sheets / LibreOffice Calc)
3. Try the **Product Lookup** on the Analysis sheet — type any product name from the Raw Data
   sheet into the yellow input cell and watch the totals update
4. Edit any row in **Raw Data** and watch the Dashboard recalculate automatically

## Note on the data

The dataset is synthetic, generated to resemble realistic retail sales transactions across
4 regions, 4 product categories, and 6 salespeople over FY2025. It's meant purely to showcase
Excel analysis technique, not to represent a real company.

---
*Built as a portfolio piece for a data analyst resume.*

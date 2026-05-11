# 💰 Financial Performance Dashboard — Tableau

![Financial Performance Dashboard](./dashboard-preview.png)

An interactive Tableau dashboard analysing sales, profitability, and discount impact across 5 countries and 6 product lines using financial transaction data.

---

## Dashboard Overview

**File:** `Unified_Financial_project1_.twb`  
**Data Source:** `financial_data_clean.csv`  
**Tool:** Tableau Desktop 2026.1

---

## Sheets & Visualisations

| Sheet | Type | Purpose |
|---|---|---|
| KPI – Total Sales | KPI Card | Headline net sales figure |
| KPI – Gross Sales | KPI Card | Gross revenue before discounts |
| KPI – COGS | KPI Card | Cost of goods sold |
| KPI – Profit Margin | KPI Card | Overall profitability % |
| KPI – Total Discounts | KPI Card | Total discount value applied |
| KPI – Units Sold | KPI Card | Volume metric across all segments |
| Sales Trend | Line Chart | Month-over-month sales performance |
| Gross Sales vs Discounts | Bar/Combo | Discount impact on gross revenue |
| Profit by Product | Bar Chart | Profitability breakdown by product line |
| Heat Map | Heat Map | Sales performance by segment × country |
| **Financial Performance Dashboard** | **Dashboard** | **Combined interactive view** |

---

## Key Metrics Tracked

- Net Sales, Gross Sales, COGS, Profit Margin
- Units Sold across segments and countries
- Month-over-month sales trends
- Discount band impact on revenue
- Product-level profitability

---

## Dataset Fields

| Field | Type | Description |
|---|---|---|
| Segment | String | Customer segment (e.g. Government, Enterprise) |
| Country | String | 5 countries |
| Product | String | 6 product lines |
| Discount Band | String | None / Low / Medium / High |
| Units Sold | Number | Volume per transaction |
| Manufacturing Price | Number | Unit cost |
| Sale Price | Number | Unit selling price |
| Gross Sales | Number | Revenue before discounts |
| Discounts | Number | Discount amount |
| Sales | Number | Net revenue |
| COGS | Number | Total cost of goods sold |
| Profit | Number | Net profit |
| Date / Month / Year | Date | Time dimensions |

---

## How to Open

1. Download `Unified_Financial_project1_.twb`
2. Open in Tableau Desktop
3. When prompted, reconnect the data source to your local copy of `financial_data_clean.csv`

---

## Skills Demonstrated

- KPI card design with custom formatting
- Heat map for cross-dimensional analysis
- Trend line charts with date functions
- Discount impact visualisation
- Multi-sheet dashboard layout with filters

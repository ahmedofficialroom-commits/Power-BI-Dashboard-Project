# Competitive Marketing Analysis (Power BI)

**File:** `Competitive_Marketing_Analysis.pbix`

A one-page Power BI report titled **Executive Overview** (1279 × 720, fit-to-page) that analyses unit market share against competitors.

## Report features

- **KPI cards and multi-row cards** for headline metrics
- **Charts:** bar, donut, clustered column, line, and line + stacked column combo (for example, % Units Market Share R12M vs. % Units Market Share by month)
- **Navigation:** action buttons and about 17 bookmarks that switch between views and options
- **Filters/slicers** on Segment, Manufacturer, Product, Category, Region, Channel, Month and Status

## Data model (from report references)

Tables used: `SalesFact`, `Product`, `Date`, `Geo`, `Category`, `KPI`, `Indicators`.

Key measures: **Total Units**, **Total Category Volume**, **% Units Market Share**, **% Units Market Share R12M** (rolling 12 months).

The `Product` table has an `isVanArsdel` flag that separates the company's own products from competitors.

## How to use

1. Open in **Power BI Desktop** (free from Microsoft).
2. Use the filter panel and bookmark buttons to explore. The page works well in Reading/Presentation mode.
3. The data model is embedded in the file (about 6.6 MB). Refresh if prompted.

## Notes

- The embedded data model is compressed, so the table and measure details above come from the report layer. Open **Model view** in Power BI Desktop to confirm the full schema and relationships.
- The report is linked to a published Power BI workspace dataset, so refresh behaviour may depend on your access to it.
- It appears to be built on Microsoft's sample data (VanArsdel). Confirm reuse terms before sharing publicly.

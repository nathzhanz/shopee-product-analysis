# Shopee Brazil: Product Performance Analysis

A business analysis of a public Shopee Brazil sample (200 products, 922 SKUs): how sales are distributed, and how reviews, price and catalog quality relate to sales.

![Dashboard](images/dashboard.png)

## Business questions
1. How concentrated are sales across products and shops?
2. Which price bands sell the most units?
3. Do products with more reviews sell more?
4. How clean is the catalog data?

## Key findings
- **Sales are highly concentrated.** The top 5 products make up 78% of units sold in 30 days, and the top 3 shops 83%. 55% of products sold 2 units or fewer.
- **Reviews go with sales.** Products with 20+ reviews average 52 units (excluding the top product), versus about 1 unit for products with no reviews. This is a correlation, not proof of cause.
- **One product drives the 25–50 BRL price band.** A single product (5,001 units) accounts for most of that band, so the band should not be read as an "optimal price".
- **Data quality.** 12% of products have no reviews and show a rating of 0, so they are excluded from rating averages. 7 products have no ship-from location.

## Files
| File | Description |
|---|---|
| `Shopee_Product_Analysis.xlsx` | Analysis workbook: Summary (formulas), Products, SKUs, Shops |
| `Shopee_Product_Analysis.pbix` | Power BI dashboard |
| `images/dashboard.png` | Dashboard screenshot |
| `data/` | Original CSV files from the source dataset |

## Tools
Excel (formulas, data checks), Power BI (DAX measures, dashboard).

## Data source and limits
Octoparse sample on Kaggle (Shopee Brazil, collected 17 Oct 2026). Prices are in BRL. "Sold" means units sold in the last 30 days. The sample is small and skewed by one very large product, so the findings describe this sample, not the whole Shopee market.

## Author
[Your name] · [LinkedIn] · [Email]

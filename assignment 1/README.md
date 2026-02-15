# Chocolate Sales Dataset

## Data Source
Chocolate sales records from an international confectionery company (Jan 2022 - Aug 2024)

## Columns

| Column | Description | Type |
|--------|-------------|------|
| Sales Person | Name of sales representative | Text |
| Country | Country where sale occurred | Text |
| Product | Name of chocolate product | Text |
| Date | Transaction date (DD-MM-YYYY) | Date |
| Amount | Revenue in US dollars | Numeric |
| Boxes Shipped | Number of boxes shipped | Integer |

## Countries
Australia, UK, India, USA, Canada, New Zealand

## Products
22 different products including Eclairs, Mint Chip Choco, 85% Dark Bars, etc.

## Data Stats
- 3,284 transactions
- 6 countries
- 22 products
- Revenue range: $7 - $26,170 per transaction

## Data Issues
- 1 missing Country value (first row)
- 1 duplicate row (rows 13-14)
- Date needed formatting
- Amount had $ and commas removed
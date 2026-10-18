# Online Retail II — Data Analysis

## Project Overview

This project analyses a 50,000-row working sample of the Online Retail II dataset using Google Sheets. The objective is to clean transaction data, validate data quality, analyse product performance, and document business insights.

## Dataset Overview

- **Working sample:** 50,000 rows before cleaning
- **Original columns:** 8
- **Transaction period:** December 2009 to December 2011
- **Analysis tool:** Google Sheets

## Tools Used

- Google Sheets
- GitHub

## Data Cleaning

The cleaning workflow included:

- Identifying and removing exact duplicate rows
- Investigating missing product descriptions
- Reviewing missing Customer IDs
- Checking zero-price and negative-quantity records
- Reviewing operational and non-sales entries
- Validating totals after cleaning

## Analysis Completed

- Top products by net quantity
- Top products by revenue
- Merchandise-only revenue ranking
- Products with negative net quantities
- Investigation of unusual negative-quantity transactions
- Documentation of business questions, findings, insights, and next steps

## Key Findings

- **Highest net quantity:** PACK OF 12 RED RETROSPOT TISSUES, with 14,609 units.
- **Highest merchandise revenue:** REGENCY CAKESTAND 3 TIER, with revenue of 16,008.94.
- **Product appearing in both top 10 lists:** JUMBO BAG RED RETROSPOT, with 3,917 net units and revenue of 7,415.36.
- **Unusual transaction:** A large negative-quantity transaction for StockCode 16259 was checked against the original source and retained pending further investigation.

## Data Quality and Limitations

- Negative quantities may represent returns, cancellations, or other adjustments.
- Revenue is not profit. Product cost data is required to calculate profit.
- This project uses a 50,000-row working sample, not the complete original dataset.
- The raw dataset is not included unless redistribution permission has been confirmed.

## Repository Structure

- `analysis/` — Product analysis and overall analysis exports
- `docs/` — Documented business insights

## Current Status

Product quantity and revenue analyses have been completed and documented. Further monthly revenue analysis is planned.

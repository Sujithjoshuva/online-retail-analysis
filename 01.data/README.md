# Data Files

## Overview

This folder contains the raw working sample and cleaned dataset used in the Online Retail II data analysis project.

## Files Included

### 1. `raw_data.csv`
- Contains the original 50,000-row working sample used for this project.
- Preserves the source data before the project's cleaning steps.

### 2. `cleaned_data.csv`
- Contains the dataset after data cleaning.
- Used for product-level analysis, revenue calculations, and business insights.

## Data Quality Notes

The cleaning process included checking duplicate records, missing product descriptions, missing Customer IDs, zero-price records, and negative quantities.

Missing Customer IDs and unusual negative-quantity transactions were retained where appropriate for analysis rather than automatically removed.

## Important Notes

- This project uses a 50,000-row working sample, not the complete original dataset.
- The cleaned dataset is intended for analytical use and may differ from the raw sample because of documented cleaning steps.
- Appropriate attribution to the original dataset is provided in the main project README.

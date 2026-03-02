# International Debt SQL Analysis
## Project Overview
This project involves analyzing international debt data collected by The World Bank. The dataset contains comprehensive information about the debt (in USD) owed by various developing countries across multiple categories. Using SQL, this project extracts meaningful insights regarding the total number of indebted countries, identifying the country with the highest overall debt, and pinpointing the country with the lowest principal repayments.
## Repository Name Suggestions
If you are planning to host this on GitHub, here are a few suggested repository names:
- `international-debt-sql-analysis` (Recommended)
- `world-bank-debt-analysis`
- `sql-world-bank-debt`
- `global-debt-insights-sql`
## Dataset Information
The analysis runs on the `international_debt` table, which includes the following schema:
| Column | Definition | Data Type |
|---|---|---|
| `country_name` | Name of the country | `varchar` |
| `country_code` | Code representing the country | `varchar` |
| `indicator_name` | Description of the debt indicator | `varchar` |
| `indicator_code` | Code representing the debt indicator | `varchar` |
| `debt` | Value of the debt indicator for the given country (in current USD) | `float` |
## Key Insights Explored
The repository uses SQL (PostgreSQL) to answer the following core questions:
1. **Total Distinct Countries**: Calculates the exact number of distinct countries present in the database (`124` countries). 
2. **Highest Debt Country**: Identifies which country owes the highest total amount of debt (`China`).
3. **Lowest Principal Repayment**: Determines which country has the lowest principal repayment on external debt (`Timor-Leste`).
## Technologies Used
- **SQL** (PostgreSQL)
- **Jupyter Notebook**

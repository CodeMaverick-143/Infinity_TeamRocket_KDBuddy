# Data Dictionary

| Column Name | Description | Data Type |
|-------------|-------------|-----------|
| ticker | Unique identifier for the fund | String |
| isin | International Securities Identification Number | String |
| fund_name | Full name of the fund | String |
| inception_date | Date the fund was established | Date |
| category | Morningstar category (e.g., Global Bond, US Large-Cap) | Categorical |
| rating | Morningstar Star Rating (1-5) | Numeric |
| risk_rating | Morningstar Risk Rating (1-5) | Numeric |
| performance_rating | Morningstar Performance Rating (1-5) | Numeric |
| ongoing_cost | The annual cost of owning the fund (%) | Numeric |
| management_fees | Annual fee paid to the fund manager (%) | Numeric |
| sustainability_score | ESG sustainability score | Numeric |
| fund_size | Total assets under management (AUM) | Numeric |
| fund_trailing_return_ytd | Year-to-date return (%) | Numeric |
| fund_trailing_return_3years | 3-year annualized return (%) | Numeric |
| fund_trailing_return_5years | 5-year annualized return (%) | Numeric |
| fund_trailing_return_10years | 10-year annualized return (%) | Numeric |
| asset_stock | Percentage of assets in stocks | Numeric |
| asset_bond | Percentage of assets in bonds | Numeric |
| asset_cash | Percentage of assets in cash | Numeric |
| sector_* | Exposure to various sectors (e.g., Technology, Healthcare) | Numeric |
| market_cap_* | Exposure to various market caps (Giant, Large, Medium, Small, Micro) | Numeric |

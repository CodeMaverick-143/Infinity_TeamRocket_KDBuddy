# Final Project Report: European Investment Landscape Analysis

## 1. Executive Summary
This report analyzes the performance, cost, and sustainability profiles of European ETFs and Mutual Funds. While Mutual Funds show a marginal lead in gross 5-year annualized returns (8.32% vs 8.10%), the significantly lower ongoing costs of ETFs (0.40% vs 1.12%) make them a more efficient vehicle for long-term wealth accumulation for the average investor.

## 2. Sector Context
The European asset management industry is undergoing a shift from active to passive management. With over 50,000 funds analyzed, this study provides a clear comparison of these two primary investment vehicles.

## 3. Data Description
- **Source**: Morningstar Datasets.
- **Size**: Comprehensive coverage of European ETFs and Mutual Funds.
- **Key Metrics**: 5-year Returns, Ongoing Costs, Sustainability Scores.

## 4. Methodology
The data was processed using a Python-based ETL pipeline (ETL Script: `scripts/etl_pipeline.py`). Missing values were handled, and date formats were standardized. Exploratory Data Analysis (EDA) was performed to identify trends and outliers.

## 5. KPI and Metric Framework
| Metric | ETF (Average) | Mutual Fund (Average) |
|--------|---------------|-----------------------|
| 5-Year Return | 8.10% | 8.32% |
| Ongoing Cost | 0.40% | 1.12% |
| Sustainability Score | 23.87 | 24.08 |

## 6. Key Insights
1. **Cost Efficiency**: ETFs are approximately 64% cheaper than Mutual Funds on average.
2. **Performance Gap**: Mutual Funds deliver slightly higher returns, possibly due to active management in specific niche sectors, but the gap (0.22%) is smaller than the cost gap (0.72%).
3. **ESG Parity**: Both ETFs and Mutual Funds show similar commitment to sustainability, with scores hovering around 24.
4. **Risk-Adjusted Value**: After accounting for the "cost drag," ETFs offer superior value for the majority of retail investors.

## 7. Actionable Recommendations
1. **For Core Portfolios**: Favor ETFs for broad market exposure to minimize fee leakage.
2. **For Niche Alpha**: Consider high-rated Mutual Funds in categories where active management has proven to add value beyond the fee difference.
3. **ESG Integration**: Use sustainability scores as a tie-breaker, as both fund types perform similarly in this regard.

## 8. Conclusion
The "Passive Revolution" in Europe is justified by the data. ETFs provide a compelling combination of market-matching returns and ultra-low costs.

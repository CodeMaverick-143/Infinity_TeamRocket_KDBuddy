# European Investment Analysis: ETFs vs Mutual Funds

## Team: TeamRocket
**Members**:
- Arpit Sarang
- Deeptanu Bhnuia
- Sahil Khan
- Chiranjeev Agarwal
- Sunny Singh

---

## Project Overview
This project provides a comprehensive comparative analysis of European Exchange-Traded Funds (ETFs) and Mutual Funds. Using datasets from Morningstar, we explore performance metrics, risk profiles, fee structures, and sustainability scores to provide data-backed investment recommendations.

## Sector
Finance / Asset Management

## Problem Statement
Investors often struggle to choose between ETFs and Mutual Funds. While ETFs are generally perceived as lower-cost and more transparent, Mutual Funds often claim to offer superior active management. This project aims to:
1. Compare the risk-adjusted returns of both fund types.
2. Analyze the impact of ongoing costs and management fees on long-term returns.
3. Evaluate the sustainability (ESG) profiles of European funds.
4. Identify which fund type performs better across different market sectors and capitalizations.

---

## Project Report & Key Findings

### Executive Summary
Our analysis of over 50,000 European ETFs and Mutual Funds reveals a distinct narrative. While Mutual Funds show a marginal lead in gross 5-year annualized returns (8.32% vs 8.10%), the significantly lower ongoing costs of ETFs (0.40% vs 1.12%) make them a highly efficient vehicle for long-term wealth accumulation for the average retail investor.

### Key Insights
1. **Cost Efficiency**: ETFs are approximately 64% cheaper than Mutual Funds on average. This fee reduction plays a massive role in compounding returns over decades.
2. **Performance Gap**: Mutual Funds deliver slightly higher returns on average (0.22% gap). This is often due to active management in niche or inefficient sectors, but for broad market exposure, the outperformance is smaller than the cost difference (0.72%).
3. **ESG Parity**: Both investment vehicles show a similar commitment to sustainability, with scores hovering around 24.
4. **Risk-Adjusted Value**: After accounting for the "cost drag," ETFs offer superior risk-adjusted value for the vast majority of investors.

### Actionable Recommendations
1. **For Core Portfolios**: Favor ETFs for broad market exposure to minimize fee leakage.
2. **For Niche Alpha**: Consider high-rated Mutual Funds in specific sectors where active management has historically proven to add value beyond the fee difference.
3. **ESG Integration**: Given both fund types perform similarly regarding ESG, use sustainability scores merely as a tie-breaker rather than a primary deciding factor between ETFs and Mutual Funds.

---

## Dataset
- **Sources**: Morningstar Datasets (European ETFs and Mutual Funds).
- **Scale**: Comprehensive coverage involving >50,000 rows and 100+ analytical columns containing ratings, performance, holdings, and ESG metrics.

---

## Interactive Notebook
- [Google Colab Notebook (EDA & Data Processing)](https://colab.research.google.com/drive/1ngnUGyQE98LnpO2rtiEPy0W2jySMyYk4?usp=sharing)

---

## Folder Structure
```text
.
├── data/               # Project data files
│   ├── raw/            # Original, unmodified datasets
│   └── processed/      # Cleaned and merged data
├── docs/               # Documentation (Data dictionary, capstone guidelines)
├── notebooks/          # Jupyter notebooks for ETL, EDA, and Analysis
├── reports/            # Detailed final project report and presentations
├── scripts/            # Python scripts for automated pipelines
├── tableau/            # Assets or workbooks related to Tableau
└── README.md           # This project overview file
```
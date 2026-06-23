# Institutional Tokenized Treasury & Settlement Dashboard

## Project Overview

This project compares tokenized Treasury products against traditional Treasury ETFs and short-term cash-rate benchmarks.

The goal is to evaluate tokenized Treasuries through an institutional finance lens, including yield, liquidity, TVL growth, collateral quality, redemption mechanics, and potential settlement use cases.

This project was built to show how tokenized real-world assets can be analyzed alongside traditional fixed-income instruments.

## Why This Matters

Tokenized Treasuries are one of the most practical real-world asset use cases in digital assets. They sit at the intersection of:

- Fixed income
- Cash management
- Collateral mobility
- Stablecoin reserves
- Blockchain-based settlement
- Institutional digital asset infrastructure

Institutional clients do not evaluate these products only by yield. They also care about liquidity, risk, operational structure, redemption mechanics, transparency, and settlement efficiency.

## Core Questions

This dashboard answers:

1. How do tokenized Treasury products compare with traditional Treasury ETFs?
2. How do yields compare against Treasury benchmarks?
3. Which issuers have the largest tokenized Treasury market share?
4. How does TVL growth reflect institutional adoption?
5. What liquidity and risk tradeoffs exist between tokenized and traditional products?
6. How could tokenized Treasuries support institutional settlement and collateral use cases?

## Data Sources

The project uses:

- Yahoo Finance through `yfinance`
- FRED through `pandas_datareader`
- Optional RWA.xyz or issuer-exported tokenized Treasury data
- Optional DeFiLlama data
- Manually curated tokenized Treasury CSV data when live product-level data is unavailable

## Main Features

- Treasury ETF price, return, volatility, drawdown, and liquidity analysis
- Treasury rate benchmark comparison
- Tokenized Treasury TVL growth analysis
- Yield spread analysis versus 3-month Treasury bills
- Issuer market share analysis
- Institutional readiness scorecard
- HTML dashboard generation
- Clean CSV exports for further analysis

## Key Metrics

The project calculates:

- Annualized ETF return
- Annualized ETF volatility
- Maximum drawdown
- 30-day average dollar volume
- Tokenized Treasury TVL
- Tokenized Treasury market share
- Product yield
- Yield spread versus 3-month Treasury bills
- Institutional readiness score

## Visualizations

The dashboard includes:

- Tokenized Treasury TVL growth by product
- Latest TVL by issuer
- Annualized yield comparison
- Spread versus 3-month Treasury bills
- Treasury ETF drawdown comparison
- Liquidity versus yield scatter plot
- Institutional readiness scorecard

## Institutional Use Case

This project is relevant to banks, asset managers, stablecoin issuers, and digital asset infrastructure firms evaluating tokenized real-world assets.

A client success or product team could use a similar framework to explain:

- Why tokenized Treasuries matter
- How they compare with traditional Treasury access products
- What risks institutions should evaluate
- How tokenized assets may support collateral mobility and settlement efficiency
- Where blockchain infrastructure adds value beyond basic yield

## Technologies Used

- Python
- pandas
- numpy
- yfinance
- pandas_datareader
- requests
- Plotly
- matplotlib
- scipy
- Google Colab

## Project Structure

```text
tokenized-treasury-dashboard/
│
├── notebook/
│   └── institutional_tokenized_treasury_dashboard.ipynb
│
├── data/
│   ├── raw/
│   └── processed/
│
├── outputs/
│   └── institutional_tokenized_treasury_dashboard.html
│
├── README.md
├── requirements.txt
└── .gitignore

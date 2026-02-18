# 📈💻 Tech Stock Price Analysis & Portfolio Diversification

## 📌 Project Overview
This project explores historical **daily stock price data** for ten major technology companies to analyze their performance, volatility, and return characteristics.

The analysis is framed from the perspective of an **investment analyst** at a small firm that currently specializes in **commodities** (coffee, cocoa, and sugar) and is considering expanding into **technology stocks**.  
The goal is to evaluate how tech stocks could be integrated into an existing commodity-focused portfolio while managing risk.

---

## Business Objective
Help the investment firm:
- Understand historical returns and volatility of major tech stocks
- Compare tech stocks with commodity assets
- Identify diversification benefits
- Recommend a balanced portfolio strategy

---

## Companies Analyzed
The dataset includes daily stock prices for the following companies:

- Apple (AAPL)
- Amazon (AMZN)
- Alibaba (BABA)
- Salesforce (CRM)
- Facebook / Meta (FB)
- Alphabet (GOOG)
- Intel (INTC)
- Microsoft (MSFT)
- Nvidia (NVDA)
- Tesla (TSLA)

Each company’s data is stored as a separate CSV file in the `data/` directory.

---

## Dataset Details

### Structure
- **Frequency:** Daily
- **Rows per file:** ~3,000 observations
- **Source:** Yahoo Finance

### Data Dictionary

| Column | Description |
|------|-------------|
| Date | Trading date |
| Open | Opening price |
| High | Highest price during the trading day |
| Low | Lowest price during the trading day |
| Close | Closing price |
| Adj Close | Adjusted closing price (splits & dividends) |
| Volume | Number of shares traded |

---

##  Key Analysis Tasks

### 1) Exploration
- Identified which of the ten companies has the **highest most recent closing price**

---

### 2) Visualization
- Created visualizations showing:
  - Monthly closing prices
  - Comparative price trends across all ten stocks

---

### 3) Analytical Insights
- Calculated the **percentage increase in closing price** over time
- Identified companies with the **strongest long-term growth**

---

## 📈 Investment Scenario Analysis

### 1️⃣ Returns & Volatility
- Computed daily and cumulative returns for tech stocks
- Measured volatility to assess risk
- Compared tech stock behavior to commodity price movements

---

### 2️⃣ Tech vs Commodities
- Contrasted returns and risk profiles of:
  - Tech stocks
  - Coffee, cocoa, and sugar commodities
- Analyzed diversification potential

---

### 3️⃣ Portfolio Recommendation
- Evaluated how tech stocks could be:
  - Combined with commodities
  - Weighted to reduce overall portfolio risk
- Provided recommendations for:
  - Growth exposure
  - Risk diversification

---

## Key Findings
- Tech stocks generally offer **higher returns** with higher volatility
- Commodities provide **stability and diversification**
- A mixed portfolio reduces risk while maintaining growth potential
- Certain tech stocks act as better long-term growth anchors than others

---

## Tools & Technologies
- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn**
- **Financial time-series analysis**

---

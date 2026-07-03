# Bitcoin Market Sentiment vs Trader Performance Analysis

## Overview

This project analyzes the relationship between Bitcoin market sentiment (Fear & Greed Index) and historical trader performance using Hyperliquid trading data.

The objective is to discover patterns that explain how market sentiment affects trader profitability, leverage, trading activity, and risk.

---

## Dataset

### 1. Bitcoin Fear & Greed Index

- Date
- Classification (Fear / Greed)

### 2. Hyperliquid Historical Trader Data

- Account
- Symbol
- Execution Price
- Size
- Side
- Time
- ClosedPnL
- Leverage
- Event
- Start Position

---

## Project Workflow

1. Data Loading
2. Data Cleaning
3. Feature Engineering
4. Merge Datasets
5. Exploratory Data Analysis
6. Visualization
7. Business Insights

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Performed

- Average PnL during Fear vs Greed
- Trading Volume Analysis
- Win Rate Analysis
- Average Leverage
- Symbol-wise Profitability
- Top Performing Traders
- Correlation Analysis

---

## Key Findings

- Trading behavior varies significantly across market sentiment.
- Higher leverage does not necessarily improve profitability.
- Greed periods generally show higher trading activity.
- Fear periods exhibit greater market volatility.

---

## Folder Structure

```
PrimeTrade_AI_Assignment/

│── data/
│── notebooks/
│── images/
│── report.pdf
│── README.md
│── requirements.txt
```

---

## How to Run

```bash
pip install -r requirements.txt
```

Run

```
analysis.ipynb
```

or

```
python analysis.py
```

---

## Author

Monis

B.Tech Computer Science & Business Systems

Bharati Vidyapeeth College of Engineering, Pune
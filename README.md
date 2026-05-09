# Trader Performance Analysis Based on Bitcoin Market Sentiment

## Project Overview

This project analyzes the relationship between Bitcoin market sentiment and trader performance using historical trading data and the Bitcoin Fear & Greed Index.

The goal of this analysis is to uncover how market emotions such as Fear and Greed influence:

- Trader profitability
- Trading volume
- Risk-taking behavior
- Win rates
- Buy/Sell activity

The project combines trader execution data with sentiment classification to generate actionable insights for smarter trading strategies.

---

## Datasets Used

### 1. Bitcoin Fear & Greed Index Dataset
Columns:
- date
- value
- classification

### 2. Historical Trader Dataset
Columns include:
- Account
- Coin
- Execution Price
- Size USD
- Side
- Timestamp IST
- Closed PnL
- Direction
- Fee
- Trade ID

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab / Jupyter Notebook

---

## Project Workflow

### 1. Data Loading
- Imported CSV and Excel datasets

### 2. Data Cleaning
- Converted timestamps
- Standardized date formats
- Removed missing values

### 3. Data Merging
- Merged trader data with sentiment data using date

### 4. Exploratory Data Analysis (EDA)
Performed:
- Profitability analysis
- Trading volume analysis
- Win rate analysis
- Buy vs Sell analysis
- Correlation analysis

### 5. Visualization
Generated charts and heatmaps to identify trends and patterns.

---

## Key Insights

- Trading activity increased significantly during Greed periods.
- Traders used larger position sizes during bullish sentiment.
- Fear periods showed relatively cautious market participation.
- Higher activity during Greed did not always improve profitability.
- Market sentiment strongly influenced trader behavior and risk exposure.

---

## Sample Visualizations

The notebook includes:
- Average Profit by Sentiment
- Trading Volume by Sentiment
- Win Rate Analysis
- Buy vs Sell Distribution
- Correlation Heatmap

---

## Conclusion

The analysis demonstrates that market sentiment plays an important role in trader behavior and trading outcomes. Greed periods were associated with increased activity and aggressive trading, while Fear periods reflected cautious participation patterns.

These findings can help traders and analysts better understand emotional market behavior and improve decision-making strategies.

---

## How to Run

1. Clone the repository
2. Install required libraries
3. Open the notebook in Jupyter or Google Colab
4. Run all cells sequentially

---

## Requirements

Install dependencies using:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

---

## Author

Nandini Reddy

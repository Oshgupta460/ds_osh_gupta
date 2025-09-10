# ds_osh_gupta
# Trader Behavior vs Market Sentiment Analysis

This project analyzes the relationship between trader behaviour (profitability, leverage, trade volume) and market sentiment (Fear vs Greed).  
Two datasets were used:
- `fear_greed_index.csv` → Market sentiment data  
- `liquidations.csv` → Historical trader data from Hyperliquid  

---

##  Project Structure
ds_osh_gupta/
├── notebook_1.ipynb
├── csv_files/
│   └── sentiment_trader_merged.csv
├── outputs/
│   └── profitability_vs_sentiment.png
├── ds_report.pdf
└── README.md

##  Key Analysis

- Aggregated daily trader metrics:  
  - Number of trades  
  - Total notional traded  
  - Average leverage  
  - Daily PnL  

- Merged these with sentiment data (Fear = 0, Greed = 1).  
- Compared profitability and leverage across Fear vs Greed days.  
- Visualized trends over time.  

---

## Insights

- Trading activity changes noticeably depending on sentiment.  
- Fear periods → lower profitability and smaller positions.  
- Greed periods → higher leverage and risk, but not always more profitable.  
- Sentiment can serve as a secondary signal for strategy refinement.  

---

## Submission Compliance

- Code in Colab notebooks.  
- Organized CSVs and outputs in separate folders.  
- Final insights summarized in **`ds_report.pdf`**.  
- Repo mirrors required structure exactly.  

---

## Candidate

**Name:** Osh Gupta  
**Role:** Data Science Candidate  


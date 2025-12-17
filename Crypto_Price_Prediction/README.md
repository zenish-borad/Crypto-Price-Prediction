# Statistical Comparison and Predictive Modeling of Cryptocurrency Price Movements

**Author:** Zenish Borad  
**University:** Northeastern University  
**Course:** INFO6105 – Data Science Engineering Methods and Tools  
**Date:** 12/05/2025  

---

## Project Overview

This project analyzes four major cryptocurrencies — **Bitcoin (BTC)**, **Ethereum (ETH)**, **XRP**, and **Solana (SOL)** — to compare their volatility, study market trends, and predict next-day closing prices using statistical methods.

The main objectives are:

- Compare volatility across the four cryptocurrencies.  
- Analyze how daily market trends affect closing prices.  
- Build predictive models for next-day closing prices using **Multiple Linear Regression**.  
- Apply **One-Way ANOVA** and **Two-Way ANOVA** to quantify market differences.  

---

## Dataset

- Source: [Cryptocurrency Price History Dataset on Kaggle](https://www.kaggle.com/datasets/sudalairajkumar/cryptocurrencypricehistory)  
- Coins analyzed: BTC, ETH, XRP, SOL  
- Data includes: Open, High, Low, Close, Volume, Marketcap, and Date  
- Preprocessing: Missing values removed, derived volatility and trend variables  

---

## Methodology

- **Multiple Linear Regression:** Predict next-day closing prices using Open, High, Low, and Volume.  
- **One-Way ANOVA:** Compare daily volatility among the four cryptocurrencies.  
- **Two-Way ANOVA:** Examine the interaction between cryptocurrency type and market trend on closing prices.  

---

## Key Findings

- BTC exhibits the highest volatility among the four coins.  
- Altcoins (ETH, SOL, XRP) show statistically similar volatility.  
- Open, High, and Low prices are strong predictors of next-day closing prices (R² ≈ 0.997).  
- Market trend (Up/Down day) has negligible effect on closing prices.  

---

## Folder Structure

```
crypto-price-prediction/
│
├── data/          # CSV files for BTC, ETH, XRP, SOL
├── report/        # Project report and presentation
└── README.md      # Project overview and instructions
```

---

## How to Run

1. Clone the repository:  
```bash
git clone https://github.com/your-username/crypto-price-prediction.git
```

2. Open the scripts in **RStudio** or **Python IDE** to run the analysis.  

3. Ensure required packages are installed:  
```r
# For R
install.packages(c("dplyr","ggplot2","tidyr","car","multcomp","agricolae","GGally"))
```

---

## Resources & References

- Rajkumar, Sudalai. *Cryptocurrency Historic Dataset*, Kaggle, accessed Nov 2025.  
- R Core Team (2025). *R: A language for statistical computing*.  
- Packages: ggplot2, dplyr, tidyr, car, multcomp, agricolae, GGally  
- Presentation Video: [YouTube Link](https://youtu.be/OX61FQP9GF8)  

---

## License

This project is for academic use and research purposes.

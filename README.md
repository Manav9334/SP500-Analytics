# 📊 S&P 500 Risk & Return Analytics

## 🔎 Overview

This project performs large-scale financial time-series analysis on 500+ S&P 500 companies using Python.  

The objective is to evaluate stock performance, volatility, inter-stock correlations, statistical differences in returns, and predictive trends using quantitative modeling techniques.

---

## 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- SciPy (Statistical Testing)  
- Scikit-learn (Regression Modeling)  

---

## 📈 Key Analysis Performed

- Computed daily returns and rolling volatility metrics  
- Built risk–return profiles for 500+ equities  
- Generated correlation heatmaps to identify stock relationships  
- Conducted statistical hypothesis testing (two-sample t-tests on stock returns)  
- Implemented regression-based forecasting to analyze trend behavior  

---

## 📊 Outputs Generated

All results are saved for reproducibility:

- Risk–return summary tables  
- Correlation matrix  
- Time-series visualizations  
- Forecast prediction results  
- Serialized regression model  

Outputs are stored inside the `outputs/` directory.

---

## 💡 Key Insights

- Higher-return equities generally exhibit higher volatility.  
- Technology stocks demonstrate strong correlation clusters.  
- Statistical testing confirms significant differences in return distributions across selected equities.  
- Linear regression captures overall trend patterns but highlights limitations in financial forecasting.

---

## ▶ How to Run

1. Install dependencies:

```bash
pip install -r requirements.txt

2. Open and run:

```bash
notebooks/SP500_Analysis.ipynb
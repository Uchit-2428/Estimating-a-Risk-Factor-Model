
# Risk Factor Modeling of Apple (AAPL) Using Fama-French 4-Factor Model

Welcome to the repository for **Risk Factor Modeling** of **Apple Inc. (AAPL)** using the **Fama-French 4-Factor Model**.  
This project builds a factor-based regression model using live market data and interprets Apple's behavior relative to systematic risk factors.

---

## Project Overview

- **Objective**:
  
  Model and explain Apple's excess stock returns based on four major risk factors:
  - **Mkt-RF**: Market Risk Premium (Market Return minus Risk-Free Rate)
  - **SMB**: Small Minus Big (Size Effect)
  - **HML**: High Minus Low (Value vs Growth Effect)
  - **MOM**: Momentum (Winners Minus Losers)

- **Model Used**:
  
  The Fama-French 4-Factor model used here is:

  **(Return of Apple - Risk-Free Rate) = Alpha + Beta_Mkt (Market - Risk-Free) + Beta_SMB (SMB) + Beta_HML (HML) + Beta_MOM (MOM) + Error**

---

## Tools and Libraries Used

- Python 3.x
- yfinance — for fetching AAPL stock data
- pandas — for data manipulation
- statsmodels — for OLS regression and statistical analysis
- matplotlib — for plotting and visualization

---

## Key Findings

- The Fama-French 4-Factor Model explains approximately **28.8%** of Apple's excess return variability.
- Apple shows:
  - **Strong positive sensitivity** to the market factor (Mkt-RF).
  - **Strong negative sensitivity** to the value factor (HML), confirming that Apple behaves like a **growth stock**.
- Size (SMB) and Momentum (MOM) factors were not statistically significant for AAPL.
- The model is **statistically significant overall** (p-value < 0.001).

---

## How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Risk_Factor_Model.git
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Open and run the `Risk_Factor_Model.ipynb` notebook step-by-step in Jupyter or Google Colab.

---






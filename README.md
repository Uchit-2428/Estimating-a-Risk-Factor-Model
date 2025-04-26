# Estimating-a-Risk-Factor-Model

:

📈 Risk Factor Modeling of Apple (AAPL) Using Fama-French 4-Factor Model
Welcome to the repository for Risk Factor Modeling of Apple Inc. (AAPL) using the Fama-French 4-Factor Model.
This project builds a factor-based regression model using live market data and interprets Apple's behavior relative to systematic risk factors.

📚 Project Overview
Objective:
Model and explain Apple's excess stock returns based on four major risk factors:

Mkt-RF: Market Risk Premium (Market Return minus Risk-Free Rate)

SMB: Small Minus Big (Size Effect)

HML: High Minus Low (Value vs Growth Effect)

MOM: Momentum (Winners Minus Losers)

Model Used:
The Fama-French 4-Factor model extends the traditional CAPM by adding size, value, and momentum effects.
The model mathematically is:

(
𝑅
𝑖
−
𝑅
𝑓
)
=
𝛼
+
𝛽
𝑚
(
𝑅
𝑚
−
𝑅
𝑓
)
+
𝛽
𝑠
SMB
+
𝛽
𝑣
HML
+
𝛽
𝑚
𝑜
𝑚
MOM
+
𝜖
(R 
i
​
 −R 
f
​
 )=α+β 
m
​
 (R 
m
​
 −R 
f
​
 )+β 
s
​
 SMB+β 
v
​
 HML+β 
mom
​
 MOM+ϵ
Where:

𝑅
𝑖
R 
i
​
 : Return of Apple (AAPL)

𝑅
𝑓
R 
f
​
 : Risk-Free Rate

𝛽
β's: Sensitivities to each factor

𝜖
ϵ: Idiosyncratic (company-specific) error

🛠️ Tools and Libraries Used
Python 3.x

yfinance — for fetching AAPL stock data

pandas — for data manipulation

statsmodels — for OLS regression and statistical analysis

matplotlib — for plotting and visualization

scikit-learn — for comparison if needed

  Key Findings
The Fama-French 4-Factor Model explains approximately 28.8% of Apple's excess return variability.

Apple shows:

Strong positive sensitivity to the market factor (Mkt-RF).

Strong negative sensitivity to the value factor (HML), confirming that Apple behaves like a growth stock.

Size (SMB) and Momentum (MOM) factors were not statistically significant for AAPL.

The model is statistically significant overall (p-value < 0.001).


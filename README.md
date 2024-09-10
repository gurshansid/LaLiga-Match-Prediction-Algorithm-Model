# LaLiga-Match-Prediction-Algorithm-Model

<h1>LaLiga-Match-Prediction-Algorithm-Model</h1>

<h2>Description</h2>
This is a machine learning model for NVIDIA's stock price I built using Jupyter Notebook written in Python. The model uses predictors like opening price, closing price, volume, daily high, and daily low to predict whether NVIDIA's price will increase or decrease tomorrow. I improved the model from having 52% accuracy to 62% accuracy by adding more predictors-specifially rolling averages that average out the closing price for the past 3 days, 5 days, 3 months, 1 year, and 4 years to help the model make better predictions by determining the type of market behavior that has been occurring lately. The model uses dowloaded and cleaned NVIDIA price data from 2000 to the current day. This model is also backtested thoroughly. 
<br />


<h2>Languages and Libraries Used</h2>

- <b>Python</b> 
- <b>Pandas</b>
- <b>yfinance</b>
- <b>scikit-learn</b>


<h2>Environments Used </h2>

- <b>Jupyter Notebook</b>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

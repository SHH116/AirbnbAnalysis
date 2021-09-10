# Airbnb Data Analysis


![image](https://user-images.githubusercontent.com/56700326/132815010-65a0318e-660b-4c76-9ec6-b3a1a734945b.png)


# Applying Business Analytics to identify KPIs contributing to Airbnb price premium 

As the Airbnb market gets more competitive and more hosts join the network, it becomes important to identify the key factors which help the hosts ask a higher price premium. I extract some of those factors based on the Seattle market data. Later, I run some comparative studies of the successful hosts vs the unsuccessful ones.  
--------
## Libraries

* !pip install pandas
* !pip install numpy
* !pip install seaborn 
* !pip install scikit-learn


## Linear Regression assumptions
<dl>
  <dt>Put-Call parity holds:</dt>
  <dd>https://corporatefinanceinstitute.com/resources/knowledge/finance/put-call-parity/</dd>
  <dt>No Arbitrage:</dt>
  <dd>https://quant.stackexchange.com/questions/41414/does-black-scholes-need-to-assume-no-arbitrage</dd>
  <dt>Underlying follows a Random Walk and its returns are lognormally distributed:</dt>
  <dd>https://en.wikipedia.org/wiki/Random_walk</dd>
  <dt>The Random walk has constant drift and volatility:</dt>
  <dd>https://www.investopedia.com/terms/b/blackscholes.asp</dd>
  <dt>The Options are Vannilla European style:</dt>
  <dd>https://en.wikipedia.org/wiki/Option_style:</dd>
  <dt>No Dividends are paid
</dl>
  

## Project steps
  
1-Data Imputations 
  
2-Data Cleaning
  
3-Data exploration
  
4-Collinearity study
  
5-Redundancy Identification
  
6-Dealing with categorical data
  
7-Implementing and evaluating a Linear Regression model to predict price
  
8-Correcting the lienar regression model
  


  


 ## Data
  
4-year Airbnb Seattle historical data is sourced from kaggle:
  
  
  <dt>Data Sources:</dt>
  <dd>[1] https://ca.finance.yahoo.com/quote/SPY/history?p=SPY</dd>
  <dd>[2] https://ca.finance.yahoo.com/quote/%5EVIX/history?p=%5EVIX</dd>
  <dd>[3] https://stooq.com/db/h/</dd>
  <dd>[4] https://www.barchart.com/ondemand/api/getHistory?gclid=Cj0KCQjw7MGJBhD-ARIsAMZ0eeuwPQiDLvub5yVYGvvfyW4AyeWpHGH9lBK1XylfM3DSyAygHiji6ccaAtpOEALw_wcB</dd>
  <dd>[5] https://www.quandl.com/search?query=stocks</dd>
  
  
## Acknowledgments
  
Thanking Dmitry Vyushin of RBC for his supervision and guidance
  
Sasha Hajy Hassani as the developer


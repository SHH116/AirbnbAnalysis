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
  1-The regression model is linear in the coefficients and the error term
2: The error term (unpredictable random error) has a population mean of zero
3: All independent variables are uncorrelated with the error term
4: Observations of the error term are uncorrelated with each other (residual plots must be random and non-trending, no autocorrelation of residuals/errors)
5-Variance of erros is constant and sum of errors must be zero.
6: No independent variable is a perfect linear function of other explanatory variables (co-linearity of indep variables should not exist).
7:Observations are independent of each other
8: Y (dependent variable) must have constant variance

  
  
  
  
  <dt>The regression model is linear in the coefficients and the error term:</dt>
  <dd>https://corporatefinanceinstitute.com/resources/knowledge/finance/put-call-parity/</dd>
  <dt>The error term (unpredictable random error) has a population mean of zero:</dt>
  <dd>https://quant.stackexchange.com/questions/41414/does-black-scholes-need-to-assume-no-arbitrage</dd>
  <dt>All independent variables are uncorrelated with the error term:</dt>
  <dd>https://en.wikipedia.org/wiki/Random_walk</dd>
  <dt>Observations of the error term are uncorrelated with each other (residual plots must be random and non-trending, no autocorrelation of residuals/errors):</dt>
  <dd>https://www.investopedia.com/terms/b/blackscholes.asp</dd>
  <dt>Variance of erros is constant and sum of errors must be zero:</dt>
  <dd>https://en.wikipedia.org/wiki/Option_style:</dd>
  <dt>No independent variable is a perfect linear function of other explanatory variables (co-linearity of indep variables should not exist):
  <dt>Observations are independent of each other:</dt>
  <dt>Y (dependent variable) must have constant variance:</dt>
  
</dl>
  

## Project steps
  
1-Data Imputations 
  
2-Data Cleaning
  
3-Data exploration
  
4-Collinearity study
  
5-Redundancy Identification
  
6-Dealing with categorical data
  
7-Implementing and evaluating a Linear Regression model to predict price
  
8-Correcting the linear regression model
  


  


 ## Data
  
4-year Airbnb Seattle historical data is sourced from kaggle:
  
  
  <dt>Data Sources:</dt>
  <dd>[1] https://www.kaggle.com/airbnb/seattle</dd>
  <dd>[2] https://www.kaggle.com/airbnb/boston</dd>
  
  
  



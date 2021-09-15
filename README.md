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
  
  <dt>The regression model is linear in the coefficients and the error term</dt>
  <dt>The error term (unpredictable random error) has a population mean of zero</dt>
  <dt>All independent variables are uncorrelated with the error term</dt>
  <dt>Observations of the error term are uncorrelated with each other (residual plots must be random and non-trending, no autocorrelation of residuals/errors)</dt>
  <dt>Variance of erros is constant and sum of errors must be zero</dt>
  <dt>No independent variable is a perfect linear function of other explanatory variables (co-linearity of indep variables should not exist)</dt>
  <dt>Observations are independent of each other</dt>
  <dt>y (dependent variable) must have constant variance</dt>
  
</dl>
  



## Linear Regression in practice


a) At least 30 isntances for a simple regression and 10 isntances per any additional feature is required. Given the 90+ features, at least 1000 isntances are required.

b) The Large number of features would ineivtably improve the R-squred of the model, but aalso exposes it to overfitting and noise learning.

c) It is critical to avoid horizontal imputations as they can lead to synthetically increased feature collinearity.

d) Features conveying similar information, must be removed to simplify the model.

e) Scatter plots of X and y must be checked to ensure the variance of the train and test data is constant.

f) One-hot-encoding of each cateogorical feature results in many new synthetic features and subsequently more instances of data are required for appropriate fitting. Given that the dataset contains very limited (approxiamtely 4000) rows of data, identifying and removing irrelevant categorical features is beneficial. 

g) An alternative solution to the above is to bin multiple categories of a feature column based on their similarity. For example, instead of having, "calendar_updated_yesterday", "calendar_updated_2 days ago","calendar_updated_3 days ago" ,etc, form a bin where all calendar_updated which occured from today to 1 week ago get fused into group A, those that occured from 1 month ago to 1 week ago get fused into group B and so on. This way I do not have to carry too many categories, and isntead can bin the data without sacrificing any information.








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
  
  
  



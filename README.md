# yes_bank_stockprice_analysis


Time Series forecasting & modeling plays an important role in data analysis. Time series analysis is a specialized branch of statistics used extensively in fields such as Econometrics & Operations Research. 

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

In this project we have presented exploratory data analysis, visualization, regression models with different types and interesting insights of the data based on the data. This dataset has around 185 observations in it with 5 columns. 

Fundamental Analysis involves analyzing the company’s future profitability on the basis of its current business environment and financial performance. 
Technical Analysis, on the other hand, includes reading the charts and using statistical figures to identify the trends in the stock market. Our focus will be on the technical analysis part. We’ll be using a dataset of Yes Bank Stock price for this particular project.

As a first step, we have loaded the data, we have mounted the drive. After mounting the drive, we have imported  important libraries such as numpy, pandas, seaborn, matplotlib and also all regression model libraries with their metrics, which are useful for our analysis.

We have explored our data by checking all the necessary parameters like shape, head, tail, information of the columns and their datatypes and description of data like mean, min and max. We have performed exploratory data analysis, normalization, lag creation, preparation of the data and two types of splits.

Finally, we have fitted the dataset using various supervised regression algorithms like Linear Regression, Ridge and Lasso Techniques, Random Forest, XG boost, Gradient, KNN, Support Vector machines, Arima and Sarima. All the performance metrics of these models were compared against each other and the best model was used to predict the stock prices.

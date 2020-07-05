# Stock-Market-Forecasting

Stock Market Forecasting using Time Series Analysis, as well as comparative analysis of different prediction methodologies.

**DATASET :** 

**TRAINING PLATFORM :** 

**MODELS INCLUDED -**
1. MOVING AVERAGE
 2. LINEAR REGRESSION
 3. CUSTOMIZED K-NN
 4. fbPROPHET
 5. AUTO-ARIMA
 6. LONG SHORT TERM MEMORY

### Problem Statement 
Building a supervised learning model which can study the various time-series trends with seasonality in the mix. The model is suppose to have a great prediction capabilities so that it can be used for stock market forecasting.

### Dataset
We’ll be using a dataset from [https://www.moneycontrol.com](https://www.moneycontrol.com/) (you can find historical data for various stocks here) and for this particular project, we have used the data for ‘STATE BANK OF INDIA’. We have collected data from January 2011 to December 2019 and after a successful implementation and training of our model, we will use the respective accuracies of the model to draw inferences to find the best suitable model out there which can be used for stock market prediction. The Data collected has been stored in the form of a CSV file; in Comma-Separated Values format.

### Methodology
![Methodology](https://github.com/dipanshuagarwal/Stock-Market-Forecasting/blob/master/Methodolgy.png)

### Conclusion
![Comparison](https://github.com/dipanshuagarwal/Stock-Market-Forecasting/blob/master/Compare.png)

As we can see in Table, LSTM is the most efficient model which was implemented on our particular dataset.
The LSTM model was the best model implemented out of all to work with Time-Series. But are the predictions from LSTM enough to identify whether the stock price will increase or decrease? Certainly not! 

As we know, stock price is affected by the news about the company and other factors like demonetization or merger/demerger of the companies. There are certain intangible factors as well which can often be impossible to predict beforehand.

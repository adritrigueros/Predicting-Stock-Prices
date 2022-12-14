# Predicting-Stock-Prices
# Application of Machine Learning Algorithms and Sentiment Analysis for the Prediction of Stock Prices

The prediction of stock prices has been a popular topic for research and its is considered one of the most challenging tasks due to the volatile and noisy nature of stock prices. Furthermore,considering exogenous variables such as the public sentiment regarding a particular task is challenging due to data being in an unstructured format. This work proposes the application of machine learning and deep learning algorithms for the prediction of stock prices, including in the final model the sentiment of public opinions about a company expressed through the social media platform Twitter. First the data is collected through the Twint scraping tool for
tweets and Yahoo Finance for historic stock prices. Then the twitter dataset is cleaned, and a sentiment analysis is performed using VADER. The final dataset is obtained by merging the sentiment analysis results of the twitter dataset and the historic stock prices. A rolling window technique is applied to incorporate lagged features in the model, and finally Random Forest, XGBoost, Linear Regression, LSTM and Bidirectional LSTM are tested for the prediction of stock prices and their evaluation is compared with R-Squared and RMSE metrics against a traditional model like ARIMA. The results indicate that the proposed models outperform by far traditional time series models, such as, ARIMA. Additionally, a relation between sentiment scores and closing prices of stocks was found using several machine learning
techniques. The performance of the models is tested on five different datasets, from the companies Tesla, Amazon, Google, Meta, and Apple.




# Bitcoin Price Prediction Using Machine Learning
![](https://changelly.com/blog/wp-content/uploads/2024/02/BTC-price-prediction-1.png)
This project aims to predict Bitcoin prices using various machine learning techniques. 
The primary focus is on using Long Short-Term Memory (LSTM) neural networks to capture the sequential nature of the data. 
The project also explores feature engineering, time series preprocessing, and model evaluation.

## Table of Contents

- [Dataset](#dataset)
- [Feature Selection](#feature-selection)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Evaluation](#evaluation)
- [Results](#results)

## Dataset

The dataset used in this project includes historical Bitcoin prices and associated features. The dataset is a CSV file with the following columns:

- Date
- Close
- Volume
- Other relevant features

You can download a sample dataset from Kaggle [Bitcoin Historical Data]([https://www.kaggle.com/mczielinski/bitcoin-historical-data](https://www.kaggle.com/datasets/meetnagadia/bitcoin-stock-data-sept-17-2014-august-24-2021)).

## Feature Selection

The following features are used in the model:

- Historical Prices: Opening, closing, high, and low prices.
- Volume: Trading volume over different periods.
- Market Sentiment: Sentiment scores from social media, news articles, and forums.
- Technical Indicators: Moving averages, RSI, MACD, Bollinger Bands, etc.
- Blockchain Data: Number of transactions, hash rate, miner activity.
- Macroeconomic Indicators: Inflation rates, stock market indices, interest rates.
- External Factors: Regulatory news, technological advancements, adoption rates.

## Data Preprocessing

The data preprocessing steps include:

1. Handling missing values.
2. Feature engineering to create new features like daily returns, rolling means, and rolling standard deviations.
3. Scaling the features using MinMaxScaler.
4. Creating time series datasets for LSTM input.

## Modeling

The main model used in this project is an LSTM neural network. The model architecture includes:

- Two LSTM layers.
- Dense layers for final prediction.

The model is compiled using the Adam optimizer and Mean Squared Error (MSE) loss function.

## Evaluation

The model is evaluated using Mean Squared Error (MSE) and visual comparison of predicted vs. actual prices.

## Results

The predictions from the LSTM model are plotted against actual prices to visually inspect the model's performance.

![Prediction Plot](https://github.com/AmiraQadry/Bitcoin-Price-Prediction/blob/main/Bitcoin%20Price%20Prediction.png)

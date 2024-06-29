# Bitcoin Price Prediction Using Machine Learning
![](data:image/jpeg;base64,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)
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

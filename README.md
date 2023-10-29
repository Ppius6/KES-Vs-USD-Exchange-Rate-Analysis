# KES/USD Exchange Rate Forecasting

## Introduction
This project aims to forecast the exchange rate between the Kenyan Shilling (KES) and the US Dollar (USD) using historical data. The motivation behind this project is to understand the trends and make informed predictions about future exchange rates, crucial for both economic understanding and financial decision-making.

## Data
The dataset used in this project contains daily exchange rates from [source]. The data includes the following columns:
- Date: The date of the observation
- Mean: The average exchange rate of KES against USD on that day
- The timeframe of the dataset spans from [start date] to [end date].

## Methodology
The project utilizes a Long Short-Term Memory (LSTM) model, a type of recurrent neural network that excels in learning from time series data.

## Data Preprocessing
- Normalization: The data was scaled using MinMaxScaler to ease the training process and improve the LSTM model's performance.
- Train-Test Split: The dataset was divided into training and testing sets to validate the model's performance.

## Model Building and Training
- LSTM Network: The neural network was built using [specifics about the layers, units, etc.].
- Compilation: The model was compiled using [loss function] and the Adam optimizer.
- Training: The model was trained over [number] epochs with a batch size of [number].

## Forecasting
- The model was used to forecast the exchange rate trends for the next 365 days.
- Predictions were plotted alongside historical data for visual comparison.

## Results
- The LSTM model successfully captured the underlying trends in the historical data and projected future exchange rate movements. [Discuss any specific findings, patterns, or points of interest.]

## Conclusions and Future Work
- This project demonstrates the potential of LSTM networks in time series forecasting, particularly in financial contexts. While the model provides valuable insights and forecasts, it's important to note that numerous external factors affect exchange rates, and the model's predictions should not be used as sole decision-making criteria.

For future work, the model's accuracy and reliability could be enhanced by:

- Incorporating additional features or economic indicators.
- Exploring different neural network architectures or other machine learning models.
- Applying more sophisticated market-based adjustments based on real-time data.

## Setup and Reproduction
If you wish to reproduce the results or further explore the methodologies used, you will need the following:
- Libraries: pandas, NumPy, scikit-learn, TensorFlow/Keras, matplotlib
- Dataset: Available from Central Bank of Kenya - https://www.centralbank.go.ke/rates/forex-exchange-rates/
- Instructions for setting up:
  - Clone the repository or download the files.
  - Install the necessary Python libraries.


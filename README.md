# financialTimeSeriesForecasting


Name: Farha T k
Register Number: TCR24CS027

## Overview
This project analyzes financial time series data using signal processing and deep learning.

Stock prices of three companies are transformed into spectrograms using STFT, and a CNN model is used to predict future values.

## Data Used
RELIANCE.NS
TCS.NS
INFY.NS
(Data collected using Yahoo Finance)

## Outputs
time_series.png → Time series plot
frequency_spectrum.png → Frequency spectrum
spectrogram.png → Time-frequency representation
cnn_architecture.png → CNN model diagram
prediction.png → Actual vs predicted graph
mse.txt → Mean Squared Error value

## How to Run
Step 1: Clone the repository
git clone https://github.com/FarhaTK101/financialTimeSeriesForecasting.git
cd Financial-Time-Series-Forecasting

Step 2: Create and activate virtual environment
python3 -m venv venv
source venv/bin/activate

Step 3: Install dependencies
pip install -r requirement.txt

step 4: run the program
python predict.py
pip install -r requirement.txt
Step 4: Run the program
python src/predict.py

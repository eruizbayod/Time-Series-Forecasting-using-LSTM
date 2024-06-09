# Time-Series-Forecasting-using-LSTM
OVERVIEW
This project involves predicting future temperatures using 7 years of weather data by employing various time series models such as Moving Window Average, LSTM (single and multi-step), and Transformer models.

DATA SOURCE
The data is sourced from the Max Planck Institute for Biogeochemistry: https://www.bgc-jena.mpg.de/wetter/

MODELS IMPLEMENTED
1. Moving Window Average (MWA): A simple model that calculates the average of past values within a defined window.
2. LSTM (Long Short-Term Memory):
    - Single-Step LSTM
    - Multi-Step LSTM
    - Architecture: LSTM-32, Adam optimizer, trained over 10 epochs, achieving an MAE of 0.19.
    
3. Transformer Model:
    - Single-Step Transformer
    - Multi-Step Transformer
    - Utilizes positional encoding, multi-head attention, and feed-forward neural networks.
    
FEATURES
    - Single Feature: Temperature
    - Multi Features: Temperature, Pressure, Density
    
RESULTS
The LSTM and Transformer models were evaluated based on Mean Absolute Error (MAE). The Transformer model was integrated to potentially improve forecasting accuracy and to provide an advanced architecture for time series prediction.

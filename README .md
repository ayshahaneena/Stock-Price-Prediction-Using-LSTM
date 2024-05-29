
# Stock Price Prediction Using LSTM

This project aims to predict stock prices using a Long Short-Term Memory (LSTM) neural network. LSTM is a type of recurrent neural network (RNN) that is well-suited to sequence prediction problems due to its ability to learn and remember over long sequences.


## Features

- Predicts future stock prices based on historical data.
- Utilizes LSTM architecture for sequence prediction.
- Provides visualization of the predicted vs actual stock prices.
- Can be adapted to different stock data with minimal changes
 


## Data

The project uses historical stock price data, including features like:
- Name	
- Date	
- Open	
- Closing_Price
- Daily_High
- Daily_Low
- Volume
## Dependencies

* numpy==1.19.2
* pandas==1.1.3
* matplotlib==3.3.2
* tensorflow==2.4.1
* scikit-learn==0.24.1

## Model Architecture
Describe the LSTM model architecture:

- Input layer
- LSTM layers with 50 units each
- Dropout(0.2)
- LSTM layers with 50 units each
- Dropout(0.2)
- LSTM layers with 50 units each
- Dropout(0.2)
- Dense layer with one unit (for the final output)
## Results
The model was evaluated using RMSE . The performance metrics on the train and test set are as follows:
- **RMSE** on train : 78.44
- **RMSE** on test : 77.60
## License

This project is licensed under the MIT License.


## Acknowledgements

- Thanks to kaggle for providing the stock price data.
- Inspired by various LSTM tutorials and documentation from TensorFlow.


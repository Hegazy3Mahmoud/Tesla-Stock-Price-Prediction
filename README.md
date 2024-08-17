# Tesla-Stock-Price-Prediction
This project uses an LSTM (Long Short-Term Memory) neural network to predict Tesla stock prices. The model is trained on historical stock data and attempts to predict future prices based on past trends.

## Data

The dataset used is `TSLA.csv`, containing the following columns:
- Date
- Open
- High
- Low
- Close
- Adj Close
- Volume

## Model

The model is built using TensorFlow and Keras and consists of:
- Two LSTM layers with 50 units each
- Dropout layers to prevent overfitting
- A Dense output layer with one unit for the predicted price

## Evaluation

-Test Loss: 0.004195124842226505

-Training Loss: 0.0018

At the end of our predictions, we encountered difficulties because the stock prices were significantly affected by the COVID-19 pandemic, which caused unusual market conditions that our model was not able to predict accurately.

The chart below shows the comparison between the actual and predicted stock prices:


![download](https://github.com/user-attachments/assets/f493ea80-e194-41cc-9766-faa6b4020c03)

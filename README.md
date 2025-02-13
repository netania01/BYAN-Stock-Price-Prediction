
# BYAN Stock Price Prediction

This project aims to analyze and predict the closing stock price of Bayan Resources Tbk (BYAN) using Long Short-Term Memory (LSTM), a type of recurrent neural network (RNN) suitable for time series forecasting. The analysis includes data preprocessing, visualization, and model evaluation.

## Dataset

[BYAN Stock Price](https://drive.google.com/file/d/1CLC_4854GssaStKIaqFgs0xZ2zgt4m37/view?usp=sharing)

[BYAN Stock Price Cleaning](https://drive.google.com/file/d/1LYDxxZc5kjbTJ2e3cciP6YTP_I_CjWAX/view?usp=sharing)



## Features

To run this project, you will need to add the following environment variables to your .env file

`Open Price`

`High Price`

`Low Price`

`Close Price`

`Volume`

## Methodology

1. Data Preprocessing

- Handling missing values

- Normalization using MinMaxScaler

- Splitting data into training and test sets

2. Model Development

- LSTM model with multiple layers and dropout regularization

- Optimizer: Adam

- Loss function: Mean Squared Error (MSE)

- Training with 10 epochs and batch size of 32

3. Model Evaluation

- Mean Absolute Percentage Error (MAPE)

- Mean Squared Error (MSE)

- Mean Absolute Error (MAE)

## Key Findings

1. The LSTM model achieved the following evaluation metrics:

- MAPE: 8.67% (indicating a relatively low prediction error)

- MSE: 1.0395

- MAE: 0.8608

2. The model successfully captures trends in BYAN's closing prices, making it useful for forecasting purposes.



## How to run the project

1. Clone this repository.

2. Install the necessary dependencies using:

```bash
  pip install -r requirements.txt
```

3. Run the Jupyter Notebook

```bash
  jupyter notebook
```

4. Open and execute the notebook step by step.

## Conclusion

The LSTM model provides a reliable method for predicting BYAN's closing stock price. However, further improvements can be made by tuning hyperparameters, incorporating external financial indicators, or experimenting with hybrid models.



## 🔗 Connect with Author
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/netania01)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/netania-pangalinan/)



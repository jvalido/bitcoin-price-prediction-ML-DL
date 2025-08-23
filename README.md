# Bitcoin Price Prediction 📈💸

Welcome to the **Bitcoin Price Prediction** repository! This project
implements and compares various machine learning and deep learning
models to predict Bitcoin prices using historical data from Yahoo
Finance. 🚀

## 📖 Overview

This repository contains Python code for predicting Bitcoin (BTC-USD)
prices using a variety of models, including Ridge, Lasso, ElasticNet,
K-Nearest Neighbors, Decision Trees, Random Forest, Gradient Boosting,
MLP Regressor, and Recurrent Neural Networks (RNN) with SimpleRNN and
LSTM architectures. The code includes data preprocessing, hyperparameter
tuning, model evaluation, and visualizations of actual vs. predicted
prices, along with an ROC curve for price direction prediction. 📊

## 🛠️ Features

-   **Data Source**: Fetches historical Bitcoin price data using
    `yfinance`. 📡
-   **Preprocessing**: Normalizes features and creates sequences for
    time-series modeling. 🔄
-   **Models**: Implements multiple regression models with optimized
    hyperparameters. 🧠
-   **Evaluation**: Compares model performance using MSE and R2 scores.
    📈
-   **Visualizations**: Plots actual vs. predicted prices and RNN
    training loss. 🎨
-   **ROC Curve**: Evaluates price direction prediction (up/down) with
    an ROC curve. 📉

## 📋 Requirements

To run the code, install the required Python packages:

``` bash
pip install yfinance numpy pandas matplotlib scikit-learn tensorflow
```

## 🚀 Getting Started

1.  **Clone the Repository**:

    ``` bash
    git clone https://github.com/shervinnd/bitcoin-price-prediction.git
    cd bitcoin-price-prediction
    ```

2.  **Install Dependencies**: Ensure all required libraries are
    installed (see Requirements).

3.  **Run the Code**: Execute the main script:

    ``` bash
    python deep4.py
    ```

4.  **Explore Results**:

    -   View model performance metrics (MSE, R2).
    -   Check visualizations for actual vs. predicted prices and RNN
        training loss.
    -   Analyze the ROC curve for price direction prediction.

## 📊 Results

The models are evaluated on the last 20% of the dataset, reflecting
their predictive power on recent data. The repository includes: - A
summary table of model performance (MSE and R2 scores). - Plots
comparing actual and predicted Bitcoin prices for all models. - RNN
training loss and ROC curve for price movement classification.

## 🗂️ Repository Structure

-   `deep4.py`: Main script with data preprocessing, model training, and
    evaluation.
-   `README.md`: This file, providing an overview and instructions.

## 🤝 Contributing

Contributions are welcome! Feel free to: - Open issues for bugs or
feature requests. 🐛 - Submit pull requests with improvements or new
models. 💡

## 📜 License

This project is licensed under the MIT License. See the
[LICENSE](LICENSE) file for details.

## 📬 Contact

For questions or suggestions, open an issue or reach out via GitHub.
Let's predict the future of Bitcoin together! 🚀💰

------------------------------------------------------------------------

*Built by Miracle⚡*

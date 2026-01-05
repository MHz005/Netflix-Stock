📈 Netflix Stock Volume Prediction

A regression-based machine learning project focused on predicting Netflix stock trading volume using historical market data. This repository demonstrates a complete, practical data science workflow—from raw data to evaluated model—implemented in a Google Colaboratory notebook.

The goal isn’t to predict the market like a crystal ball, but to apply sound preprocessing, modeling, and evaluation techniques to real-world financial data.

🧠 Project Overview

This project explores how different features of Netflix stock data can be used to model and predict trading volume. The workflow emphasizes clarity and reproducibility, making each step of the pipeline easy to follow and reason about.

Key steps include:

Data inspection and cleaning

Handling categorical variables using one-hot encoding

Training a Random Forest Regressor to capture non-linear relationships

Evaluating model performance using standard regression metrics

🛠️ Tech Stack & Tools

Python

Google Colaboratory

Pandas – data manipulation

NumPy – numerical operations

Scikit-learn – preprocessing, modeling, and evaluation

Matplotlib / Seaborn – basic visualization

📊 Model & Evaluation

The core model used in this project is a Random Forest Regressor, chosen for its ability to handle complex, non-linear patterns commonly found in financial data.

Model performance is evaluated using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

Root Mean Squared Error (RMSE)

R² Score

These metrics provide a balanced view of prediction accuracy and error behavior.

📁 Repository Structure
├── Netflix_Stock.ipynb   # Main Colab notebook containing the analysis
└── README.md             # Project documentation

🚀 How to Run

Open the notebook in Google Colaboratory or any Jupyter-compatible environment.

Ensure required libraries are installed (most are pre-installed in Colab).

Run the notebook cells sequentially to reproduce the analysis and results.

📌 Notes

This project is intended for educational and demonstrative purposes.

It focuses on applied machine learning techniques rather than financial advice or live trading strategies.

Cryptocurrency Price Prediction using LSTM, ANN, and Ensemble Models
This project focuses on predicting cryptocurrency prices, specifically Bitcoin, using deep learning. We implement three models—an Artificial Neural Network (ANN), a Long Short-Term Memory network (LSTM), and an Ensemble model that combines both. The ensemble approach shows improved accuracy by leveraging both time-series and pattern recognition capabilities.

Overview
Built using Google Colab for ease of access and use

Uses a historical Bitcoin dataset (Date, Open, High, Low, Close, Volume)

Preprocesses data using normalization and sequence windowing

Trains three models and compares their results

Visualizes actual vs. predicted prices for analysis

Technologies Used
Google Colab (Python)

Pandas and NumPy

Scikit-learn for preprocessing and metrics

Keras (TensorFlow) for model building

Matplotlib for visualization

Dataset Format
You should use a CSV dataset with the following columns:

mathematica
Copy
Edit
Date, Open, High, Low, Close, Volume
We recommend the publicly available Bitcoin historical price data from Kaggle.

How to Run
Open the provided notebook in Google Colab.

Upload your CSV file containing the historical price data.

Run the notebook step-by-step:

Data cleaning

Train/test preparation

Model training (ANN, LSTM, Ensemble)

Accuracy comparison and graph plotting

Model Performance
Below is the performance comparison of the three models used:

Model	Accuracy (%)
ANN	92.98
LSTM	92.41
Ensemble (ANN + LSTM)	95.19

The ensemble model outperforms both individual models by combining sequential learning (LSTM) with pattern-based learning (ANN).

Visual Output
The notebook provides plots comparing actual vs. predicted prices for each model, allowing you to visualize prediction quality over time.

Future Work
Add multivariate support (e.g., Open, Volume)

Optimize model hyperparameters

Export models for deployment

Build a simple frontend for real-time predictions

License
This project is released under the MIT License. You are free to use, modify, and share it.

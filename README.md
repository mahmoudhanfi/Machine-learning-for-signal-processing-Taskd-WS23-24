# Machine Learning for Signal Processing Tasks WS23-24

This repository contains solutions for various machine learning tasks applied to signal processing, implemented in Jupyter Notebooks. Each notebook addresses different aspects and challenges in the field of signal processing using machine learning techniques.

## Project Structure

- `Task 3.3.ipynb`: **Signal Filtering and Noise Reduction**
  - **Objective**: This task focuses on implementing signal filtering techniques to reduce noise in a given signal.
  - **Logic**: We explore different filtering methods such as low-pass, high-pass, and band-pass filters. The main objective is to understand how these filters can help in enhancing the quality of the signal by attenuating unwanted noise components.
  - **Key Algorithms**: Fourier Transform, Butterworth Filter, Moving Average Filter.

- `task 4.3.ipynb`: **Feature Extraction from Signals**
  - **Objective**: The goal of this task is to extract meaningful features from the signal that can be used for further analysis or machine learning models.
  - **Logic**: We apply various feature extraction techniques such as time-domain analysis (mean, variance, skewness) and frequency-domain analysis (spectral features). These features are crucial for tasks like classification and anomaly detection in signals.
  - **Key Algorithms**: FFT (Fast Fourier Transform), Wavelet Transform, Statistical Measures.

- `task 5.3.ipynb`: **Signal Classification Using Machine Learning**
  - **Objective**: This task aims to classify different types of signals using machine learning algorithms.
  - **Logic**: We build and evaluate machine learning models to classify signals into predefined categories. The process includes data preprocessing, feature selection, model training, and evaluation.
  - **Key Algorithms**: SVM (Support Vector Machine), Random Forest, k-NN (k-Nearest Neighbors).

- `Task 6.3.ipynb`: **Time-Series Forecasting**
  - **Objective**: The focus of this task is on forecasting future values of a signal based on its historical data.
  - **Logic**: We implement time-series forecasting models to predict future trends in the signal. The task involves understanding the temporal dependencies in the data and using appropriate forecasting techniques.
  - **Key Algorithms**: ARIMA (AutoRegressive Integrated Moving Average), LSTM (Long Short-Term Memory) Networks, Exponential Smoothing.

## Prerequisites

To run the notebooks, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook
- Necessary Python packages listed in the requirements section

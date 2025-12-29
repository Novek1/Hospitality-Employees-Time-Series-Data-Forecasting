# Hospitality Employees Time Series Forecasting

![Time Series Graph](https://cdn.prod.website-files.com/64a7eed956ba9b9a3c62401d/64a80371696fdd543e06257a_Orange-and-green-chart-on-blue-background.webp)

## 📌 Project Overview
This project focuses on **time series forecasting** using historical employee data from the hospitality sector. The objective is to model temporal patterns and predict future employee counts using deep learning techniques.

The notebook demonstrates an **end-to-end time series workflow**, covering data exploration, preprocessing, sequence generation, model training, and evaluation.

---

## 📊 Dataset
- **Source:** [Hospitality Employees Time Series Dataset](https://www.kaggle.com/datasets/gabrielsantello/hospitality-employees-time-series-dataset)
- **Type:** Univariate time series
- **Target variable:** Number of employees
- **Frequency:** Time-indexed observations

The dataset captures changes in hospitality employment over time, making it suitable for forecasting and sequence modeling tasks.

---

## 🧠 Methodology

### 1. Exploratory Data Analysis (EDA)
- Visualization of overall trends
- Inspection of time-dependent patterns

### 2. Data Preprocessing
- Feature scaling using normalization
- Train–test split while preserving temporal order
- Sequence creation using a sliding window approach

### 3. Modeling
- Recurrent Neural Network (RNN)
- Implemented with TensorFlow / Keras
- Designed for univariate time series forecasting

### 4. Evaluation
- Mean Squared Error (MSE)
- Visual comparison of predicted vs actual values
- Analysis of forecast deviations

---

## 📈 Results
The trained model:
- Captures general employment trends
- Produces reasonable short-term forecasts
- Highlights limitations of basic RNNs for long-term dependency modeling

This project prioritizes **learning and practical implementation** over aggressive hyperparameter optimization.

---

## 🛠️ Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- TensorFlow / Keras
- Google Colab

---

## 🚀 How to Run
1. Open the notebook in **Google Colab** or Jupyter Notebook
2. Ensure required libraries are installed
3. Run the notebook cells sequentially
4. (Optional) Swap the dataset with another univariate time series to experiment

---

## 📌 Key Takeaways
- Practical experience with time series preprocessing
- Hands-on implementation of RNN-based forecasting
- Understanding of common challenges in sequence modeling
- Foundation for extending to LSTM, GRU, or multivariate forecasting


---

## 📬 Author
**Kevon Bvunza**  
Bachelor of Engineering – Computer Engineering  
Focus: Machine Learning & Time Series Analysis

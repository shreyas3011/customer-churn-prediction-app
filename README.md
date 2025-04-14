# customer-churn-prediction-app
A Streamlit web application that predicts customer churn using a deep learning model trained on a bank dataset.



# Customer Churn Prediction App

This is a Streamlit web application that predicts whether a bank customer is likely to churn based on their profile. The prediction is made using a deep learning model trained on the `Churn_Modelling.csv` dataset.

## 🚀 Features

- Simple and interactive UI using Streamlit.
- Predicts the probability of customer churn.
- Uses a trained TensorFlow model with pre-processing pipelines (Label Encoding, One-Hot Encoding, and Standard Scaling).

## 📁 Project Structure
├── app.py # Streamlit app script ├── prediction.ipynb # Jupyter notebook for prediction testing ├── experiments.ipynb # Jupyter notebook for model training and experimentation ├── model.h5 # Trained TensorFlow model ├── label_encoder_gender.pkl # Saved label encoder for gender ├── onehot_encoder_geo.pkl # Saved one-hot encoder for geography ├── scaler.pkl # Saved standard scaler ├── Churn_Modelling.csv # Dataset used for training


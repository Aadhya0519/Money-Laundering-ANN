# 💰 Money Laundering Detection Using Artificial Neural Networks (ANN)

## 📌 Project Overview

This project is a Machine Learning and Deep Learning based web application that predicts whether a financial transaction is suspicious and potentially related to money laundering.

The model is built using an Artificial Neural Network (ANN) with TensorFlow/Keras and is deployed as an interactive web application using Streamlit.

---

## 🚀 Features

- Predicts whether a transaction is suspicious.
- Interactive Streamlit web interface.
- ANN model built using TensorFlow/Keras.
- Data preprocessing using Scikit-learn.
- Real-time predictions.
- Easy deployment on Streamlit Community Cloud.

---

## 🛠️ Technologies Used

- Python 3.11
- TensorFlow / Keras
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib
- H5py

---

## 📂 Project Structure

```
Deep Learning/
│
├── app.py
├── model.keras
├── preprocessor.pkl
├── requirements.txt
├── README.md
└── dataset.csv (if included)
```

---give 
## 🧠 Model Workflow

The project follows the following workflow:

1. Data Collection
2. Data Cleaning
3. Data Preprocessing
4. Feature Encoding
5. Feature Scaling
6. Train-Test Split
7. ANN Model Training
8. Model Evaluation
9. Save Model and Preprocessor
10. Streamlit Deployment

---

## 🏗️ Model Architecture

The Artificial Neural Network consists of:

- Input Layer
- Hidden Layer(s)
- ReLU Activation Function
- Dropout Layer (to reduce overfitting)
- Output Layer
- Adam Optimizer
- Binary Cross-Entropy Loss Function

---

## 📊 Input Features

The model accepts various transaction-related features, including customer and transaction details. These inputs are preprocessed using the saved `preprocessor.pkl` before making predictions.

---

## 📈 Output

The model predicts whether a transaction is:

- **Legitimate Transaction**
- **Suspicious Transaction**

---

## 📦 Required Libraries

- streamlit
- tensorflow
- numpy
- pandas
- scikit-learn
- h5py
- pickle

---

## 📸 Application Preview

You can add screenshots of the application here after deployment.

Example:

- Home Page
- Input Form
- Prediction Result

---

## 🔮 Future Improvements

- Improve model accuracy through hyperparameter tuning.
- Integrate Explainable AI (XAI) for better prediction transparency.
- Connect the application with a real-time transaction database.
- Deploy using Docker and cloud platforms.
- Add user authentication and transaction history.

---

## 👨‍💻 Author

**Manisha K**

---

## 📜 License

This project is developed for educational and learning purposes.
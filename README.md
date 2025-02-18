# Online-payment-fraud-detection
# 🚀 Fraud Detection Using Neural Networks  

This project implements a deep learning model using **PyTorch** to detect fraudulent financial transactions. The model analyzes transaction patterns and characteristics to identify potential fraud cases.  

## 📌 Overview  
The system processes financial transaction data to detect fraudulent activities by analyzing various features such as **transaction type, amount, and account balances**. A **neural network-based model** is trained to recognize patterns linked to fraudulent transactions.  

## ✨ Features  
✅ **Data preprocessing & exploratory analysis**  
✅ **Transaction pattern visualization**  
✅ **Neural network-based fraud detection**  
✅ **Support for multiple transaction types:**  
   - 🔹 Cash-out  
   - 🔹 Payment  
   - 🔹 Cash-in  
   - 🔹 Transfer  
   - 🔹 Debit  

## 📦 Dependencies  
Ensure you have the following installed before running the project:  
- Python 3.x  
- PyTorch  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

📊 Dataset
The project utilizes a fraud detection dataset containing:

- Transaction type
- Transaction amount
- Original & new account balances
- Fraud labels (binary classification: Fraud/Not Fraud)

🏗️ Model Architecture
The neural network is structured as follows:

- Input layer (based on feature dimensions)
- Two hidden layers (128 & 64 neurons)
- ReLU activation in hidden layers
- Output layer with sigmoid activation

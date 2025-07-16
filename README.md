# 🔍 Bank Customer Churn Prediction using ANN

This project builds an Artificial Neural Network (ANN) model to predict whether a customer is likely to leave a bank (churn) based on personal and account-related features. The dataset contains customer information from a European bank, and the goal is to identify at-risk customers so that the bank can take retention measures.

## 📊 Dataset Overview

The dataset used is [`Churn_Modelling.csv`](./Churn_Modelling.csv), which includes **10,000 customer records** and the following features:

- **Geography**: Country of residence
- **Credit Score**: Creditworthiness indicator
- **Gender**: Male/Female
- **Age**: Customer age
- **Tenure**: Number of years the customer has stayed with the bank
- **Balance**: Bank account balance
- **NumOfProducts**: Number of bank products (e.g., credit cards, loans)
- **HasCrCard**: Whether the customer owns a credit card
- **IsActiveMember**: Whether the customer actively uses bank services
- **EstimatedSalary**: Approximate salary
- **Exited** *(Target)*: 1 = Customer left the bank, 0 = Customer stayed

## ⚙️ Technologies Used

- Python
- Google Colab
- TensorFlow / Keras (for ANN)
- Scikit-learn
- Pandas / NumPy

## 🧠 Model Overview

We developed a classification model using a fully connected **Artificial Neural Network**. The workflow includes:

1. Data Preprocessing (handling categorical data, feature scaling)
2. Building and training the ANN model
3. Making a single prediction on a hypothetical customer

## ✅ Test Case Prediction

We tested the trained ANN model on the following customer:

- **Geography**: France  
- **Credit Score**: 600  
- **Gender**: Male  
- **Age**: 40  
- **Tenure**: 3 years  
- **Balance**: $60,000  
- **Number of Products**: 2  
- **Has Credit Card?** Yes  
- **Active Member?** Yes  
- **Estimated Salary**: $50,000  

### 📣 Prediction Output:
> ❌ Based on the ANN model, this customer is **likely to stay** with the bank.  
> So, **no need to say goodbye** just yet!

> *(Note: This result is based on the trained model and is subject to data generalization and performance metrics.)*

## 📈 Model Performance

- **Test Accuracy**: `86.58%` 

## 📌 Conclusion

This project shows how deep learning can be used for customer retention problems in the banking sector. The model performs well on the test data and can be integrated into a larger customer relationship system.


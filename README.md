##  Customer Churn

# 📊 Customer Churn Prediction using ANN (Deep Learning)

This project uses **Artificial Neural Networks (ANN)** to predict customer churn based on the **Telco Customer Churn dataset**. It involves data preprocessing, model building, evaluation, and visualization.

---

## 🚀 **Project Structure**


---

## 📌 **Dataset Overview**
- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Features:**
  - `customerID`: Unique customer identifier
  - `gender`: Male/Female
  - `SeniorCitizen`: Indicates if the customer is a senior citizen (1 or 0)
  - `tenure`: Number of months the customer has stayed with the company
  - `MonthlyCharges`: Monthly service charges
  - `TotalCharges`: Total charges incurred
  - `Churn`: Target variable (`Yes` or `No`)

---

## 🔥 **Technologies Used**
- Programming Language: **Python 3**
- Libraries:
  - `pandas`, `numpy` → Data processing
  - `sklearn` → Preprocessing, train-test split, and metrics
  - `tensorflow` → Building the ANN model
  - `seaborn`, `matplotlib` → Visualization
- **Model:** ANN with multiple hidden layers and dropout regularization.

---


---

## 📌 **Dataset Overview**
- **Source:** [Kaggle - Telco Customer Churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- **Features:**
  - `customerID`: Unique customer identifier
  - `gender`: Male/Female
  - `SeniorCitizen`: Indicates if the customer is a senior citizen (1 or 0)
  - `tenure`: Number of months the customer has stayed with the company
  - `MonthlyCharges`: Monthly service charges
  - `TotalCharges`: Total charges incurred
  - `Churn`: Target variable (`Yes` or `No`)

---

## 🔥 **Technologies Used**
- Programming Language: **Python 3**
- Libraries:
  - `pandas`, `numpy` → Data processing
  - `sklearn` → Preprocessing, train-test split, and metrics
  - `tensorflow` → Building the ANN model
  - `seaborn`, `matplotlib` → Visualization
- **Model:** ANN with multiple hidden layers and dropout regularization.

---

## ⚙️ **Model Architecture**
- **Input Layer:** 64 neurons with `ReLU` activation  
- **Hidden Layers:**  
    - Layer 1: 128 neurons, `ReLU` activation  
    - Layer 2: 64 neurons, `ReLU` activation  
    - **Dropout layers** to prevent overfitting  
- **Output Layer:**  
    - 1 neuron with `Sigmoid` activation for binary classification  
- **Optimizer:** `Adam`  
- **Loss Function:** `Binary Cross-Entropy`

---

## 🛠️ **Installation and Setup**

### 📥 **1. Clone the Repository**
```bash
git clone <repository-url>
cd Customer_Churn_ANN


---

## 📦 **2. Create a Virtual Environment**
It is recommended to create a virtual environment to isolate the dependencies for the project.

**For Windows:**
```bash
python -m venv venv
venv\Scripts\activate

pip install -r requirements.txt

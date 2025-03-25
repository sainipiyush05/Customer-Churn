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

📦 2. Create a Virtual Environment
It is recommended to create a virtual environment to isolate the dependencies for the project.

For Windows:

bash
Copy
Edit
python -m venv venv
venv\Scripts\activate
For macOS/Linux:

bash
Copy
Edit
python3 -m venv venv
source venv/bin/activate
✅ Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
✅ If you don't have requirements.txt, create one:

bash
Copy
Edit
pip freeze > requirements.txt
🚀 5. Run the Model
Execute the script to train and evaluate the ANN model:

bash
Copy
Edit
python churn_prediction.py
🔥 Future Enhancements
Hyperparameter Tuning: Use GridSearchCV or RandomSearch to optimize the model parameters.

Ensemble Models: Combine ANN with models like XGBoost or RandomForest for improved accuracy.

Deployment: Deploy the model using Flask or FastAPI to create a RESTful API.

Web App: Build a Streamlit or Dash web app for user-friendly predictions.

Feature Selection: Implement Recursive Feature Elimination (RFE) to identify the most significant features.

Automated ML Pipeline: Use MLflow or DVC for experiment tracking and model versioning.

🙌 Contributors
Piyush Saini

📧 Email: piyush.saini@example.com

🛠️ GitHub: Piyush's GitHub

📜 License
This project is licensed under the MIT License.
Feel free to use, modify, and share it for personal or commercial purposes.


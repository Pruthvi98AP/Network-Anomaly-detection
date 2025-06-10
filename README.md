#  Network Anomaly Detection

A Machine Learning project to detect anomalous behavior in network traffic that could indicate potential cyber threats, intrusions, or attacks.

---

##  Project Overview

The goal of this project is to build a model that can distinguish between **normal** and **anomalous** network traffic using machine learning techniques. This helps in improving cybersecurity by identifying suspicious activity in real time.

---

##  Dataset

- **Source**: NSL-KDD / CICIDS / Custom Network Traffic Dataset  
- **Format**: CSV file  
- **Features**:
  - Duration, Protocol Type, Service
  - Source Bytes, Destination Bytes
  - Flag, Count, Same_srv_rate, etc.
- **Target**: Label (Normal, Anomaly or various attack types)

---

##  Technologies Used

- Python 🐍  
- Jupyter Notebook  
- Pandas, NumPy  
- Scikit-learn / XGBoost  
- Seaborn, Matplotlib  
- Flask (for deployment)  
- HTML/CSS/Bootstrap (for front-end)

---

##  ML Workflow

1. **Data Preprocessing**  
   - Encode categorical variables  
   - Handle class imbalance  
   - Normalize features  
2. **Feature Selection**  
   - Correlation matrix / Feature importance  
3. **Model Training**  
   - Logistic Regression, Random Forest, Isolation Forest, XGBoost  
4. **Model Evaluation**  
   - Accuracy, Precision, Recall, F1 Score, Confusion Matrix  
5. **Deployment**  
   - Real-time prediction via Flask web app

---

# Web App Features
Input form to enter network traffic details

Predicts whether the input is Normal or Anomalous

Displays probability/confidence of prediction

#  Results
Achieved high precision and recall using Isolation Forest and Random Forest

Effectively detects anomalies with reduced false positives

# 🧠 Stroke Prediction Machine Learning App

This repository contains the code and trained machine learning model used to predict the risk of stroke based on patient medical attributes.  
The model is deployed as an interactive web application using **Gradio** and hosted on **HuggingFace Spaces**.

---

## 🚀 Live Demo (HuggingFace Space)

👉 **Try the live app here:**  
🔗 https://huggingface.co/spaces/ghenaa/Stroke_Prediction

This interface allows users to enter medical and demographic information and receive a prediction of stroke risk.

---

## 📌 Project Description

The goal of this project is to provide a simple and accessible machine learning tool that predicts the probability of stroke based on:

- Age  
- Gender  
- Hypertension  
- Heart Disease  
- Marital Status  
- Work Type  
- Residence Type  
- Average Glucose Level  
- Body Mass Index (BMI)  
- Smoking Status  

The project includes:
- Data preprocessing  
- Outlier handling  
- Feature scaling  
- SMOTE for imbalance correction  
- Logistic Regression model  
- Threshold optimization for better F1-score  
- Deployment with Gradio  

---

## 🛠️ Technologies Used

| Component | Technology |
|----------|------------|
| Programming Language | Python |
| Model | Logistic Regression |
| Libraries | scikit-learn, imbalanced-learn, joblib |
| Interface | Gradio |
| Deployment | HuggingFace Spaces |
| Environment | Jupyter / Google Colab |

---

## 📦 Files in This Repository

| File | Description |
|------|-------------|
| `app.py` | Gradio application file used in the deployment |
| `logistic_regression_model.joblib` | Trained machine learning model |
| `scaler.joblib` | StandardScaler used for preprocessing |
| `best_threshold.joblib` | Optimal classification threshold |
| `requirements.txt` | Python dependencies |
| `README.md` | Project documentation |

---

## ▶️ Running the Project Locally

To run the app on your local machine:

```bash
git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
cd YOUR_REPO_NAME
pip install -r requirements.txt
python app.py

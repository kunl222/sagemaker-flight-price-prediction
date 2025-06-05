# ✈️ Flight Price Prediction Using AWS SageMaker

This project showcases a complete machine learning pipeline for predicting flight prices using Amazon SageMaker. It covers data preprocessing, exploratory data analysis (EDA), feature engineering, model training with XGBoost, and deployment using Streamlit for real-time predictions.

## 🔗 Project Repository

---

## 📌 Table of Contents
- [Why Amazon SageMaker?](#why-amazon-sagemaker)
- [Libraries Used](#libraries-used)
- [Dataset Information](#dataset-information)
- [Model and Evaluation](#model-and-evaluation)
- [Deployment](#deployment)

---

## 🚀 Why Amazon SageMaker?

Amazon SageMaker is a fully managed cloud service that enables you to:
- Build and train machine learning models at scale.
- Use integrated Jupyter notebooks for easy development.
- Automatically manage the compute infrastructure.
- Easily deploy models as REST endpoints.
- Collaborate and version control using Git.

---

## 📚 Libraries Used

| Library      | Purpose                                  |
|--------------|-------------------------------------------|
| `pandas`     | Data manipulation                         |
| `numpy`      | Numerical operations                      |
| `matplotlib` | Data visualization                        |
| `seaborn`    | Advanced visualization                    |
| `scikit-learn` | Preprocessing, metrics                  |
| `xgboost`    | XGBoost Regressor                         |
| `joblib`     | Model serialization                       |
| `boto3`      | AWS SDK for Python                        |
| `streamlit`  | Web application for real-time predictions |


---

## 🧾 Dataset Information

The dataset includes:
- Airline
- Source and Destination
- Date of Journey
- Departure and Arrival Time
- Duration
- Number of Stops
- Ticket Price (Target variable)

📌 *Note:* The dataset is pre-cleaned for missing values and properly formatted before training.

---

## 📈 Model and Evaluation

- **Model Used:** XGBoost Regressor
- **Evaluation Metric:** R² Score
- **Reason for Choosing XGBoost:** Excellent performance on structured/tabular data, handles overfitting well.

---

## 🌐 Deployment

- The model is serialized using `joblib` and loaded in a `Streamlit` web application.
- Users can input flight details and receive price predictions instantly.

---



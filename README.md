# Customer Segmentation & Churn Prediction

## 📌 Overview
This project performs **customer segmentation** using **K-Means clustering** and builds a **churn prediction model** using machine learning. It helps businesses identify distinct customer groups and predict which customers are likely to churn, allowing for targeted marketing and retention strategies.

## 🚀 Features
- **Customer Segmentation**: Clusters customers into different segments using K-Means.
- **Feature Engineering**: Uses demographic and behavioral data for clustering.
- **Predictive Modeling**: Trains a classifier (Random Forest/XGBoost) to predict churn.
- **Model Evaluation**: Uses accuracy, precision, recall, and F1-score for assessment.
- **Real-Time Prediction**: Predicts churn probability for new customers.

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- **Machine Learning** (K-Means Clustering, Random Forest, XGBoost)
- **SHAP** (For feature importance analysis)
- **Streamlit** (For building an interactive dashboard) *(if applicable)*

## 📊 Project Workflow
1. **Data Preprocessing**
   - Handle missing values
   - Scale numerical features
   - Convert categorical variables
2. **Customer Segmentation (K-Means)**
   - Determine the optimal number of clusters using the Elbow Method & Silhouette Score
   - Assign each customer to a segment
4. **Evaluation & Insights**
   - Check model performance using classification metrics
   - Identify key factors influencing churn

## 🔍 How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Mishthijainn/customer-segmentation.git
   cd customer-segmentation

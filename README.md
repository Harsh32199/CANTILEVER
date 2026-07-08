# 💳 Credit Card Fraud Detection using Machine Learning

## 📌 Project Overview

This project focuses on detecting fraudulent credit card transactions using Machine Learning. Since fraud transactions are extremely rare compared to genuine transactions, the dataset is highly imbalanced. The project applies data preprocessing, exploratory data analysis (EDA), SMOTE for handling class imbalance, and multiple machine learning models to accurately identify fraudulent transactions.

---

## 🎯 Objectives

* Detect fraudulent credit card transactions.
* Handle imbalanced data using SMOTE.
* Compare the performance of different machine learning models.
* Evaluate models using appropriate metrics for imbalanced datasets.
* Save the best-performing model for future predictions.

---

## 📂 Dataset

* **Dataset:** Credit Card Fraud Detection Dataset
* **Source:** Kaggle
* **Total Transactions:** 284,807
* **Fraudulent Transactions:** 492
* **Features:** 30

  * Time
  * Amount
  * V1–V28 (PCA-transformed features)
  * Class (Target Variable)

### Target Variable

* **0** → Genuine Transaction
* **1** → Fraudulent Transaction

---

## 🛠️ Technologies Used

* Python
* JupyterLab
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Imbalanced-learn (SMOTE)
* Joblib

---

## 📊 Exploratory Data Analysis (EDA)

The following analyses were performed:

* Dataset information
* Missing value analysis
* Duplicate value removal
* Class distribution visualization
* Transaction amount distribution
* Transaction time distribution
* Correlation heatmap

---

## ⚙️ Data Preprocessing

* Removed duplicate records
* Split dataset into training and testing sets
* Applied SMOTE only on the training dataset
* Scaled features where required using StandardScaler

---

## 🤖 Machine Learning Models

The following models were trained and evaluated:

1. Logistic Regression
2. Random Forest Classifier

---

## 📈 Evaluation Metrics

The models were evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC Score
* Confusion Matrix
* Classification Report
* ROC Curve

> Since the dataset is highly imbalanced, greater importance was given to Precision, Recall, F1-Score, and ROC-AUC instead of Accuracy.

---

## 📁 Project Structure

```text
Credit_Card_Fraud_Detection/
│
├── data/
│   └── creditcard.csv
│
├── notebooks/
│   └── Fraud_Detection.ipynb
│
├── models/
│   └── fraud_detection_model.pkl
│
├── images/
│
├── README.md
└── requirements.txt
```

---

## 🚀 How to Run

1. Clone the repository.
2. Install the required libraries.
3. Open the notebook in JupyterLab or Jupyter Notebook.
4. Run all cells in sequence.
5. Train the models and evaluate their performance.
6. Save the best-performing model.

---

## 📌 Key Learnings

* Handling imbalanced datasets using SMOTE
* Performing Exploratory Data Analysis (EDA)
* Data preprocessing techniques
* Model training and evaluation
* Comparing multiple machine learning algorithms
* Preventing data leakage by applying SMOTE only to the training data
* Saving trained models using Joblib

---

## 🔮 Future Improvements

* Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
* Cross-validation
* XGBoost and LightGBM implementation
* Streamlit web application for real-time prediction
* Model deployment on cloud platforms

---

## 👨‍💻 Author

**Harsh Aggarwal**

If you found this project useful, feel free to ⭐ the repository and connect with me for discussions on Machine Learning and Artificial Intelligence.

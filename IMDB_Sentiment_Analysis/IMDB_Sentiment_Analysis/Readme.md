# Movie Review Sentiment Analysis using NLP and SVM

## 📌 Project Overview
This project performs sentiment analysis on IMDb movie reviews. It classifies reviews as **Positive** or **Negative** using Natural Language Processing (NLP) techniques and a Support Vector Machine (SVM) classifier.

---

## 🎯 Objective
The objective of this project is to analyze movie reviews, preprocess the text data, extract meaningful features, train a machine learning model, and accurately classify the sentiment of each review.

---

## 🛠️ Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn

---

## 📂 Dataset
- **Dataset:** IMDb Movie Reviews Dataset
- **Size:** 50,000 movie reviews
- **Classes:** Positive, Negative

---

## ⚙️ Workflow
1. Import required libraries
2. Load the dataset
3. Perform Exploratory Data Analysis (EDA)
4. Remove duplicate records
5. Preprocess text
   - Convert text to lowercase
   - Remove HTML tags
   - Remove special characters
   - Remove stopwords
   - Apply stemming
6. Convert text into numerical features using TF-IDF
7. Split the dataset into training and testing sets
8. Train the Support Vector Machine (SVM) model
9. Evaluate the model using:
   - Accuracy
   - Precision
   - Recall
   - F1-Score
   - Confusion Matrix
   - Classification Report
10. Predict sentiment for new movie reviews

---

## 🤖 Machine Learning Algorithm
- Support Vector Machine (SVM)

---

## 📊 Feature Extraction
- TF-IDF (Term Frequency–Inverse Document Frequency)

---

## 📈 Evaluation Metrics
- Accuracy Score
- Precision
- Recall
- F1-Score
- Confusion Matrix
- Classification Report

---

## 📁 Project Structure

```
Movie-Review-Sentiment-Analysis/
│── sentiment_analysis.ipynb
│── IMDB Dataset.csv
│── sentiment_model.pkl
│── tfidf_vectorizer.pkl
│── requirements.txt
└── README.md
```

---

## ▶️ How to Run

1. Install the required libraries:
   ```
   pip install -r requirements.txt
   ```

2. Open `sentiment_analysis.ipynb` in Jupyter Notebook or JupyterLab.

3. Run all cells in sequence.

4. Test the model with your own movie review.

---

## 📌 Output
The trained model predicts whether a movie review is:

- 😊 Positive
- 😞 Negative

---

## 👨‍💻 Author
**Harsh Aggarwal**

# NLP-PROJECT_SENTIMENT-ANALYSIS_RAJ-ARYAN-RAY
# NLP Sentiment Analysis using Machine Learning

## 📌 Project Overview

This project focuses on Sentiment Analysis using Natural Language Processing (NLP) and Machine Learning techniques. The objective of this project is to analyze customer reviews and classify them into:

- Positive Sentiment
- Negative Sentiment
- Neutral Sentiment

The project uses customer review data containing review titles, ratings, and review descriptions to understand customer opinions automatically.

---

## 🎯 Business Objective

Businesses receive thousands of customer reviews every day. Manually analyzing customer feedback is time-consuming and inefficient.

This project helps automate customer feedback analysis using NLP and Machine Learning, enabling businesses to:
- Understand customer satisfaction
- Identify negative feedback quickly
- Improve products and services
- Make data-driven decisions

---

## 📂 Dataset Information

The dataset contains customer reviews with the following columns:

| Column Name | Description |
|---|---|
| title | Review Title |
| rating | Customer Rating |
| body | Review Description |

Dataset Shape:
```python
(1440, 3)
```

---

## 🛠 Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## 📊 Exploratory Data Analysis (EDA)

Performed various EDA techniques to understand the dataset:

- Sentiment Distribution Analysis
- Rating Distribution
- Review Length Analysis
- Word Frequency Analysis
- Data Visualization using Graphs

### Key Insights:
- Positive reviews were higher compared to negative and neutral reviews
- Dataset imbalance was observed
- Customer feedback patterns were identified through visualizations

---

## 🧹 Text Preprocessing

The text data was cleaned and preprocessed using:
- Lowercase conversion
- Punctuation removal
- Stopword removal
- Special character removal

This helped improve model performance and text quality.

---

## 🔠 TF-IDF Vectorization

TF-IDF (Term Frequency–Inverse Document Frequency) was used to convert textual data into numerical format.

Why TF-IDF?
- Assigns importance to meaningful words
- Reduces importance of common words
- Helps machine learning models understand text patterns effectively

---

## 🤖 Machine Learning Models Used

The following models were trained and evaluated:

- Logistic Regression
- Naive Bayes
- Random Forest
- Support Vector Machine (SVM)

---

## ⚖ Handling Imbalanced Data

SMOTE (Synthetic Minority Oversampling Technique) was applied to balance sentiment classes and improve prediction quality.

---

## 📈 Model Evaluation Metrics

Models were evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report
- ROC-AUC Score

---

## 🏆 Final Outcome

The best-performing model successfully predicted customer sentiments as:
- Positive
- Negative
- Neutral

The project demonstrates how NLP and Machine Learning can automate customer sentiment analysis effectively.

---

## 🚀 Future Improvements

Possible future enhancements:
- Deploying using Streamlit or Flask
- Deep Learning implementation using LSTM/RNN
- Real-time sentiment analysis
- WordCloud visualizations

---

## 📷 Project Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Text Preprocessing
5. TF-IDF Vectorization
6. Model Building
7. Model Evaluation
8. Sentiment Prediction

---

## 🙌 Conclusion

This project provided practical understanding of:
- Natural Language Processing
- Text Preprocessing
- Feature Engineering
- Machine Learning
- Sentiment Classification

It also demonstrated how customer review analysis can help businesses improve decision-making using data-driven insights.

---

## 👨‍💻 Author

Raj Aryan Ray

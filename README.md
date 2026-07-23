# 🎬 Survey-Based Analysis of Viewer Expectations, Genre Preferences, and Success Factors in Movies

A machine learning project that analyzes audience opinions on movies using survey-based comments. The project applies Natural Language Processing (NLP) and supervised machine learning techniques to classify movie reviews into sentiment categories and identify the factors influencing audience perceptions.

---

## 📌 Project Overview

This project focuses on understanding viewer expectations, genre preferences, and success factors in movies through sentiment analysis of survey responses. The workflow includes data preprocessing, exploratory data analysis, feature engineering using TF-IDF, model training, explainability with LIME, and comprehensive error analysis.

---

## 🎯 Objectives

- Clean and preprocess survey-based movie comments.
- Perform exploratory data analysis (EDA).
- Extract textual features using TF-IDF.
- Train and compare machine learning models.
- Optimize the best-performing model using hyperparameter tuning.
- Interpret model predictions using LIME.
- Analyze model errors and misclassifications.

---

## 📂 Project Structure

```
Movie_Review_Analysis/
│
├── data/
│   ├── Movie Comments Dataset.xlsx
│   └── clean_movie_comments.csv
│
├── models/
│   └── final_pipeline.pkl
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_text_preprocessing.ipynb
│   ├── 03_model_training.ipynb
│   ├── 04_cross_validation.ipynb
│   ├── 05_hyperparameter_tuning.ipynb
│   ├── 06_feature_importance.ipynb
│   ├── 07_lime_explainability.ipynb
│   └── 08_error_analysis.ipynb
│
├── results/
│   ├── classification_report.csv
│   ├── confusion_matrix.png
│   ├── lime_explanation.html
│   └── misclassified_reviews.csv
│
├── README.md
└── requirements.txt
```

---

## 🛠️ Technologies Used

- Python
- Visual Studio Code
- Jupyter Notebook (VS Code Extension)

### Python Libraries

- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- NLTK
- LIME
- Pickle

---

## ⚙️ Workflow

1. Data Understanding
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis
4. TF-IDF Feature Extraction
5. Machine Learning Model Training
6. Cross Validation
7. Hyperparameter Tuning
8. Feature Importance Analysis
9. LIME Explainability
10. Error Analysis

---

## 🤖 Machine Learning Models Evaluated

- Logistic Regression
- Naive Bayes
- Random Forest

The final model selected was **Logistic Regression** after performance comparison and hyperparameter tuning.

---

## 📊 Model Performance

| Metric | Value |
|---------|-------|
| Accuracy | **84%** |
| Macro F1-Score | **0.76** |
| Weighted F1-Score | **0.83** |

### Best Class Performance

- Excellent → F1 Score: **0.90**
- Poor → F1 Score: **0.87**
- Very Good → F1 Score: **0.86**

---

## 🔍 Explainability

The project uses **LIME (Local Interpretable Model-Agnostic Explanations)** to explain individual predictions by identifying the words that contribute positively or negatively to each sentiment class.

---

## 📈 Results

- Successfully classified movie reviews into five sentiment categories.
- Achieved **84% classification accuracy**.
- Performed feature importance analysis.
- Generated local explanations using LIME.
- Conducted error analysis to identify common misclassification patterns.

---

## 🚀 Future Improvements

- Integrate transformer-based models such as BERT.
- Improve classification for the "Not Good" category.
- Build an interactive web application for real-time sentiment prediction.
- Expand the dataset with multilingual movie reviews.

---

## 👨‍💻 Author

**Vennelakanti Gnana Narasimha Sriman**

B.Tech Computer Science and Engineering  
SRM University – Andhra Pradesh

---

## 📄 License

This project is developed for educational and research purposes as part of the Summer Internship Program at SRM University, Andhra Pradesh.

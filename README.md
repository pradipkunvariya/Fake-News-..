# Fake News Detection using Machine Learning

## 📌 Overview
Fake news spreads misinformation rapidly through digital platforms.  
This project uses **Natural Language Processing (NLP)** and **Machine Learning** techniques to classify news articles as **Fake or Real**.

This is a **beginner-friendly, job-focused data science project** demonstrating an end-to-end ML pipeline.

---

## 📊 Dataset
- File: `fake_news_dataset.csv`
- Columns:
  - `title` – News headline
  - `text` – Full article content
  - `label` – Fake / Real

---

## 🛠️ Technologies Used
- Python
- Pandas & NumPy
- Scikit-learn
- NLTK
- Matplotlib & Seaborn
- Jupyter Notebook

---

## ⚙️ Workflow
1. Data loading and cleaning  
2. Exploratory Data Analysis (EDA)  
3. Text preprocessing  
4. Feature extraction using **TF-IDF**  
5. Model training  
6. Model evaluation and comparison  

---

## 🤖 Machine Learning Models
- Logistic Regression
- Multinomial Naive Bayes
- Passive Aggressive Classifier

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

The **Passive Aggressive Classifier** achieved the best performance due to its efficiency with large sparse text data.

---

## ▶️ How to Run
```bash
git clone https://github.com/your-username/Fake-News-Detection.git
cd Fake-News-Detection
pip install -r requirements.txt
jupyter notebook

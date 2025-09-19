# 📧 Spam Message Classification

This project focuses on classifying SMS messages as **spam** or **ham** using machine learning algorithms. The dataset contains labeled messages, and the goal is to compare different models to find the most accurate and reliable classifier.

---

## 🔹 Features

* Cleaned and preprocessed text data (removing duplicates, punctuation, stopwords, and stemming)
* TF-IDF feature extraction
* Comparison of multiple ML models:

  * **Naive Bayes (Gaussian, Multinomial, Bernoulli)**
  * **SVM, KNN, Logistic Regression, Decision Tree**
  * **Ensemble methods**: Random Forest, Extra Trees, Bagging, AdaBoost, Gradient Boosting, XGBoost
* Performance evaluation using **accuracy** and **precision**

---

## 📊 Results

| Model    | Accuracy | Precision |
| -------- | -------- | --------- |
| KNN      | 0.9052   | 1.0000    |
| NB       | 0.9710   | 1.0000    |
| RF       | 0.9768   | 0.9750    |
| SVC      | 0.9758   | 0.9748    |
| LR       | 0.9565   | 0.9697    |
| ETC      | 0.9778   | 0.9675    |
| XGB      | 0.9710   | 0.9500    |
| GBDT     | 0.9507   | 0.9307    |
| BgC      | 0.9594   | 0.8692    |
| AdaBoost | 0.9236   | 0.8391    |
| DT       | 0.9304   | 0.8367    |

**Best Models:** Multinomial Naive Bayes, Extra Trees Classifier, and Random Forest.

---

## ⚙️ Tech Stack

Python, Pandas, NumPy, Scikit-learn, NLTK, Matplotlib, Seaborn, XGBoost

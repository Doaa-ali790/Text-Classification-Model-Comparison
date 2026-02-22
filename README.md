#  Text Classification Model Comparison

This project performs sentiment analysis on movie reviews and compares a baseline text classification model with an improved optimized model.

The goal is to demonstrate how proper preprocessing and hyperparameter tuning can significantly improve model performance on NLP tasks.

---

##  Project Overview

In this project, we:

* Cleaned and preprocessed movie review text data
* Built a baseline TF-IDF + LinearSVC model
* Developed an improved optimized model
* Compared performance using accuracy and classification metrics

---

##  Dataset

* **Dataset:** Movie Reviews
* **Task:** Binary Sentiment Classification (Positive / Negative)
* **Size:** ~2000 reviews

---

## ⚙️ Models Used

### 🔹 Baseline Model

* TF-IDF (default settings)
* LinearSVC

### 🔹 Improved Model

* TF-IDF with optimized parameters
* Added bigrams (ngram_range=(1,2))
* English stopword removal
* Tuned SVM regularization parameter
* Stratified train/test split

---

## 📊 Results

| Model          | Accuracy |
| -------------- | -------- |
| Baseline Model | 0.85     |
| Improved Model | **0.88** |

📌 For detailed analysis, see **results_comparison.md**

---

##  How to Run

1. Clone the repository:

```bash
git clone https://github.com/Doaa-ali790/Text-Classification-Model-Comparison.git
cd Text-Classification-Model-Comparison
```

2. Install requirements:

```bash
pip install -r requirements.txt
```

3. Run the notebooks.

---

##  Technologies

* Python
* Scikit-learn
* Pandas
* NumPy
* NLP (TF-IDF)

---

##  Future Improvements

* Try Logistic Regression
* Apply lightweight transformers
* Perform cross-validation
* Deploy as an API





**Doaa Ali**
GitHub: https://github.com/Doaa-ali790

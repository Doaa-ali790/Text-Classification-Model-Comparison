#  Model Results Comparison

This document compares the performance of the baseline and improved text classification models on the movie reviews dataset.

---

##  Models

### 🔹 Baseline Model
- TF-IDF + LinearSVC (default settings)

### 🔹 Improved Model
- TF-IDF optimized
- Added bigrams (ngram_range=(1,2))
- Removed English stopwords
- Tuned SVM parameter C
- Stratified train/test split

---

## 📈 Performance Comparison

| Model | Accuracy |
|------|---------|
| Baseline Model | 0.84 |
| Improved Model | **0.88** |

---

## 🔍 Key Observations

- The improved model achieved higher accuracy.
- Using bigrams helped capture phrase-level meaning.
- Hyperparameter tuning improved classification performance.
- Stratified splitting ensured balanced evaluation.

---


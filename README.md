
# Hate Speech Detection on Twitter Data 🐦🛡️

This project implements a machine learning pipeline to detect hate speech in tweets. The goal is to classify tweets into three categories:

- **0**: Hate Speech
- **1**: Offensive Language
- **2**: Neither

The model uses text preprocessing, vectorization with TF-IDF, and various machine learning algorithms to perform classification. The dataset used is from Twitter and provides labeled samples for training and evaluation.

---

## 📁 Project Structure

```
.
├── Hate speech detection on twitter data_live.ipynb
├── README.md
```

---

## 📦 Requirements

To run this project, you will need:

- Python 3.7+
- Jupyter Notebook or any Python IDE
- The following libraries:

```bash
pip install pandas numpy matplotlib seaborn nltk sklearn
```

---

## 🧠 Models Used

The notebook trains and evaluates the following models:

- Logistic Regression

---

## 🧹 Preprocessing Steps

1. **Lowercasing**  
2. **Removing Twitter Handles**  
3. **Removing Punctuation and Special Characters**  
4. **Stopword Removal**  
5. **Lemmatization**  
6. **Tokenization**

The `nltk` library is used for text normalization and stopword removal.

---

## 📊 Evaluation Metrics

The models are evaluated using:

- Accuracy
- Classification Report (Precision, Recall, F1-score)
- Confusion Matrix
- Visualization with Seaborn

---

## 📉 Data Visualization

Exploratory Data Analysis (EDA) includes:

- Class distribution bar plot
- Word clouds for each class
- Word frequency histograms

---

## 📄 Dataset Information

- **Source**: [Kaggle - Hate Speech and Offensive Language Dataset](https://www.kaggle.com/datasets/aniketkudale/twitter-hate-speech)
- **Columns Used**: `class`, `tweet`
- **Classes**:
  - `0`: Hate speech
  - `1`: Offensive language
  - `2`: Neither

---

## 🚀 How to Run

1. Clone this repository.
2. Open the notebook `Hate speech detection on twitter data_live.ipynb`.
3. Run each cell in order.
4. View visualizations and model evaluation at the end.


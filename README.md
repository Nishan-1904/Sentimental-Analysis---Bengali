

# 📊 Sentiment Analysis for Bengali Language

This project performs **sentiment analysis on Bengali text data** using traditional machine learning techniques. The primary goal is to classify Bengali sentences into sentiment categories (e.g., Positive, Negative, Neutral) with high accuracy, leveraging preprocessing techniques and a Support Vector Machine (SVM) classifier.

## 🔍 Overview

* **Language:** Bengali (বাংলা)
* **Model Used:** Support Vector Machine (SVM)
* **Dataset Size:** 10,000 labeled samples (used for training & testing)
* **Techniques:** Text preprocessing, TF-IDF vectorization, model tuning
* **Accuracy Achieved:** Improved from 65% to 79%
* **Libraries:** Scikit-learn, Pandas, NLTK

## 🧠 Key Features

* ✅ Preprocessing of Bengali text data (cleaning, tokenization)
* ✅ Feature extraction using **TF-IDF**
* ✅ Classification using **SVM**
* ✅ Accuracy optimization via iterative model tuning
* ✅ Reduced processing time by **20%** using efficient pipelines

## 🛠️ Tech Stack

| Component          | Tool/Library             |
| ------------------ | ------------------------ |
| Programming Lang   | Python                   |
| ML Algorithms      | SVM (Scikit-learn)       |
| Text Processing    | NLTK, Pandas             |
| Feature Extraction | TF-IDF (TfidfVectorizer) |
| IDE                | Jupyter Notebook         |

## 📁 File Structure

```
📦 Bengali-Sentiment-Analysis
 ┣ 📜 Sentiment Analysis For Bangla Language.ipynb
 ┗ 📜 README.md
```

## 🧪 Results

* Final Accuracy: **79%**
* Dataset: 10,000 samples
* Feature Vector Size (TF-IDF): \~5000 tokens
* Processing time reduced by **20%** through optimized training

## 🧹 Preprocessing Steps

1. Lowercasing text
2. Removing punctuation and stopwords
3. Tokenization (using NLTK)
4. TF-IDF vectorization

## 📈 Model Training

* Algorithm: **Support Vector Machine**
* Vectorizer: **TF-IDF**
* Evaluation Metric: **Accuracy**
* Cross-validation: Performed with stratified splits

## 🚀 How to Run

1. Clone the repository

   ```bash
   git clone https://github.com/yourusername/Bengali-Sentiment-Analysis.git
   cd Bengali-Sentiment-Analysis
   ```

2. Install required libraries

   ```bash
   pip install -r requirements.txt
   ```

3. Open the notebook

   ```bash
   jupyter notebook "Sentiment Analysis For Bangla Language.ipynb"
   ```

## 📚 Dependencies

Add this in `requirements.txt`:

```
scikit-learn
pandas
nltk
matplotlib
```

## ✍️ Author

* **Nishan Chakraborty**
  [LinkedIn](https://www.linkedin.com/in/your-profile) • [GitHub](https://github.com/yourusername)



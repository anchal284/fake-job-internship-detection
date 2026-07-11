# 🛡️ Fake Job & Internship Detection using NLP

An NLP-based machine learning project that detects whether a job or internship posting is **Real** or **Fake** using text classification techniques.

## 📌 Project Overview

Fake job and internship postings are becoming increasingly common across online job portals and social media. This project uses **Natural Language Processing (NLP)** and **Machine Learning** to analyze job descriptions and classify them as genuine or fraudulent.

---

## 🚀 Features

- Data cleaning and preprocessing
- Text normalization
- Stopword removal
- Lemmatization
- TF-IDF feature extraction
- Fake vs Real job classification
- Performance evaluation using classification metrics

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset

The dataset contains job and internship postings labeled as **Real** or **Fake**.

Target column:

- `fraudulent`
  - 0 → Real Job
  - 1 → Fake Job

---

## 🔄 Workflow

1. Load Dataset
2. Data Cleaning
3. Text Preprocessing
4. TF-IDF Vectorization
5. Train-Test Split
6. Train SVM Classifier
7. Evaluate Model
8. Predict New Job Postings

---

## 🧹 Text Preprocessing

The following preprocessing steps were performed:

- Convert text to lowercase
- Remove punctuation
- Remove numbers
- Remove special characters
- Remove extra whitespaces
- Remove stopwords
- Lemmatization

---

## 🤖 Machine Learning Model

### Feature Extraction
- TF-IDF Vectorizer

### Classification Model
- Support Vector Machine (SVM)

---

## 📊 Evaluation Metrics

The model was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

---

## 📁 Project Structure

```
fake-job-internship-detection/
│
├── fakejobposting.ipynb
├── README.md
└── dataset.csv
```

---

## ▶️ How to Run

Clone the repository

```bash
git clone https://github.com/anchal284/fake-job-internship-detection.git
```

Move to the project folder

```bash
cd fake-job-internship-detection
```

Install dependencies

```bash
pip install pandas numpy nltk scikit-learn
```

Open the notebook

```bash
jupyter notebook
```

Run all cells.

---

## 🎯 Future Improvements

- Deploy using Streamlit
- Add BERT-based classification
- Build REST API using Flask/FastAPI
- Improve accuracy using hyperparameter tuning

---

## 👩‍💻 Author

**Anchal**

GitHub: https://github.com/anchal284

---

⭐ If you found this project useful, consider giving it a star.

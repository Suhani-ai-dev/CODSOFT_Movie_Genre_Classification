# CODSOFT_Movie_Genre_Classification
Movie Genre Classification using TF-IDF and Machine Learning
# 🎬 Movie Genre Classification

A Machine Learning project that predicts the **genre of a movie** based on its plot summary using **TF-IDF** and classifiers like **Naive Bayes**, **Logistic Regression**, and **Linear SVM**.

---

## 📌 Problem Statement
Create a model that predicts the genre of a movie based on its plot summary using NLP techniques.

---

## 📂 Dataset
- Source: [Kaggle - Genre Classification Dataset IMDB](https://www.kaggle.com/datasets/hijest/genre-classification-dataset-imdb)
- Files: `train_data.txt`, `test_data.txt`, `test_data_solution.txt`

---

## 🛠️ Tech Stack
- Python
- Google Colab
- Scikit-learn
- TF-IDF Vectorizer
- Pandas, NumPy, Matplotlib, Seaborn

---

## ⚙️ Models Used
| Model | Accuracy |
|-------|----------|
| Naive Bayes | ~52% |
| Logistic Regression | ~58% |
| Linear SVM | ~57% |

---

## 🔄 Steps
1. Load & explore the dataset
2. Clean and preprocess text
3. TF-IDF Vectorization
4. Train multiple ML models
5. Compare accuracies
6. Predict genre for new descriptions

---

## ▶️ How to Run
1. Open `movie_genre_classification.ipynb` in [Google Colab](https://colab.research.google.com/)
2. Download the dataset from Kaggle
3. Run all cells step by step
##0R Run
Google Collab Link:-https://colab.research.google.com/drive/1mMlIgvHBdjgu6fUP3qm2Sw4oTdqlWQLy?usp=sharing
---

- ## 📊 Results
- Best Model: **Logistic Regression** with **58% accuracy**
- Dataset is imbalanced (Drama & Documentary dominate)
- All 3 models used TF-IDF (10,000 features, bigrams)

---

## 👤 Author
- Suhani Parveen
- GitHub: [Suhani-ai-dev](https://github.com/Suhani-ai-dev)

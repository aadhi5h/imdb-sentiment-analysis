# 🎬 IMDb Sentiment Analysis

A complete end-to-end machine learning pipeline for sentiment classification using the IMDb Movie Reviews dataset. This project includes data exploration, text preprocessing, model training, and an interactive sentiment analysis demo.
Created as a project for the Internship in AI — powered by Novolo.ai and AccelerateX.
Created by P S Aadhish.

---

## 📁 Project Structure

```
imdb-sentiment-analysis/
├── data/
│   ├── raw/                  # Raw dataset (IMDB_Dataset.csv)
│   └── processed/            # Cleaned and preprocessed dataset
├── notebooks/
│   ├── 01_data_exploration.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_model_training.ipynb
│   ├── 04_evaluation_visualization.ipynb
│   └── 05_interactive_demo.ipynb
├── models/                   # Saved models and vectorizers
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## 📦 Installation

```bash
# Create virtual environment
python -m venv sentiment_env

# Activate environment
# Windows:
sentiment_env\Scripts\activate
# Mac/Linux:
source sentiment_env/bin/activate

# Install dependencies
pip install -r requirements.txt
```

---

## 📚 Dataset

- **Name:** IMDb Movie Reviews
- **Size:** 50,000 labeled movie reviews (positive/negative)
- **Source:** [Kaggle IMDb Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)

📂 Place the CSV file as: `data/raw/IMDB_Dataset.csv`

---

## 🚀 How to Run

1. **Exploratory Data Analysis**: `01_data_exploration.ipynb`
2. **Text Cleaning + Preprocessing**: `02_preprocessing.ipynb`
3. **Model Training + Evaluation**: `03_model_training.ipynb`
4. **Interactive UI Demo**: `05_interactive_demo.ipynb`

---

## 📊 Models Trained

- Logistic Regression
- Multinomial Naive Bayes
- Support Vector Machine (SVM)

📦 Best model and vectorizer saved in `models/`

---

## ✨ Interactive Demo

Use the notebook `05_interactive_demo.ipynb` to try out live sentiment predictions using custom input text.

---

## 📈 Evaluation

Includes:

- Accuracy, cross-validation scores
- Confusion matrix
- Feature importance for best model

---

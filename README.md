# 🎬 IMDb Sentiment Analysis

This project develops an automated system for classifying movie reviews as **positive** or **negative**, leveraging both classical machine learning techniques (TF-IDF + Logistic Regression) and modern neural approaches (BERT).

---

## 🧠 Objective

To build a comprehensive pipeline for sentiment analysis, including:
- Text cleaning and preprocessing
- Model development using TF-IDF, Word2Vec, and BERT
- Comparative evaluation of model performance
- An interactive interface for predicting sentiment on new reviews

---

## 📁 Project Structure
```
├── data/                 # Raw and processed datasets
├── notebooks/            # Exploratory Data Analysis (EDA) and experiments
├── src/                  # Code for preprocessing, training, and inference
├── models/               # Saved model files
├── app/                  # Streamlit web application
├── requirements.txt      # Project dependencies
├── .gitignore            # Git ignore file
└── README.md             # Project documentation
```

---

## 💻 Technologies Used

### 🧰 Languages and Libraries
- **Python 3.8+**  
- **pandas**, **numpy** — Data manipulation and analysis  
- **scikit-learn** — Classical machine learning models  
- **nltk**, **beautifulsoup4** — Text preprocessing and cleaning  
- **matplotlib**, **seaborn** — Data visualization  
- **joblib** — Model serialization  
- **gensim** — Word2Vec for word embeddings  
- **transformers**, **torch** — BERT for deep learning-based sentiment analysis  
- **streamlit** — Interactive web interface for model inference  

---

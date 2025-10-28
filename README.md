# 🎬 MovieSentimentXGBoost

An end-to-end **Sentiment Analysis Web App** that predicts whether a movie review is **positive or negative** using **XGBoost** and **scikit-learn** with **TF-IDF text features** and **Flask** for real-time inference.

---

## 🚀 Project Overview

This project demonstrates how to build, tune, and deploy a sentiment classification model using:
- **XGBoost** for gradient boosting on text data  
- **scikit-learn** for pipeline construction, preprocessing, and model evaluation  
- **GridSearchCV** for hyperparameter optimization  
- **TF-IDF Vectorization** for text representation  
- **Flask** for serving model predictions via a web app  

---

## 🧠 Features
- Trains a movie review sentiment classifier on the **NLTK Movie Reviews dataset**  
- Uses **GPU-accelerated XGBoost** for faster training  
- Implements **GridSearchCV** (scikit-learn) for hyperparameter tuning  
- Combines preprocessing + model in a **scikit-learn Pipeline**  
- Saves and loads models using **joblib**  
- Deploys via a **Flask web app** with both form input and JSON API endpoint  

---


## ⚙️ Setup & Installation

### 1️) Clone the repository
```bash
git clone https://github.com/<your-username>/MovieSentimentXGBoost.git
cd MovieSentimentXGBoost

### open your browser and navigate to:

http://127.0.0.1:5000

### Model Training (scikit-learn + XGBoost)

python sentiment_training.ipynb




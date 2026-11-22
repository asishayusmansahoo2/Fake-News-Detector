<div align="center">

# 📰 Fake News Detector

**An end-to-end machine learning project that classifies news articles as real or fake.**

[![Python](https://img.shields.io/badge/Python-3.10+-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML-orange?logo=scikitlearn&logoColor=white)](https://scikit-learn.org/)
[![TensorFlow](https://img.shields.io/badge/TensorFlow-LSTM-ff6f00?logo=tensorflow&logoColor=white)](https://www.tensorflow.org/)
[![Streamlit](https://img.shields.io/badge/Streamlit-App-ff4b4b?logo=streamlit&logoColor=white)](https://streamlit.io/)

### [🚀 Live Demo on Hugging Face](https://huggingface.co/spaces/asish16/Fake-News-Detection)

</div>

---

## 📌 Overview

Misinformation spreads fast. This project builds a text classifier that predicts whether a news article is **real** or **fake**, using classical ML models and a deep learning (LSTM) model, deployed as an interactive web app.

## ✨ Features

- Text preprocessing (cleaning, stopword removal, tokenization)
- TF-IDF feature extraction
- Multiple models compared: Logistic Regression, Naive Bayes, Random Forest
- LSTM neural network for sequence-based classification
- Interactive Streamlit app deployed on Hugging Face Spaces

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| Language | Python |
| Data | Pandas, NumPy |
| ML | Scikit-learn |
| Deep Learning | TensorFlow / Keras |
| App | Streamlit |
| Deployment | Hugging Face Spaces, Docker |

## 📂 Project Structure

```
Fake-News-Detector/
├── app.py                # Streamlit app
├── requirements.txt      # Dependencies
├── Dockerfile            # Container config
├── notebooks/            # Training & EDA notebooks
├── models/               # Saved models / vectorizer
└── README.md
```

## 📊 Model Results

| Model | Accuracy |
|---|---|
| Logistic Regression | XX% |
| Naive Bayes | XX% |
| Random Forest | XX% |
| LSTM | XX% |

> Replace `XX%` with your actual results.

## 🚀 Run Locally

```bash
git clone https://github.com/asishayusmansahoo2/Fake-News-Detector.git
cd Fake-News-Detector
pip install -r requirements.txt
streamlit run app.py
```

## 📁 Dataset

Trained on a fake/real news dataset from [Kaggle](https://www.kaggle.com/).

## 🔮 Future Improvements

- Try transformer models (BERT)
- Add explainability (LIME/SHAP)
- Support URL input for live articles

## 👤 Author

**Asish Ayusman Sahoo**
Data Analytics & AI/ML | Bhubaneswar, India
[GitHub](https://github.com/asishayusmansahoo2)

---

⭐ If you found this useful, consider giving it a star!

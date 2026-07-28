# 🛒 Amazon Review Intelligence Platform

🚀 **Enterprise Sentiment Analysis Platform powered by Fine-Tuned DistilBERT & Streamlit**

An end-to-end AI platform that analyzes Amazon customer reviews using Natural Language Processing (NLP) and Deep Learning.
The system provides real-time sentiment prediction and interactive analytics dashboards to understand customer feedback at scale.

---

## 🌟 Project Overview

**Amazon Review Intelligence** is an AI-powered sentiment analysis application designed to automatically classify customer reviews into:

* ✅ Positive Sentiment
* ❌ Negative Sentiment

The platform uses a fine-tuned **DistilBERT Transformer model** trained on Amazon product reviews and deployed through an interactive Streamlit dashboard.

---

## 🚀 Live Features

### 🔮 AI Sentiment Predictor

Users can enter any product review and instantly receive:

* Sentiment classification
* Confidence score
* Positive probability
* Negative probability
* Detailed prediction information

Example:

Input:

> Absolutely amazing product! The quality exceeded my expectations. Everything works perfectly and I highly recommend it.

Output:

```
Positive (100%)
👍 Positive Probability: 100%
```

---

### 📊 Enterprise Analytics Dashboard

The dashboard provides comprehensive insights from Amazon reviews:

#### Key Performance Indicators

* Total Reviews Count
* Average Rating
* Positive Sentiment Percentage
* Average Review Length

#### Visual Analytics

Included visualizations:

⭐ Star Rating Distribution

👍 Positive vs Negative Sentiment Distribution

📏 Review Length Analysis

🔝 Most Frequent Words

☁️ Positive & Negative Word Clouds

📅 Monthly Review Trends

---

## 🧠 Machine Learning Model

### Fine-Tuned Model

Model:

```
DistilBERT for Sequence Classification
```

Architecture:

```
Input Review Text
        |
        ↓
DistilBERT Tokenizer
        |
        ↓
Fine-Tuned DistilBERT
        |
        ↓
Softmax Classification
        |
        ↓
Positive / Negative Sentiment
```

Model Performance:

```
Accuracy: 95%+
```

---

## 🤗 Model Hosting

The trained model is hosted on Hugging Face:

Model Repository:

```
FatmaEissa1/amazon-review-sentiment-distilbert
```

The Streamlit application automatically downloads the model during deployment.

---

## 🏗️ Project Structure

```
AMAZON-REVIEW-SENTIMENT-ANALYSIS
│
├── app.py                         # Streamlit Application
├── requirements.txt               # Dependencies
├── README.md
│
├── data/
│   ├── amazon_sample_100k.csv
│   └── absa_dashboard_data.csv
│
├── images/
│   ├── positive_prediction.png
│   ├── negative_prediction.png
│   └── analytics_dashboard.png
│
└── notebooks/
    └── amazon-product-reviews.ipynb
```

---

## 🛠️ Technologies Used

### Programming

* Python

### Machine Learning / NLP

* PyTorch
* Hugging Face Transformers
* DistilBERT
* Natural Language Processing

### Data Analysis

* Pandas
* NumPy
* Scikit-learn

### Visualization

* Plotly
* Matplotlib
* WordCloud

### Deployment

* Streamlit
* Hugging Face Hub

---

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/FatmaEissa1/AMAZON-REVIEW-SENTIMENT-ANALYSIS.git
```

Navigate to the project:

```bash
cd AMAZON-REVIEW-SENTIMENT-ANALYSIS
```

Create virtual environment:

```bash
python -m venv venv
```

Activate environment:

Windows:

```bash
venv\Scripts\activate
```

Install requirements:

```bash
pip install -r requirements.txt
```

---

## ▶️ Run Application

Start Streamlit:

```bash
streamlit run app.py
```

The application will open automatically in your browser.

---

## 📸 Application Screenshots

### 🔮 Positive Sentiment Prediction

![Positive Prediction](images/positive_prediction.png)

### ❌ Negative Sentiment Prediction

![Negative Prediction](images/negative_prediction.png)

### 📊 Analytics Dashboard

![Analytics Dashboard](images/analytics_dashboard.png)

---

## 🎯 Business Applications

This platform can help businesses:

* Monitor customer satisfaction
* Analyze product feedback
* Detect customer complaints
* Improve product quality
* Support data-driven decisions

---

## 👩‍💻 Author

**Fatma Eissa**

AI Engineer | Machine Learning | Computer Vision | NLP

GitHub:

```
https://github.com/FatmaEissa1
```

---

⭐ If you find this project useful, consider giving it a star!

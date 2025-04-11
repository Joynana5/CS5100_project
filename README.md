# 🧠 Bias and Sentiment Detection in Social Media

This project investigates how **bias** can manifest in both traditional and AI-based sentiment classification models using real-world tweet data. Our goal is to compare **traditional machine learning approaches** and **modern deep learning models** in terms of performance and fairness, while exploring the limitations and potential biases each introduces.

---

## 📁 Dataset

We use the [Bias Detection Combined](https://huggingface.co/datasets) dataset from Hugging Face. This dataset contains thousands of tweets, each labeled with a **sentiment**:
- `0` — Neutral  
- `1` — Personally driven sentiment (Positive or Negative)

---

## 🔍 Project Goals

- Analyze the **bias and fairness** in traditional and AI-based sentiment classifiers.
- Compare **Logistic Regression** with **Transformer-based AI models**.
- Examine **how different models misclassify tweets** and whether bias is reflected in those misclassifications.
- Identify key challenges in bias mitigation and model interpretability.

---

## 🧪 Methods

### ✅ Traditional Machine Learning (Non-AI)

**Model:** Logistic Regression  
**Implemented by:** Joynae Whitehurst

We selected logistic regression for its:
- **Interpretability** – easily reveals which features impact decisions.
- **Efficiency** – fast training and testing, making it ideal as a baseline.

📊 Current Results (Confusion Matrix Highlights):


### 🤖 AI-Based Model (Coming Soon)

- **Model:** BERT-based or GPT-based Transformer
- **Goal:** Compare its performance and fairness with the traditional model
- **Focus:** Interpretability challenges and potential amplification of bias

---

## 🖼️ Visualizations

Confusion matrices and other visualizations are created to analyze misclassifications and model performance. Example:

![Confusion Matrix](image.png)

---

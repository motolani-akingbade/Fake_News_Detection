# 📰 AI-Powered Fake News & Misinformation Detection System

This project focuses on detecting fake news and AI-generated content using machine learning and natural language processing (NLP) techniques. It integrates TF-IDF, Logistic Regression, and GPT-2 generated headlines to build a robust misinformation detection pipeline. Real-world testing, root cause analysis, and ethical considerations are incorporated using the Toyota Business Practice.

---

## 🚀 Try It Now on Google Colab

Click the button below to open and run the notebook directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1tgsPr5W1tKB2yd-gVjL2mzWPesOdQdYe?authuser=1#scrollTo=WeHpeENZ6LlO![image](https://github.com/user-attachments/assets/4ebb5105-cf8a-4318-8fa8-88e4d400eb2b)
)

---

## 📂 Dataset

The following datasets are used in this project:

- `news.csv`: Contains real news headlines.
- `synthetic_headlines.csv`: GPT-2 generated fake headlines based on clickbait, science, and conspiracy prompts.

The notebook creates a **balanced dataset** of real and synthetic headlines, used for binary classification.

✅ **Note**: The dataset is generated or downloaded within the notebook — no manual uploads required.

---

## 🔧 Environment Setup

All dependencies are installed automatically at the top of the notebook.

### Main Libraries Used:

- `pandas`
- `numpy`
- `scikit-learn`
- `nltk`
- `matplotlib`
- `seaborn`
- `transformers` (for future improvements using BERT)

For local development:

```bash
pip install pandas numpy scikit-learn nltk matplotlib seaborn transformers

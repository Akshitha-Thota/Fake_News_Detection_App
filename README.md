# Fake News Detection Project

## 📌 Overview

The topic of fake news detection on social media has recently attracted tremendous attention. The basic countermeasure of comparing websites against a list of labeled fake news sources is inflexible, and so a machine learning approach is desirable.

Our project aims to use Machine Learning algorithms to detect fake news directly, based on the **text content** of news articles.

---

## ❓ Problem Definition

The goal is to develop a machine learning program to identify when a news source may be producing fake news.

- We aim to use a **corpus of labeled real and fake news articles** to build a classifier.
- The model will focus on identifying **fake news sources** based on **multiple articles** originating from a source.
- Once a source is labeled as a fake news producer, we can confidently flag future articles from that source as fake.
- This approach reduces article-level misclassification by leveraging **source-level data**.

📌 The intended application is to apply **visibility weights** in social media platforms.  
Using the model's output, platforms can **reduce the visibility** of content likely to be fake.

---

## 🗂️ Project Planning

1. **Data Collection**
2. **Model Building**
3. **Backend Work**
4. **Deployment**


---

## ⚙️ Installation

Use the package manager `pip` to install required libraries.

```bash
pip install virtualenv
virtualenv env_name
env_name/scripts/activate


## 🚀 Start Project

Follow these commands to start your project:

```bash
pip install -r requirements.txt
python app.py

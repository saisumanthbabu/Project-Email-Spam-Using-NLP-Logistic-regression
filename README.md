# 📧 Email Spam Detection Using NLP and Logistic Regression

A machine learning project for automatically classifying text messages as **Spam** or **Not Spam** using **Natural Language Processing (NLP)** and **Logistic Regression**.

The project demonstrates a complete machine learning workflow, including text preprocessing, feature extraction, model training, evaluation, and visualization.

---

## 📌 Project Overview

Spam messages are unwanted and potentially harmful messages that can contain advertisements, fraudulent content, or misleading information. This project aims to automatically identify spam messages using machine learning and NLP techniques.

The **SMS Spam Collection Dataset** is used to train and evaluate the classification model. The text data is processed and converted into numerical features before being provided to the Logistic Regression classifier.

---

## 📂 Dataset

The project uses the **SMS Spam Collection Dataset**, containing approximately **3,000 messages** categorized as:

- **Spam** – Unwanted or suspicious messages
- **Not Spam (Ham)** – Normal messages

The dataset is used for training and evaluating the spam classification model.

---

## 🔄 Machine Learning Workflow

```text
Raw Text Data
      ↓
Data Preprocessing
      ↓
Text Cleaning
      ↓
Feature Extraction
      ↓
Train-Test Split
      ↓
Logistic Regression
      ↓
Model Evaluation
      ↓
Spam / Not Spam Prediction

# Sentiment Analysis Using NLP

## 📌 Project Overview

This project implements a **Natural Language Processing (NLP)** based sentiment analysis system using the **IMDb Movie Reviews dataset**.

The objective of this project is to develop a machine learning model capable of classifying movie reviews into two sentiment categories:

- Positive
- Negative

The project follows a complete NLP workflow including text preprocessing, feature extraction using TF-IDF, sentiment classification using Logistic Regression, and model evaluation.

This project was completed as part of the **EncoderX Remote Internship – AI/ML Batch 02, Week 02**.

---

## 🎯 Objectives

The main objectives of this project are:

- To understand the basic NLP workflow.
- To preprocess and clean textual data.
- To remove unnecessary noise from reviews.
- To extract numerical features from text using TF-IDF.
- To train a sentiment classification model.
- To evaluate the model using Accuracy, Precision, Recall, and F1-Score.
- To analyze classification results using a confusion matrix.
- To identify practical applications and possible improvements.

---

## 📊 Dataset

The project uses the **IMDb Movie Reviews dataset**.

The dataset contains movie reviews labeled according to their sentiment.

### Sentiment Classes

| Label | Sentiment |
|------:|-----------|
| 0 | Negative |
| 1 | Positive |

The dataset is divided into training and testing data for building and evaluating the sentiment classification model.

---

## 🔄 NLP Workflow

The project follows these main steps:

```text
Raw Movie Reviews
        ↓
Text Preprocessing
        ↓
Cleaned Text
        ↓
TF-IDF Feature Extraction
        ↓
Logistic Regression
        ↓
Sentiment Prediction
        ↓
Model Evaluation

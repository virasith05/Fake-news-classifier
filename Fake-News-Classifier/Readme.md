# Fake News Classifier

A machine learning project that classifies news articles as real or fake using a variety of supervised learning models. The classifier uses advanced NLP preprocessing and applies several ML algorithms to compare their accuracy in distinguishing fake news.

## Table of Contents
- [Fake News Classifier](#fake-news-classifier)
  - [Table of Contents](#table-of-contents)
  - [Project Overview](#project-overview)
  - [Features](#features)
  - [Model Architecture](#model-architecture)
  - [Installation](#installation)
  - [Usage](#usage)
  - [Results](#results)

## Project Overview

This project is a comprehensive approach to fake news detection using machine learning techniques, designed to help MSCS students and researchers learn the mechanics of classification algorithms in NLP. It compares various models like Random Forest, Naive Bayes, SVM, Decision Tree, and XGBoost. Each model's performance is evaluated using metrics such as accuracy and confusion matrices.

## Features

- **Multi-Model Comparison**: Random Forest, Naive Bayes, SVM, Decision Tree, KNN, XGBoost, and other models are applied to understand their efficacy on fake news detection.
- **Explainable Model Outputs**: Confusion matrices and accuracy scores for each model to compare performance.
- **Customizable Data Preprocessing**: Advanced text cleaning and tokenization techniques to handle different text variations.

## Model Architecture

The project uses traditional machine learning models with text processing to classify fake news, as described below:

1. **Data Preprocessing**:
   - Removal of punctuation and stopwords.
   - Lemmatization to handle word forms.
   - Vectorization with CountVectorizer.

2. **Machine Learning Models**:
   - Trained and compared models including **Random Forest**, **Naive Bayes**, **Support Vector Machine (SVM)**, **Decision Tree**, **KNN**, **XGBoost**, **AdaBoost**, and **Perceptron**.
   - Metrics like accuracy and confusion matrices are used to evaluate model performance.

3. **Evaluation and Visualization**:
   - Model accuracies are visualized through bar plots.
   - Confusion matrices for each model provide insights into prediction performance.

## Installation

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/fake-news-classifier.git
    cd fake-news-classifier
    ```

2. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

3. **Download the Dataset**:
   - Ensure you have a dataset labeled with news article titles and labels (real/fake). We recommend using the [Fake News Dataset](https://www.kaggle.com/c/fake-news/data).

## Usage

1. **Train and Test Models**:
   Open the Jupyter Notebook `news_classification.ipynb` to execute the data preprocessing, training, and evaluation of models.

2. **Visualize Results**:
   Use the notebook's built-in visualization commands to compare model performance through confusion matrices and accuracy plots.

## Results

The models achieved varying levels of accuracy, with **Random Forest** and **XGBoost** performing well on benchmark datasets. Visualization and evaluation provide insights into the effectiveness of each model for the classification task.



# E-commerce Review Sentiment Analysis

A beginner-friendly machine learning project that classifies e-commerce customer reviews as **Positive** or **Negative** using Python, TF-IDF, and Logistic Regression.

This project was built to understand the basic workflow of a Natural Language Processing (NLP) based sentiment analysis system.

---

## Project Overview

Customer reviews are important for understanding product quality, customer satisfaction, and business performance.  
In this project, I built a simple sentiment analysis model that takes a customer review as input and predicts whether the review is positive or negative.

Example:

| Review | Prediction |
|---|---|
| "The product quality is excellent and worth the price" | Positive |
| "Very bad product, waste of money" | Negative |

---

## Tech Stack

- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TF-IDF Vectorizer
- Logistic Regression

---

## Machine Learning Pipeline

The project follows this basic ML workflow:

1. Created / loaded customer review data
2. Cleaned the text data
3. Converted text into numerical features using TF-IDF
4. Split the data into training and testing sets
5. Trained a Logistic Regression model
6. Evaluated the model using accuracy and confusion matrix
7. Tested the model with custom review examples

---

## How It Works

The model does not understand raw text directly.  
So, first the review text is cleaned and converted into numbers using **TF-IDF Vectorization**.

Then a **Logistic Regression** model is trained on the processed data to learn patterns from positive and negative reviews.

For example, words like:

- "excellent"
- "amazing"
- "good"
- "worth"

are usually connected with positive reviews.

Words like:

- "bad"
- "waste"
- "poor"
- "disappointed"

are usually connected with negative reviews.

---

## Features

- Text preprocessing
- Sentiment classification
- TF-IDF feature extraction
- Logistic Regression model training
- Accuracy evaluation
- Confusion matrix visualization
- Custom review prediction

---

## Project Structure

```text
ecommerce-review-sentiment-analysis/
│
├── Ecommerce_Review_Sentiment_Analysis.ipynb
├── README.md
└── .gitignore
```
## Sample Prediction
- Review: The product is amazing and delivery was fast
- Predicted Sentiment: Positive

- Review: Worst product, completely waste of money
- Predicted Sentiment: Negative

## Results

The model was evaluated using test data.

Accuracy: 16.67%

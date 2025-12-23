Based on the project files, here is a comprehensive README for your repository.

---

# Forecasting Catastrophe: Disaster Tweet Prediction Using NLP

This project leverages Natural Language Processing (NLP) techniques to identify and classify tweets that report real disasters. In the era of social media, rapid identification of disaster-related information can serve as a critical precautionary tool for emergency management and response teams, potentially saving lives through timely intervention.

## Table of Contents

* [Overview](https://www.google.com/search?q=%23overview)
* [Dataset](https://www.google.com/search?q=%23dataset)
* [Methodology](https://www.google.com/search?q=%23methodology)
* [Technologies Used](https://www.google.com/search?q=%23technologies-used)
* [Key Features](https://www.google.com/search?q=%23key-features)
* [Results](https://www.google.com/search?q=%23results)

## Overview

Social media platforms like Twitter (X) are often the first place disaster news breaks. However, the high volume of daily posts makes it challenging to filter actual emergency alerts from metaphorical language (e.g., "The concert was a disaster"). This project focuses on building an automated classification model to distinguish between disaster-related and non-disaster-related tweets.

## Dataset

The project utilizes a training and test dataset of categorized tweets:

* **Training Set**: 7,613 observations.
* **Test Set**: 3,263 observations.
* **Features**: Includes tweet ID, keyword, location, and the tweet text.

## Methodology

The pipeline involves extensive text preprocessing and advanced modeling:

### 1. Text Preprocessing

To clean and normalize the raw social media data, the following steps were implemented:

* **URL & Emoji Removal**: Cleaning irrelevant web links and pictographs.
* **HTML & Punctuation Removal**: Eliminating noise from web scraping and standard grammar marks.
* **Tokenization**: Breaking text into individual words.
* **Stopword Removal & Lemmatization**: Reducing words to their base form (e.g., "evacuation" to "evacuate") to focus on core meaning.
* **POS Tagging**: Applying Part-of-Speech tags for better linguistic understanding.

### 2. Exploratory Data Analysis (EDA)

The project includes visualization of:

* Target distribution (disaster vs. non-disaster).
* Word clouds and frequency distributions of keywords.

### 3. Modeling

The repository explores several machine learning and deep learning approaches:

* **Traditional ML**: Vectorization using `CountVectorizer` and `TfidfVectorizer`.
* **Deep Learning**: Implementation of **BERT** (Bidirectional Encoder Representations from Transformers) for sequence classification using the `transformers` library and `PyTorch`.

## Technologies Used

* **Programming Language**: Python
* **NLP Libraries**: NLTK, Spacy
* **Machine Learning**: Scikit-learn
* **Deep Learning**: PyTorch, Transformers (Hugging Face)
* **Visualization**: Matplotlib, Seaborn, WordCloud

## Key Features

* Full NLP pipeline from raw text to model prediction.
* Comparison between traditional TF-IDF approaches and state-of-the-art Transformer models.
* In-depth visualization of disaster-specific keywords and linguistic patterns.

## Contributors

* **Dharanidhar Manne**
* **Ravi Prasad Grandhi**

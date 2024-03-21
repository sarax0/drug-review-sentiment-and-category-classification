## Drug Reviews - NLP Analysis (Sentiment & Classification)

This repository implements Natural Language Processing (NLP) techniques to analyze drug reviews. It focuses on:

* **Sentiment Analysis:** Identifying reviewer opinions on the drugs (positive, negative, etc.)
* **Drug Type Classification:** Categorizing drugs based on the review content using a machine learning model

![image](https://github.com/sarax0/drug-review-sentiment-and-category-classification/assets/122404545/90971ca9-9cb2-48c0-9eb8-1fa580c323f0)

This project provides a framework for exploring drug review data and extracting valuable insights.

# Key functionalities:

* **Exploratory Data Analysis (EDA):**
  * Generates visualizations (word clouds, bar charts, pie charts) to understand:
    * Drug name distribution
    * Reviewer sentiment distribution (positive/negative)
    * Top medical conditions mentioned
    * Drug usage patterns for specific conditions 
* **Data Preprocessing:**
  * Cleans text data by removing special characters 
  * Tokenizes text into individual words 
  * Removes stop words (common words with little meaning)
  * Identifies named entities (specifically drug names) 
  * Applies lemmatization to reduce words to their base form (e.g., "running" -> "run") 
* **Sentiment Analysis:**
  * Analyzes reviewer sentiment towards the drugs using NLP techniques. The chosen library/method should be clearly documented within the code 
* **Drug Type Classification:**
  * Implements a Multinomial Naive Bayes (MNB) model to classify drug types based on the reviews 
  * Includes code for testing the model's accuracy using real drug review data 

# Data
You can find and upload dataset from here: https://drive.google.com/drive/folders/1U_bmieGvuoe72KIh_CyTGLcqIrkE01Cr?usp=sharing

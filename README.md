# Text Mining - Simple Sentiment Analysis

Simple sentiment analysis based on IMDB reviews (50k observations, balanced dataset, labels: positive, negative). I trained several most popular classification models to find out how they deal with sentiment analysis. The project covers almost all DS project steps from pre-processing data to re-usage. However, the workflow was simplified and there is lack of proper model evaluation (cross-validation, analysis of learning curve etc.) All mentioned missing steps will be covered in future updates.

Enjoy discovering my project! I hope you will find it usefull and interesting :) 

## Sentiment Analysis - IMDB reviews:

**IDE:** Jupyter Notebook <3

**data** <- IMDB reviews: https://www.kaggle.com/datasets/columbine/imdb-dataset-sentiment-analysis-in-csv-format

**model evaluation:** accuracy metric

**used algorithms:**
- LinearSVC
- Naive Bayes:  BernoulliNB, MultinomialNB
- LogisticRegression
- KNeighborsClassifier

**embedding:**
- TfidfVectorizer


**used libaries:**

machine learning
- sklearn

plotting
- seaborn
- wordcloud 
- matplotlib.pyplot

nltk
- nltk

utilities
- re
- pickle
- numpy 
- pandas
- contractions
- string
- time
- os









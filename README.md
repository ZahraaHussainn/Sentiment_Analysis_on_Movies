# Introduction
This project aims to perform sentiment analysis on movie reviews collected from IMDB. Sentiment analysis involves determining whether a piece of text (in this case, a movie review) is positive, negative, or neutral. We utilize web scraping to collect data, preprocess 
the data, and then apply various machine learning and deep learning models to predict the sentiment of the reviews.

# Data Collection
The data is collected by scraping movie reviews from the IMDB website. The script data_collection.py in the src directory handles the scraping process. This script uses libraries such as BeautifulSoup and requests to extract reviews and their corresponding ratings.

# Data Preprocessing
Once the data is collected, it undergoes preprocessing to prepare it for model training. The preprocessing steps include:
1. Cleaning the text (removing HTML tags, special characters, etc.)
2. Tokenization
3. Stop words removal
4. Lemmatization

# Machine Learning Models
Several machine learning models are implemented to predict the sentiment of the reviews. These include:
1. Logistic Regression
2. Support Vector Machines (SVM)
3. Random Forest
4. Naive Bayes

# Deep Learning Models
For more advanced sentiment analysis, deep learning models such as Recurrent Neural Networks (RNN) and ANN are used. I have libraries such as TensorFlow and Keras for building and training these models.

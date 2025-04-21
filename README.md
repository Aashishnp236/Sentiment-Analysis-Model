# Twitter-Sentiment-Analysis- NLP
Dataset Information
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets.

Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.

For training the models, we provide a labelled dataset of 31,962 tweets. The dataset is provided in the form of a csv file with each line storing a tweet id, its label and the tweet.

Download link: https://datahack.analyticsvidhya.com/contest/practice-problem-twitter-sentiment-analysis/

witter Sentiment Analysis - NLP
Welcome to the Twitter Sentiment Analysis project! This application utilizes Natural Language Processing (NLP) techniques to analyze and classify the sentiment of tweets as positive or negative. It leverages machine learning models to achieve high accuracy and provides insights into the general sentiment trends on Twitter.

Features
Sentiment Classification: Classifies tweets into positive or negative sentiments.

Data Preprocessing: Includes text cleaning, tokenization, and vectorization.

Model Training: Trains a logistic regression model using scikit-learn.

Performance Visualization: Uses graphs and plots to analyze results and model accuracy.

Libraries Used
pandas – For data manipulation and analysis.

matplotlib – For visualizing data and model performance.

seaborn – For enhanced statistical graphics.

scikit-learn – For machine learning algorithms and model evaluation.

Algorithm Used
Logistic Regression: A supervised learning algorithm used for binary classification.

Best Model Accuracy
✅ 95.00% (Achieved using Logistic Regression)

Installation
Make sure you have Python 3 installed. You can download Python from python.org.

Install the required libraries using pip:

bash
Copy
Edit
pip install pandas matplotlib seaborn scikit-learn
How to Run the Project
Clone or download the project repository.

Navigate to the project directory.

Run the main Python script:

bash
Copy
Edit
python sentiment_analysis.py
How It Works
Load and preprocess the tweet dataset.

Vectorize the cleaned text using TF-IDF or CountVectorizer.

Train a Logistic Regression model.

Predict and classify tweet sentiments.

Evaluate model accuracy and visualize the results.

Credits
This project was developed by Mr. Aashish Tharu Gamuwa from Quantum University.
Feel free to fork the repository, suggest improvements, or contribute!

Thank You ✔️

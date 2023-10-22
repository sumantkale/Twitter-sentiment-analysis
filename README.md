# Twitter Sentiment Analysis 
# Overview
This is a Twitter Sentiment Analysis project that aims to analyze and classify the sentiment of tweets using machine learning techniques. In this part, we perform data preprocessing, exploratory data analysis, and build a basic sentiment classification model.

# Contents
Importing Libraries: We start by importing the necessary Python libraries for data analysis, visualization, and machine learning.

Importing Dataset: We load the tweet dataset from a CSV file, which contains tweet text and their corresponding sentiment labels.

Data Preprocessing: We clean and prepare the data for analysis. This includes selecting relevant columns, mapping sentiment labels to numerical values, and handling whitespace.

Data Exploration and Visualization: We explore the dataset's sentiment distribution using histograms and pie charts, helping us understand the data's composition.

Splitting the Dataset: The dataset is split into training and testing sets to train and evaluate our sentiment classification model.

Text Vectorization: We convert text data into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency).

Model Training: We train a logistic regression model on the training data for sentiment classification.

Model Evaluation: We evaluate the model's performance by calculating accuracy, ROC AUC scores, and creating confusion matrices for both training and testing sets.

Binary Sentiment Classification: We narrow down the analysis to binary sentiment classification (positive vs. negative) and retrain the model.

Feature Weights Visualization: We visualize the distribution of feature weights (coefficients) learned by the logistic regression model.

Identifying Positive and Negative Words: We identify and print the most positive and negative words based on their weights in the model.

# Getting Started
Follow these steps to get started with this project:

Clone the Repository: Clone this GitHub repository to your local machine.

Requirements: Ensure you have the required libraries and dependencies installed. You can use the libraries mentioned in the "Importing Libraries" section.

Dataset: You will need a dataset similar to the "Tweets.csv" used in this project. You can replace it with your own dataset or use publicly available Twitter datasets.

Run the Notebook: Execute the Jupyter notebook "twitter-sentiment-analysis.ipynb" to run the analysis and explore the code.

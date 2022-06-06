# Reddit NLP Project


## Introduction

We want to train and deploy online a machine learning model that can predict how well a Reddit post for a given subreddit will be received, based on its title and text. 

We use the Reddit API to pull data. We will use a Docker container for the SQL database that will store the data, the model training service, data ingestion and transformation services, and logging. The final model will be deployed online.


## Completed Work

We succesfully trained an XGBoost model on a set of test data, achieving a root mean square error of 7.97. We use the geometric mean of a posts upvotes and upvote/downvote ratio as the training target.


## Next Steps

1. Create and configure a Docker container
2. Configure SQL database
3. Configure data ingestion
4. Configure model training service
5. Create testing tasks
6. Deploy final model online

## Authentication

Authentication information is ommited from the script, and it is read from the 'auth.txt' file.

## Requirements

We use the following versions of data science libraries

|     |     |
| --- | --- |
numpy | 1.21.6
pandas | 1.3.5
praw | 7.6.0
xgboost | 1.6.1
nltk | 3.2.5
tensorflow | 2.8.2
keras | 2.8.0
keras-Preprocessing | 1.1.2
scikit-learn | 1.0.2

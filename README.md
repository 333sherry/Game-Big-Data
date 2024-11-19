# Game-Big-Data
This is a Collaborative Filtering Recommendation System for Steam Games using PySpark on GCP :)
+ Uploaded an over 40 GB dataset to a GCP bucket via Kaggle’s API
+ Performed EDA and Data Cleaning with PySpark.SQL
+ Built a Logistic Regression model with NLP features (Tokenizer, StopWordsRemover, HashingTF, IDF) on a GCP cluster
+ Achieving 0.86 accuracy and 0.80 F1 score from the model for generating sentiment scores from user reviews
+ Converted sentiment scores into user ratings and developed an ALS Collaborative Filtering model with 0.13 RMSE

I might add a classification model later on, as the entire project is still a work in progress, but the recommendation system part is finished!

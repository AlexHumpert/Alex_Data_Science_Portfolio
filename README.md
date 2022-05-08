# Data Science Portfolio

Portfolio of Data Science Projects - Machine Learning Projects (Python)

## [Project 1: Pyspark - Covid-19 Tweet Fake News Detector, Binary Classification](https://github.com/AlexHumpert/Covid_19_Tweet_Fake_News_Detection)

#### Business Value

Content moderation is a [billion dollar problem](https://www.cnbc.com/2021/02/27/content-moderation-on-social-media.html) for Twitter, Facebook and Youtube. Why? Not having a content moderation strategy can be a death sentence. Look at [Parler](https://techcrunch.com/2021/01/11/parler-is-officially-offline-after-aws-suspension/?guccounter=1&guce_referrer=aHR0cHM6Ly93d3cuZ29vZ2xlLmNvbS8&guce_referrer_sig=AQAAACJxmI540vaq34KI0o7DGQZtrIYducKSxqjTesQ9p8l9-g9puvtoiRDCUJer-7a3qlFUSgX3qlwBZvg4jmYIMUq-lYhH0zPOmz0dNX_C1sFORtvKxjiiwGOG7uYM-OH867GbChyT_RxZoTwSaEPRsvVxb7LEyfVzQomP5MTpAzW6), offering itself as an alternative social media platform with minimal content moderation was suspended from the Apple and Google app stores as well as hosting by AWS. A robust content moderation strategy ensures that online speech does not degenerate into the worst of human communication: hate-speech, disinformation and incitements to violence. 




Classified Covid-19 tweets ingested in real-time using Apache Kafka with hyperparameter tuned Random Forest classifier trained on pre-labeled covid-19 fake news dataset stored in HDFS – achieved 70% accuracy on test set.

Built natural language processing pipeline (tokenizer, count vectorizer and TF-IDF) to transform data in order to extract relevant information from text and prepare correct format for ingestion by classification model.


## [Project 2: Python - Forest Cover Type Prediction Challenge, Multiclass Classification](https://github.com/AlexHumpert/Forest_Cover_Type_Prediction_Competition)

Term 2 group project for Machine Learning 2 class at IE university - part of the Masters in Business Analytics and Big Data program.

Predicted forest cover type through an ensemble model of Random Forest and Extra Trees classifiers trained on expanded feature set with Python – achieved average 79.7% accuracy (89th percentile Kaggle competition ranking).

Applied data-centric approach to improve model accuracy by conducting feature expansion (averaging and summing numerical features) and feature reduction (reverse hot-encoding dummy variables and normalizing numerical features to conduct principal component analysis).

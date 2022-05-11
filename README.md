# Data Science Portfolio

Hi there! My name is Alex, my goal is to deepen my experience in machine learning by learning from experienced and driven individuals who are passionate about the data products they are building. Below are a few of the projects I have worked in the past couple of months for your enjoyment!

I am on a mission to continue to get my hands dirty working on new problems that push my learnings to the next level. Over the coming months my goal is to add a project in the domains of NLP, Social Network Analysis and Deep Learning. 

Any feedback is much appreciated! Feek free to email me @ humpertalex@gmail.com or connect on [linked-in](https://www.linkedin.com/in/alex-humpert/) to talk about Data Science stuff or big problems in the world :) 

## [Project 1: Pyspark - Covid-19 Tweet Fake News Detector, Binary Classification](https://github.com/AlexHumpert/Covid_19_Tweet_Fake_News_Detection)

### Business Value

The bulk of content moderation by Twitter is done by human moderators. According to CNCB, this is a [billion dollar solution](https://www.cnbc.com/2021/02/27/content-moderation-on-social-media.html) for social media platforms like Twitter, Facebook and Youtube. Replacing human moderators with automated processes would therefore present significant cost savings for Twitter. 

One might ask, "if this is such an expensive problem, why not do away with content moderation all together?" There are two issues with this: 

1. The reality is, content shared on social media has real-world implications. This has become evident since the start of the Covid-19 pandemic, with online misinformation about the seriousness of the virus and innacurate information ranging from treatments to  vaccinations being linked to ["early Covid-19 vaccination hesitancy and refusal"](https://www.nature.com/articles/s41598-022-10070-w). This is a reason why the World Health [Organization (WHO) has termed this the "Infodemic"](https://onu.delegfrance.org/IMG/pdf/cross-regional_statement_on_infodemic_final_with_all_endorsements.pdf). Being able to accurately flag misleading information on Covid-19 is therefore vital for public health and countries' strategies to return to a normal state fo affairs.

2. A weak content moderation strategy is a death sentence. Look at Parler, an alternative social media platform offering users an experience with minimal content moderation, was [dropped by Apple, Google app stores and AWS' cloud hosting services](https://edition.cnn.com/2021/01/09/tech/parler-suspended-apple-app-store/index.html) for not abiding with their community guidelines.

The value of a robust Covid-19 Tweet Fake News Detector servers multiple interests: 
  1. Twitter's bottom line
  2. Public health
  3. Countries' strategies to return to a normal state fo affairs

### Implementation Summary

Classified Covid-19 tweets ingested in real-time using Apache Kafka with hyperparameter tuned Random Forest classifier trained on pre-labeled covid-19 fake news dataset stored in HDFS – achieved 70% accuracy on test set.

Built natural language processing pipeline (tokenizer, count vectorizer and TF-IDF) to transform data in order to extract relevant information from text and prepare correct format for ingestion by classification model.


## [Project 2: Python - Forest Cover Type Prediction Challenge, Multiclass Classification](https://github.com/AlexHumpert/Forest_Cover_Type_Prediction_Competition)

Term 2 group project for Machine Learning 2 class at IE university - part of the Masters in Business Analytics and Big Data program.

Predicted forest cover type through an ensemble model of Random Forest and Extra Trees classifiers trained on expanded feature set with Python – achieved average 79.7% accuracy (89th percentile Kaggle competition ranking).

Applied data-centric approach to improve model accuracy by conducting feature expansion (averaging and summing numerical features) and feature reduction (reverse hot-encoding dummy variables and normalizing numerical features to conduct principal component analysis).

## Steve Song's  Capstone Project
=================================

### Project Overview  
With more than 145 million active daily users, Twitter has become
a part of market stratefy for most business owners. It is a gold
mine of customer insights and opportunities to build the band, drive
sales and win fans. The dataset contains tweets on US airlines 
classified as positive,negative and neutral. We will perform sentiment
analysis in this project. 


### Project Organization
After the dataset was imported, we need to do some data pre-processing
or wrangling to remove unnecessary characters. And EDA analysis was 
proformed. 
Then we created a document-term matrixm to encode text data into a 
numeric matrix. Two methods are used: Bag of Words and TF-IDF.

After feature vectorization is completed, we are going to apply 
different machine learning algorithms to build models, logistic 
regression, KNN and decistion tree. 

### Data Dictionary
   tweet_id  int64
   airline_sentiment object
   airline_sentiment_confidence float64
   negativereason object
   negativereason_confidence float64
   airline   object
   airline_sentiment_gold object
   name object
   negativereason_gold object
   retweet_count int64
   text object
   tweet_coord object
   tweet_created object
   tweet_location object
   use_timezone object

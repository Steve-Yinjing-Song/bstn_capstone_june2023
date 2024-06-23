## Sentiment Analysis on Airline Tweets Dataset
===============================================

### Project Overview  
The objective of this project is to apply sentiment analysis, the most common text classification
tool, to analyse an incoming message and tell whether the underlying sentiment is positive, negative
or neutral. The dataset contains tweets on US Airlines of 2015. We applied some data preprocessing 
or wrangling techniques to remove unnecessary characters,symbols and tokens.Different machine learning
algorithms are used to bulild the models, evaluate the performance and make the predictions. Once 
the model is put into implementation, the business owner is able to predict whether the customers'
feedback is positve,negative and neutral. This can help identify potential issues in the process of 
corporate operations and improve customers' satisfaction.  

### Walkthrough Demo

...
...
...

### Project Flowchart

...
...
...

### Project Organization
1. Problem Statement
The airline inductry is a very competitive market.The traditional customer feedback forms are very 
tedious and time consuming. Tweeter data serves as a good source to gather customer feedback.
Through machine learning and text analytics,sentiment analysis is used to determine sentiments such 
as positive,neutral and negative. This help the business monitor social media mentions in a real time
manner and proactively manage negative comments so as to improve customer satisfaction.
2. Data Preprocessing
A couple of techniques are used to prerprocess text data. These include lowercaing, punctuation removal
,stemmings and stop words removal. 
3. Data Vectorization
CountVectorization simply counts the number of occurance in the documents for each tokens. Td-Idf reduces
the weights of those tokens that appear too often in most documents, which makes the document-term matrix 
more meaningful for model building. 
Word Embedding is a more advanced because it not only considers the similarity between words , but also 
reduce the dimension of document-term matrix significantly. This makes the model training process much
more efficient. The pretraind model word2vec LexVec is used to reduce the word dimension to 300.
4. Model Building
First of all, we set the baseline by identifying random guess of around 60%. Then we trid different 
machine learning algorithms including logistic regression, decision tree and random forest. Other 
advanced methods such as Adaboost Classifier and Gradient Boosting have also been tested. Neural network
is good at solving non-linear classfication problems. we built the neural network model based on the 
Lexvec word embedding and achived much better performace in terms of accuracy, precision and recall. 
Traditional neural network suffers from short term memory. To address this issue, recursive neural network 
came into play. It adds one time stamp to train the model word by word sequentially. 
5. Model Evaluation
Accuracy score is usually the main indicator to evaluate the performance of models. However,for imbalanced 
datasets, precision,recall and f1 score are more meaningful. We also applied ROC curve and AUC tools to 
better evaluate the model.

* `data` 
    - contains link to copy of the dataset (stored in a publicly accessible Google Drive folder)
    - saved copy of aggregated / processed data as long as those are not too large (> 10 MB)

* `model`
    - joblib dump of final model / model object

* `notebooks`
    - contains all final notebooks involved in the project

* `reports`
    - contains final report which summarises the project

* `references`
    - contains papers / tutorials used in the project

* `src`
    - Contains the project source code (refactored from the notebooks)

* `.gitignore`
    - Part of Git, includes files and folders to be ignored by Git version control

* `capstine_env.yml`
    - Conda environment specification

* `Makefile`
    - Automation script for the project

* `README.md`
    - Project landing page (this page)

* `LICENSE`
    - Project license

### Dataset

...
...
...

### Credits & References

...
...
...

--------

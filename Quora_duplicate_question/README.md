# Quora Duplicate Question Classification

**Data Sources :** 

1. Quora Question Pairs. [http://www.cs.cornell.edu/people/pabo/movie-review-data/review_polarity.tar.gz
](https://www.kaggle.com/competitions/quora-question-pairs/data)

**quora-duplicate-question-baseline.ipynb** 
1. feature_extraction : BOW and TF-IDF, Purely baseline model without ant text preprocessing
2. Model1 (BOW): Logistic Regression, Accuracy : 69.6 % 
3. Model2 (BOW): Random forest, Accuracy : 73.4 %  
4. Model3 (BOW): XGboost, Accuracy : 72.5 %  
5. Model1 (TF-IDF, max_feature =3000): Logistic Regression, Accuracy : 71.7 % 
6. Model2 (TF-IDF, max_feature =3000): Random forest, Accuracy : 73.4 %  
7. Model3 (TF-IDF, max_feature =3000): XGboost, Accuracy : 71.6 % 


**bow-tfidf-with-preprocessing.ipynb** 

1. In this notebook a little bit text preprocessing has been used ie. decontraction of some words, replaced some punctuations with their word equivalent and lower casing etc.
1. Sklearn implementation of BOW,with logistic regression Accuracy 75 %
2. Sklearn implementation of BOW,with Random forest Accuracy 81.7 %
3. Sklearn implementation of BOW,with XGboost Accuracy 74.7 %
4. Sklearn implementation of TF-IDF,with logistic regression Accuracy 76.1 %
5. Sklearn implementation of TF-IDF,with Random forest Accuracy 81.5 %
6. Sklearn implementation of TF-IDF,with XGboost Accuracy 75.9 %

**tf-idf-preprocessing-random-forest-accuracy-82.ipynb**

1. stop words removed 
2. 81.9 % 

**advanced-feature-engineering-with-tf-idf.ipynb**

1. Created some new features like 

  1. common_word_count
  2. common_stop_word_count
  3. common_token_count
  4. min,max length of document etc.
  
2. Use of fuzzywuzzy to create some additional features
3. Accuracy 83.3% **(BEST)**

word2vec is coming soon with ANN,CNN, RNN and LSTM model.......................

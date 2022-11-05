# IMDB movie review

**Data Sources :** 

1. Movie Review Polarity Dataset (review polarity.tar.gz, 3MB). http://www.cs.cornell.edu/people/pabo/movie-review-data/review_polarity.tar.gz

2. IMDB 50,000 movie review Dataset https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews

**IMDB_movie_review.ipynb** 
1. feature_extraction : TF-IDF from scratch
2. Model1 : Logistic Regression, Accuracy : 80.16 % 
3. Model2 : Neural Network, Accuracy : 85 %  
Needs improvement .....


**IMDB_movie_reviewV2.ipynb** 

0. Here 50,000 movie review dataset has been used
1. Sklearn implementation of BOW,with logistic regression Accuracy 88.25 %
2. Sklearn implementation of BOW,with Random forest Accuracy 85.55 %
3. BOW with 6000- features only, logistic regression (86.56 %) and with random forest (84.46 %) 
4. Bi-gram implementation of BOW, logistic regression (85.40 %) and with random forest (80.65 %)  
5. TF-IDF with Logistic regression is 89.48 %(**Best**)

**IMDB_movie_review_word2vec.ipynb**

1. word2vec model trained on reviews
2. Logistic regression 86.66 %
3. Random forest 83.66 %
4. ANN 86.25
Needs improvement, might increase dimension of the vectors from 100 to 200 or 300, window size can also be increased..............  

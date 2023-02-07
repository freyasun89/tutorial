# Unsupervised-Aspect-Category-Detection
This file contains basic instructions on how to set everything up. 

## Download data and put in the right folder 
* The unlabeld yelp reviews sentences can be downloaded at [https://drive.google.com/file/d/1aCOK59-hWj9qmFT7jsYb4N791Ty9tvNx/view] Put this file in the 'yelp-weak-supervision' folder.
* The pre-trained word embeddings can be downloaded at [https://drive.google.com/file/d/1Uh7TOEqthjbzIUHIOQ2EYH1nLzVhpLrn/view] Put this file in the 'word-embedding' folder.
* Download Restaurants train data from [http://metashare.ilsp.gr:8080/repository/browse/semeval-2014-absa-restaurant-reviews-train-data/479d18c0625011e38685842b2b6a04d72cb57ba6c07743b9879d1a04e72185b8/] and Test data: Phase B from [http://metashare.ilsp.gr:8080/repository/browse/semeval-2014-absa-test-data-phase-b/551605f2b10b11e3a4bd842b2b6a04d7e6c38921a2b9404a940a2f2e96b7b21a/]. And put these two files in the "Dataset" folder.

## Set gensim to certain version 
pip install gensim==3.8.3

## Download stopwords in nltk
python -m nltk.downloader stopwords

## Run main.py



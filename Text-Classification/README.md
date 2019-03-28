Multiclass Text Classification - Keras | LSTM

This repo contains multiclass text classification model using Keras and 
LSTM

Dataset:
News Aggregator Corpora 
Link: https://archive.ics.uci.edu/ml/datasets/News+Aggregator

News are grouped into clusters that represent pages discussing the same 
news story. 
The dataset includes also references to web pages that, at the access 
time, pointed (has a link to) one of the news page in the collection. 

422937 news pages and divided up into: 

152746 news of business category 
108465 news of science and technology category 
115920 news of business category 
45615 news of health category 

2076 clusters of similar news for entertainment category 
1789 clusters of similar news for science and technology category 
2019 clusters of similar news for business category 
1347 clusters of similar news for health category 

References to web pages containing a link to one news included in the 
collection are also included. They are represented as pairs of urls 
corresponding to 2-page browsing sessions. The collection includes 15516 
2-page browsing sessions covering 946 distinct clusters divided up into: 

6091 2-page sessions for business category 
9425 2-page sessions for entertainment category

Model:
LSTM model with 4-units dense layer softmax output 


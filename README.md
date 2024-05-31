# Project Description

Experiment with APIs and clustering.

## Chosen API
https://newsapi.org/  
"Locate articles and breaking news headlines from news sources and blogs across the web with our JSON API"

## Extracted Data
One month of top 100 headlines from BBC news

## Methods Used
Stop words, TF-IDF and pre-trained embeddings, with KMeans clustering

## Results and Conclusions
News topics are significantly skewed due to the overwhelming number of sports-related articles; splitting clustering and analysis into two catgeories (sports and non-sports) was necessary to obtain any usable clustering results.

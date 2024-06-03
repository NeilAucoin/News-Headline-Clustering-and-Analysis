# Project Description

Goal: Experiment with APIs and clustering  
Method: Use natural language processing and clustering to seperate news headlines based on topics covered

## Chosen API
https://newsapi.org/  
"Locate articles and breaking news headlines from news sources and blogs across the web with our JSON API"

## Extracted Data
One month of top 100 daily headlines from BBC news

## Methods Used
Stop words, TF-IDF and pre-trained embeddings, with KMeans clustering

## Results and Conclusions
News topics are significantly skewed due to the overwhelming number of sports-related articles; splitting clustering and analysis into two catgeories (sports and non-sports) was necessary to obtain any usable clustering results.

K-means was likely not the best clustering method for this dataset and further experimenation with clustering methods could have yielded better results.

Non-sports news cluster plots
![News Cluster Plots](https://github.com/NeilAucoin/News-Headline-Clustering-and-Analysis-Using-NLP/blob/main/Assets/news_cluster_plots.PNG?raw=true)

Sports news cluster plots
![Sports Cluster Plots](https://github.com/NeilAucoin/News-Headline-Clustering-and-Analysis-Using-NLP/blob/main/Assets/sports_cluster_plots.PNG?raw=true)

## Example Successful Clusters
Samsung and Apple
![Example Cluster 1](https://github.com/NeilAucoin/News-Headline-Clustering-and-Analysis-Using-NLP/blob/main/Assets/example_cluster1.PNG?raw=true)

Manchester
![Example Cluster 2](https://github.com/NeilAucoin/News-Headline-Clustering-and-Analysis-Using-NLP/blob/main/Assets/example_cluster3.PNG?raw=true)

Nintendo Switch Games
![Example Cluster 3](https://github.com/NeilAucoin/News-Headline-Clustering-and-Analysis-Using-NLP/blob/main/Assets/example_cluster2.PNG?raw=true)

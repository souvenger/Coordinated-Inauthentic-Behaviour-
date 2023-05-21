## Coordinated-Inauthentic-Behaviour-


# US Election 2020 Tweets Network Analysis

This project aims to analyze a dataset of US Election 2020 tweets using natural language processing and network analysis techniques. The dataset contains over 1.72 million tweets collected from October 15th to November 8th, 2020, and has been divided into two parts - one for Biden and another for Trump. The model has been trained on a subset of 100k+ tweets.

## Data Collection

The first step of the analysis was to collect the tweets that we want to analyze. This was done using the Twitter API or web scraping tools.

## Preprocessing and Data Cleaning

After collecting the data, the tweets were preprocessed to prepare them for analysis. This included removing stop words, stemming or lemmatizing words, and removing special characters and URLs.

## Embedding

Once the preprocessing was done, word embeddings were used to represent each tweet as a numerical vector. The TF-IDF algorithm was used, which represents each word as a high-dimensional vector based on its context.

## Similarity Calculation

With each tweet represented as a vector, the similarity between pairs of tweets was calculated using cosine similarity or another distance metric.

## Threshold Selection

Based on the similarity scores, a threshold was defined above which two tweets are considered similar enough to be connected by an edge in the network using DBSCAN algorithm.

## Network Creation

Finally, a network was created where each node represents a tweet and edges represent the similarity between pairs of tweets above the threshold.

## Network Analysis

Network analysis tools such as betweenness, degree, and closeness centrality were used to identify clusters of similar tweets, key influencers, and other properties of the network.

Overall, this project demonstrates how a combination of NLP and network analysis techniques can be used to create a network of similar tweets. It is important to carefully preprocess the data and select appropriate similarity measures and thresholds to ensure that the resulting network accurately represents the similarity between tweets.

## Requirements





This project requires Python 3.x and the following packages:

- Pandas
- Scikit-learn
- NetworkX
- Matplotlib

## Usage

To use this project, clone the repository and run the `US_Election_Tweets_Network_Analysis.ipynb` file in a Jupyter Notebook or any other compatible environment. The dataset can be downloaded from [US Elections 2020 Kaggle](https://www.kaggle.com/datasets/manchunhui/us-election-2020-tweets).

## Credits

The dataset was obtained from [US Elections 2020 Kaggle](https://www.kaggle.com/datasets/manchunhui/us-election-2020-tweets). 

## Working
https://github.com/souvenger/Coordinated-Inauthentic-Behaviour-/assets/74491716/14ae4c6c-f77e-43df-81b6-58997071c6c0

# Results
![image](https://github.com/souvenger/Coordinated-Inauthentic-Behaviour-/assets/74491716/9825539c-3ad5-4cf7-b284-5f8d5a74d036)
![image](https://github.com/souvenger/Coordinated-Inauthentic-Behaviour-/assets/74491716/623e1d44-6168-4fdd-8848-163ef47e502b)
![image](https://github.com/souvenger/Coordinated-Inauthentic-Behaviour-/assets/74491716/84fcde40-9e79-42c3-90fc-f94b210feae7)





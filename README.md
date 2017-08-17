# tech_news_NLP
NLP applied to technology news

This project focuses on using NLP and unsupervised learning to interpret articles from news websites focusing on technology.
Articles were scraped from TechCrunch, ArsTechnica, and Engadget.

An SSH tunnel was used to connect to a remote MongoDB database.

# Files

`scraper.ipynb`: scrapes articles from several tech news websites and stores them in a MongoDB instance

`process_explore.ipynb`: extract the data from MongoDB, preprocess the text and apply 
unsupervised learning (clustering, dimensionality reduction, sentiment analysis)

# Results

K-means clustering with 20 clusters

Clusters could be mapped directly to major companies, industries, or current events in technology.

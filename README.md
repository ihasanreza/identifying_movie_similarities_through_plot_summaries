# Identifying Movie Similarities through Plot Summaries
In this project, we will be using natural language processing (NLP) techniques to analyze movie plot summaries and quantify the similarity between movies. The dataset we will be using contains the titles of the top 100 movies on IMDb as well as each movie's plot summary from both IMDb and Wikipedia.

## Getting Started
To begin, we will import and observe the dataset. Then, we will combine the Wikipedia and IMDb plot summaries into a single column for more efficient analysis.

Next, we will apply tokenization and stemming to the text to build context and reduce the words to their root form. We will then combine these processes into a single function for easier use.

Using the TfidfVectorizer, we will create a matrix of term frequency-inverse document frequency (TF-IDF) values for each movie plot summary. This matrix will allow us to determine the relevance of each word in the plot summaries and how unique it is to each movie.

We will then use the KMeans algorithm to cluster the movies based on their plot summaries. This will allow us to group movies that are similar based on their plot summaries.

Then, we will calculate the similarity distance between the movies in each cluster to further understand the relationships between them.

To visualize the results, we will use Matplotlib and create a dendrogram using the linkage and dendrogram functions. This will allow us to see the hierarchical structure of the clusters and how closely related the movies are to each other.

## Prerequisites
To run this project, you will need to have the following libraries installed:

* pandas
* numpy
* re
* nltk
* sklearn
* matplotlib

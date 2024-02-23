# User Request Clustering
## Overview
This repository contains a Jupyter notebook demonstrating the clustering of user requests using NLP techniques. The primary focus is to categorize user inquiries, typically directed to a chatbot, into distinct clusters for better understanding and analysis. This approach is particularly useful in enhancing the efficiency of customer support systems by identifying common patterns and themes in user communications.

## Project Description
This project uses BERTopic to create a streamlined pipeline for text processing and clustering:

1. **Embedding Extraction**: Utilizes SentenceTransformer to convert text data into meaningful vector representations.
2. **Dimensionality Reduction**: Applies UMAP for reducing the high-dimensional embeddings to a lower-dimensional space.
3. **Clustering**: Uses HDBSCAN to cluster the reduced embeddings into meaningful groups.
4. **Topic Tokenization**: Employs CountVectorizer for tokenizing the processed text data within each cluster.
5. **Topic Representation**: Creates a topic representation using ClassTfidfTransformer.

## Dataset
This dataset includes inquiries from 400 unique users to a chatbot

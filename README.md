## Information Retrieval using VSM and QLM
This project implements an Information Retrieval (IR) system using the Vector Space Model (VSM) and the Query Likelihood Model (QLM). The system processes the Cranfield dataset to index documents and retrieve relevant results for user queries.
### Data Preprocessing: 
- Cleans documents and queries by removing stopwords, punctuation, and applying stemming.
- Represents documents using the Bag-of-Words (BoW) approach.
### Indexing:
- Vector Space Model: Represents documents and queries as vectors in a multi-dimensional space. Uses TF-IDF weighting to rank documents based on cosine similarity.
- Query Likelihood Model: Constructs unigram language models for documents. Applies Maximum Likelihood Estimation (MLE) and smoothing techniques.
### Query Retrieval:
- Retrieves relevant documents based on similarity scores: Cosine similarity (VSM), Log-scaled probabilities (QLM).
### Evaluation:
- Measures system performance using Mean Average Precision (MAP), Precision, Recall, and F1-Score.

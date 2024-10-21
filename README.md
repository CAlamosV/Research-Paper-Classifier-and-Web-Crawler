# Research-Paper-Classifier-and-Web-Crawler

```openreview_webcrawler.ipynb:```
This notebook implements a web crawler to scrape data from OpenReview, an open-access platform for academic paper reviews.
It extracts metadata, such as paper titles, abstracts, authors, and other relevant information for further analysis or classification.

```classify_paper_subfields.ipynb:```
This notebook classifies academic papers into subfields using text clustering. It preprocesses abstracts and keywords, then applies two methods: TF-IDF with KMeans for clustering by word patterns, and SentenceTransformer embeddings with KMeans for clustering by semantic similarity.

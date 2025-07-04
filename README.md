# 🎬 Movie Review Sentiment Analysis

This project focuses on analyzing electronic word-of-mouth (eWOM) movie reviews collected from platforms such as IMDB, Book My Show, and RTMT. The goal is to understand public sentiment and key discussion themes using text analysis, clustering, and entity recognition techniques.

🔍 Project Objective

To develop a data-driven sentiment analysis pipeline that can:

Extract opinions from user-generated content.

Identify key themes, people, and entities discussed.

Visually represent sentiment trends and relationships among terms.

🧠 Methodology

1. Data Collection
Collected genuine and timestamped movie reviews from IMDB, Book My Show, and RTMT.

Reviews included metadata like comments, source, and review date to maintain authenticity.

2. Data Preprocessing & Analysis
📊 Text Analysis
Used Term Frequency (TF) and Bag of Words (BoW) models to extract high-importance terms.

Generated word clouds to highlight the most discussed topics and terms across reviews.

🧠 Named Entity Recognition (NER)
Identified entities such as movie names, actors, directors, etc.

Helped contextualize opinions and trace sentiment back to specific people or films.

🔗 Clustering
Applied hierarchical clustering to discover relationships among frequently mentioned terms.

Uncovered clusters of similar reviews to analyze common patterns and themes.

## 📊 Results & Analysis

### Top Words from Corpus for hit & flop movie

![Picture 1](screenshots/Picture1.png)
![Picture 2](screenshots/Picture2.png)

### Named Entities identified from Corpus for hit & flop movie

![Picture 3](screenshots/Picture3.png)
![Picture 4](screenshots/Picture4.png)

###  Word Cloud for hit movie  & flop movie

![Picture 5](screenshots/Picture5.png)
![Picture 6](screenshots/Picture6.png)

###  Hierarchical clustering of important terms for hit and flop movie

![Picture 7](screenshots/Picture7.png)
![Picture 8](screenshots/Picture8.png)



🛠 Tech Stack
Language: Python

Libraries: NLTK, Scikit-learn, Pandas, Matplotlib, Seaborn

Tools: Excel, Jupyter Notebook

Methods: BoW, TF, Word Clouds, Named Entity Recognition, Hierarchical Clustering

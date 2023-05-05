# DATAH195-project: Leveraging Deep Learning to Model and Analyze Gendered Reddit Questions

A BERTopic Analysis of r/AskMen and r/AskWomen

Abstract: This paper uses deep learning to model the variety of topics represented in the over 400,000 questions that were posted to the Reddit forums r/askmen and r/askwomen from 2010 to 2019. It uses the modular BERTopic algorithm to perform unsupervised topic modeling, with sentence transformer sBERT as the embedding model, UMAP for dimensionality reduction, and HDBSCAN for clustering. We find that BERTopic performs very well in grouping together semantically similar texts but has difficulty in determining topic “priority”. It also performs poorly in automatically merging topics⁠—producing overly large, non-useful clusters. However, BERTopic shows very promising applications in preliminary assessments on whether a subreddit would have enough content to be a good data source for a particular research topic, as well as inspiring new research questions. This framework of leveraging BERTopic to analyze topics can be easily extended to more current data, as well as to other subreddits of potential research interest.

Unfortunately the data files are too large to be uploaded, but the datasets can be found at Cornell Conversational Analysis Toolkit (ConvoKit) and Pushshift.io’s public Google BigQuery database.

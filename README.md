# sentiment-analysis-embedding-study
This repo contains my research for NLP sentiment analysis study, with the focus on the effect of pre-trained embeddings. 

The dataset used is SST-2. There are two models with the same architecture, bi-directional LSTM with attention. The difference is that one model trained from scratch with embeddings randomly initialized, while the other trained with pre-trained embeddings, specifically the glove.6B.100d embeddings. 

There are several csv files that contain different validation and test examples. In particular, subsets with few unknown tokens and subsets with no unknown tokens with respect to the training set. 

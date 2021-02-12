# Topic Modeling on News Articles

**Problem Statement** - Identify major themes/topics across a collection of BBC news articles using topic modeling techniques.

**Data Summary** - The dataset contains a set of news articles for each major segment consisting of business, entertainment, politics, sports and technology. Total of 2225 articles are there in the dataset from the BBC news website corresponding to stories in five topical areas from 2004-2005. Need to create an aggregate dataset of all the news articles and perform topic modeling on the dataset and verify whether these topics correspond to the different tags available or not.

**Aproach** -
1. Merged all the articles to create the dataset with two columns. One column consists of article news and other with corresponding topics.
2. Applied various data preprocessing techniques to clean the data. Used lemmatization along with multiple libraries to remove stopwords. 
3. Created some features such as length, total words and average words of each article to get better insights of data. 
4. Before modeling checked distribution of of each topic using so to compare model output clusters/topics to given topics.
5. Using TF-IDF vectorizer converted bag of words model to sparse matrix which to be used for modeling.
6. Implemented several topic modeling techniques such as Latent Dirichlet Allocation (LDA), Latent Semantic Analysis (LSA) and Non-negative Matrix Factorization (NMF).
7. Checked model performance by visualizing model output clusters/topics using tools such as pyLDAvis, t-SNE Clustering and wordcloud. 
8. Assigned respective clusters to topics as given initially (business, entertainment, politics, sports, technology), according to words it consists of. 

**Conclusion** - Non-negative Matrix Factorization (NMF) showed best performance to properly segregate the articles into given 5 topics.

**Challenges** - 
1. Due to large number of text files, data importing and some data cleansing tasks took longer time to excecute.
2. Limited visualization techniques restricted evaluation of slightly mixed topics.

**Scope of Future Work** -
1. Using LDA through Genism library or other topic modeling techniques.
2. Implementing neural network with word2vec. 

[Link for the project presentation](https://docs.google.com/presentation/d/1HovJlwruNkk9EuQrrAWPEBI4VrugZv2eqzjIAkk3LPU/edit?usp=sharing)

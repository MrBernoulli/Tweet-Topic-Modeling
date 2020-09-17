# Tweet-Topic-Modeling-Using-LDA

In this unsupervised learning project, we utilize latent Dirichlet allocation (LDA) to model likely topics for a given tweet.

We read tweets from Twitter using the Tweepy python API, then carry out the necessary preprocessings such as punctuation removal, tokenization, stemming, and lemmatization.

We then proceed to use the powerful Gensim library to carry out the LDA; under both Bag-of-words and TF-IDF tweet representations, and while varying the key hyperparamter in LDA - the number of topics.

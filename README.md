# Explorations in Topic Modeling
## Models to Explore 
- [ ] LSA
- [ ] LDA
- [ ] lda2vec


## Topic Modeling Overview
- A `document` is a mixture of `topics`.
- A `topic` consists of a collection of `words`

Given a document is about a particular topic, one would expect words to appear in the document more or less frequently. Suppose, a document is 90% about cats and 10% about dogs. It is makes sense to expect the document to contain 9 times more cat words than dog words. 

A topic model should capture this initution in a mathematical framework by examining a set of documents and
discovering, based on the statistics of the words in each, what the topics might be and what each document's balance of
topics is.

## Latent Dirichlet Allocation (LDA)
LDA is a generative statistical model that allows sets of observations to be explained by unobserved groups that
explain why some parts of the data are similair. So if in our case, the observations are words collected
into documents. LDA's claim would be that each document is a mixture of a small number of topics and that each
word's presence is attributable to one of the documents topics.



## Relevant Links and Resources
https://medium.com/nanonets/topic-modeling-with-lsa-psla-lda-and-lda2vec-555ff65b0b05
https://en.wikipedia.org/wiki/Topic_model

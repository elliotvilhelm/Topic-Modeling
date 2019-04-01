# Explorations in Topic Modeling
```
 "A word is characterized by the company it keeps." - John Rupert Firth
```
## Models Explored
- [ ] LSA
- [ ] LDA
- [ ] lda2vec


## Topic Modeling Overview
- A `document` is a mixture of `topics`.
- A `topic` consists of a collection of `words`

### Intuition
Given a document is about a particular topic, one would expect words to appear in the document more or less frequently. Suppose, a document is 90% about cats and 10% about dogs. It is makes sense to expect the document to contain 9 times more cat words than dog words.

A topic model should capture this initution in a mathematical framework by examining a set of documents and
discovering, based on the statistics of the words in each, what the topics might be and what each document's balance of topics is.



## Latent Semantic Analysis (LSA)
Latent semantic analysis (LSA) is a technique in natural language processing, in particular
distributional semantics, of analyzing relationships between a set of documents and the
terms they contain by producing a set of concepts related to the documents and terms.

LSA assumes `distributional hypothesis`, which claims that words which are used and occur in the same contexts tend to have similair meanings.



## Latent Dirichlet Allocation (LDA)
LDA is a generative statistical model that allows sets of observations to be explained by unobserved groups.

In application `observations` represent `words` from documents. The unobserved `groups` are `topics` which explain the relationships between sets of `observations`, explain why some parts of the data are similair.

LDA's claim is that each document is a mixture of a small number of topics and that each word's presence is attributable to one of the documents topics.





## Relevant Links and Resources
http://langvillea.people.cofc.edu/DISSECTION-LAB/Emmie%27sLSI-SVDModule/p4module.html
https://multithreaded.stitchfix.com/blog/2016/05/27/lda2vec
http://lsa.colorado.edu/papers/dp1.LSAintro.pdf
https://medium.com/nanonets/topic-modeling-with-lsa-psla-lda-and-lda2vec-555ff65b0b05
https://en.wikipedia.org/wiki/Topic_model
https://en.wikipedia.org/wiki/Distributional_semantics

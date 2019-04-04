# intro-bayes-text-classification
Introduction to some libraries and techniques for Bayesian Text Classification in R.

In this R Markdown file we walk through some of the basic steps of text classification in R: dataset preparation, corpus creation, wordclouds, word filtering and model fitting and prediction.

The model used is Naive Bayes (for simplicity) and the useful R functions tm::DocumentTermMatrix and caret::createDataPartition are introduced.

R version 3.5.

Packages: 
 + tm v 0.7-5
 + quanteda v 1.3.4
 + dplyr v 0.7.6
 + caret v 6.0-80
 + e1071 v 1.7-0
 + wordcloud v 2.5

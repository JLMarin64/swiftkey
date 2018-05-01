Capstone Presentation
author: Jonathan Marin
date:   11/20/2017
autosize: true

========================================================
# Data Science Capstone Project

## Building a Word Predictor

by: Jonathan Marin

========================================================


Introduction
========================================================

The final data science capstone project is to build a predictive word model after receiving input from the user.  The user can enter any length string as the input and the model will look at the word or words entered to predict the next word.

Data
========================================================

 - The data was downloaded and sampled from blogs, twitter, and news sources. These sources were then merged into one corpus.
 - The data then was combed over to remove punctuation, unneccesary white spaces, remove numbers, plain test, stop words, stem words, and was coverted to lowercase.
 - N-grams then was created for 2 words, 3 words, and 4 words (Bigram, Trigram, Quadram)
 - The N-grams are then counted and sorted by frequency
 - These N-gram tables are then saved as .RData files to use within the shiny app
 


Model Method 
========================================================
The model used is based off of the Katz Back-off algorithm.  Katz back-off is a generative n-gram language model that estimates the conditional probability of a word given its history in the n-gram. It accomplishes this estimation by "backing-off" to models with smaller histories under certain conditions. By doing so, the model with the most reliable information about a given history is used to provide the better results.

The model was introduced in 1987 by Slava M. Katz. Prior to that, n-gram language models were constructed by training individual models for different n-gram orders using maximum likelihood estimation and then interpolating them together.

Source: https://en.wikipedia.org/wiki/Katz%27s_back-off_model

========================================================



Shiny App 
========================================================

![](app.jpg)

========================================================


# Description

This project aims to build collaborative filters with applications in movie recommendation systems. More specifically, we will build a systems that predict how a particular will rate a move in a scale from 0 to 5. The higher the rating the more likely that user will like the movie, and we will make recommendation based on these predictions.

# Approach
We will use a popular method for recommendation system: collaborative filering.

By [definition](https://en.wikipedia.org/wiki/Collaborative_filtering):

**Collaborative filtering is a method of making automatic predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating)**

# Learning objectives
We will get to understand collaborative filers and construct several models: a linear filter and a simple neural network.

Through this project, we also get to understand the idea of *embedding* that appears frequently in NLP context. This idea is very important as it enables us continue exploring *word embedding* in various deep learning problems for NLP. Lastly, as we will have multiple inputs (users and movies), we will explore Keras's functional API which allows us to merge multiple inputs easier than Sequential API.

# Detail notebook
Complete project with detailed explaination and work examples can be found [here](https://github.com/tnaduc/Collaborative_filtering/blob/master/Collaborative%20filter%20for%20movie%20recommendation.ipynb).

# Sources

Collaborative filter is covered in Prof. Andrew Ng's famous [course](https://www.coursera.org/learn/machine-learning) on machine learning.

Jerremy Howard also covered briefly in his fantastic Deep Learning [course](http://course.fast.ai) and, in fact, most of the insights from this project are learned, adapted, and inspired from Jerremy's lessons.

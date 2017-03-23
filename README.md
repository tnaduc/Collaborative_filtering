# Description

This project aims to build collaborative filters with applications in movie recommendation systems. Specifically, we will build a system that predicts how a particular user will rate a move in a scale of 0 to 5. The higher the rating, the more likely that user will like the movie, and we will make recommendations based on these predictions.

# Approach
We will use a popular method for recommendation systems: collaborative filering.

By [definition](https://en.wikipedia.org/wiki/Collaborative_filtering):

**Collaborative filtering is a method of making automatic predictions (filtering) about the interests of a user by collecting preferences or taste information from many users (collaborating)**

# Data

We use movielens [datasets](http://files.grouplens.org/datasets/movielens/ml-20m.zip). In particular, we will use a small [100000 dataset ](http://files.grouplens.org/datasets/movielens/ml-latest-small.zip) for quick protyping and experimenting.

# Tools

- Python 2.7 with Pandas, Numpy, Theano/Tensorflow, Keras, sklearn, matplotlib

- AWS: EC2 t2.xlarge instance (I found no difference when using p2.xlarge for this project)


# Learning objectives
We will get to understand collaborative filters and construct several models: a linear filter and a simple neural network.

Through this project, we also get to understand the idea of *embedding* that appears frequently in natural language processing context. This idea is very important as it enables us continue exploring *word embedding* in various deep learning problems for NLP. Lastly, as we will have multiple inputs (users and movies), we will explore Keras's functional API which allows us to merge multiple inputs to model much easier than Sequential API.

# Detail notebook
Complete project with detailed explaination and work examples can be found [here](https://github.com/tnaduc/Collaborative_filtering/blob/master/Collaborative%20filter%20for%20movie%20recommendation.ipynb).

# Sources

Collaborative filter is covered in Prof. Andrew Ng's famous [course](https://www.coursera.org/learn/machine-learning) on machine learning.

Jerremy Howard also covered briefly in his fantastic Deep Learning [course](http://course.fast.ai) and, in fact, most of the insights from this project are learned, adapted, and inspired from Jerremy's lessons.

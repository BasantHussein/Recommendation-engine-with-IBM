# Data Scientist Nanodegree
# Recommendation-engine-with-IBM

### Introduction
This project analyze the interactions that users have with articles on the IBM Watson Studio platform, and will help to make recommendations to the users about new articles they will like.

### Project Overview & Steps:

I. Exploratory Data Analysis

II. Rank Based Recommendations

 find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. 

IV. Content Based Recommendations

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. 

V. Matrix Factorization

Finally, a machine learning approach to building recommendations. Using the user-item interactions, build out a matrix decomposition. Using decomposition.

### Install

This project requires **Python 3.x** and the following Python libraries installed:

- [NumPy]
- [Pandas]
- [matplotlib]
- [NLTK]

i recommend you to install [Anaconda]

### Code

Template code is provided in the `Recommendations_with_IBM.ipynb`

### Run

```bash
ipython notebook Recommendations_with_IBM.ipynb
```  
or
```bash
jupyter notebook Recommendations_with_IBM.ipynb
```

This will open the iPython Notebook software and project file in your browser.




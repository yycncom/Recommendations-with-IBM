# Introduction
  For this project analyzing the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they will like. 

project will be divided into the following tasks

   - I. Exploratory Data Analysis

  Before making recommendations of any kind, explore the data for the project. There are some basic, required questions to be answered about the data throughout the rest of the notebook. 

   - II. Rank Based Recommendations

To get started in building recommendations, first finding the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

   - III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

   - IV. Content Based Recommendations (EXTRA )

Given the amount of content available for each article, there are a number of different ways in which someone might choose to implement a content based recommendations system. Using your NLP skills, you might come up with some extremely creative ways to develop a content based recommendation system. You are encouraged to complete a content based recommendation system, but not required to do so to complete this project.

   - V. Matrix Factorization

Finally, complete a machine learning approach to building recommendations. Using the user-item interactions, build out a matrix decomposition. Using decomposition, get an idea of how well it can predict new articles an individual might interact with (spoiler alert - it isn't great). Finally discuss which methods might use moving forward, and testing how well recommendations are working for engaging users.

# IBM Recommendation

## Project Motivation
This project is analysing data of users and their interactions with artciles on the IBM Watson Studio platform. It aims to make recommendations to users about new articles that they will like.

## Content

1. This notebook begins with Exploratory Data Analysis to insights from the desriptive statistics of the data.
2. Rank-based recommendation to recommend the users based on the popularity (in this case, interaction) rank of the articles.
3. User-user based collaborative filtering
    - Create recommendation based on the articles that other similar users liked. The similar users (neighbors) are determined by creating a similarity vector as a result of the dot product of the user-item matrix and sorting the neighbors based on the dot product value.
    - The articles that are interacted with the most by the closest neighbor, and yet not seen by the user, will then be recommended.
4. Matrix Factorization to build recommendations for the user.

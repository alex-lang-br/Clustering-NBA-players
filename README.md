# Clustering NBA players to get a better marketing campaign

## 1- About this project

### 1-a Motivation:

#### Suppose you're a big sportswear company, like Nike or Adidas. Your goal is to sell products, and to target and segment your audience so that you can sell more products. A good way of doing that is to use some marketing, like sponsoring NBA players and make them wear your products, so that people would want to buy what those athletes are wearing. But exactly, how do you select those players ? Should you target the best players, and if so how do you measure the quality of a player ? Do you favor more his or her raw capabilities, or the number of points he or she scored, etc...

### 1-b Goal of this project:

#### Throughout this notebook, we'll see how we can leverage unsupervised ML techniques to cluster NBA players based on their statistics, like the number of games played, points scored, etc... Then, the marketing department will be able to use these clusters to better target their audience and reach more customers by using the top players as their vector of marketing

### 1-c About our data:

#### This dataset comes from Kaggle (https://www.kaggle.com/datasets/justinas/nba-players-data) and contains data from 1996-2021. It contains roughly 12000 rows and 22 features (~2mb), which should be useful to create a robust model. Features includes everything from the name of the player and their physical description (height, age, weight), the seasons they played as well as their draft number and performance metrics.

### 1-d Outline of this notebook

#### First, we will read the data and perform some basic EDA on it. Then, we'll visualize our data and do some feature engineering. Finally, we'll build our model and conclude by talking about what went wrong and what we learned throughout this process.

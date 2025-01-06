Code for the  **<a href="https://www.kaggle.com/competitions/nfl-big-data-bowl-2025/">NFL Big Data Bowl 2025</a>** submission **<a href="https://www.kaggle.com/code/romanbukreev/clustering-pre-snap-movements-and-predicting-route">Clustering Pre-snap Movements and Predicting Routes</a>**

# Intro

**Pre-snap movements** in football are utilized by offense team to confuse the opponent and reveal their defensive strategies. However, the potential of the insights that defense team can get from the pre-snap movements of the opponent is still underestimated. These movements can reveal some attacking patterns, and help the defense be more prepared for them. This project, in particular, is focused on predicting the running routes of the players that perform pre-snap motion based on their movement trajectory.

The main tool used to implement this project is **clustering of pre-snap motions**. There are thousands of pre-snap motions in our dataset, and since the idea of the project is to make a prediction based on the motion of the opponent, we need to be able to differentiate these motions from each other. That's why we will perform clustering to sparate all the movements into catefories. Then we will look at the distribution of routes ran within each cluster to get the insights about them.

The reasons why route ran was chosen as the offensive behaviour to predict are not really unique for this metric only. This just seems as somrthing that can benefit defensive team in preparing for games and provide some useful insights about the offense. But the main part of the project is movements clustering. After we split them into categories, we will be able to look at different metrics within cluster and make some predictions. So you can think of route ran just as of simple example to illustrate our approach.

# Code

All the code is available in the 'code' folder. All the daataset are in the 'data' subfolder inside 'code'. All the data was taken from the Kaggle **<a href="https://www.kaggle.com/competitions/nfl-big-data-bowl-2025/">NFL Big Data Bowl 2025</a>** 

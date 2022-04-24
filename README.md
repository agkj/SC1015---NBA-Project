# SC1015 Group 8 SC17
-----------------------------
# Team members:

| Contributor                                            | Contributions                                                   
| ------------------------------------------------------|:---------------------------------------------------------------:|
| Aloysius Tay Zen (U2121353L) @Aloyloyloyloy https://github.com/Aloyloyloyloy          | Machine Learning + EDA + Data Cleaning                          |
| Goh Kai Jun, Alger (U2122842K) https://github.com/agkj                  | EDA + Data Cleaning + Github Implementation                    
| Ang Arthur Ace  (U2121103E) @ScatteredThunderstorms https://github.com/ScatteredThunderstorms  | Narration + Script + Tableau                                             | 

-----------------------------

# Link to presentation slides and video: 

https://drive.google.com/drive/folders/1NJ91A9LBOsEel-DAJx8rY5OriZ4UszYe?usp=sharing

-----------------------------

# Title: Analyzing the NBA dataset

This project aims to identify outstanding and mediocre players through analyzing their NBA statistics from 1996 to 2019. 

Data is taken from: https://www.kaggle.com/datasets/justinas/nba-players-data

-----------------------------

# Problem Definition:
What makes an NBA player good?
1. What statistic did we consider to determine how good a player is and how do other factors affect it?
2. Can we predict if a player is from draft round 1 or not using that statistic?
![image](https://user-images.githubusercontent.com/39144132/164891284-d47b3686-e549-44d2-af38-b7add91546f3.png)



-----------------------------

# Models Used:
1. Linear Regression
2. Decision Trees, goodness of fit model
3. Learning something new: Tableu to generate new data visualisation (World Map Visualisation, timeline model)

-----------------------------
# Data filtering

As our dataset has repeated players across each season and also players who played too little games which will affect the desired output of our predictions, we will
be filtering out players who have played less than 70% of the games played in each season.

By doing so, it will reduce the skewness and increase accuracy of our desired output, which is to determine the best and mediocre players in the NBA.

![image](https://user-images.githubusercontent.com/39144132/164891171-e5323d34-1b65-489c-a7b6-fdac6525ff38.png)

-----------------------------
# EDA
Identifying other variables that affects the number of points a player scores per game during his career in the NBA
1. Age
2. Games Played
3. Usage rate
4. Net rating

All these variables are factors that affects a player's points throughout his career, we will be using this variables against "points" to determine whether it affects the player's performance in the NBA.

-----------------------------
# Machine Learning




-----------------------------

# Conclusion:
1. Not all the players in the dataset can be considered as they might have played in very little games during their respective seasons
2. As years go by, players are scoring more and more points - Could be due to the shift in focus more to the offensive side of Basketball
3. Usage rate is the statistic that affects points a player scores per game the most
4. The decision tree is able to accurately predict if a good player is from draft round 1 or not
5. However, it did not perform so well when it came to predicting the worst players
![Alt Text](https://media.giphy.com/media/3o7aTnQqygA3TcukFi/giphy.gif)
-----------------------------

# Learning something new using tableau:

Learning something new:
We generated a world map visualusation of where players originated from and also a timeline model of how much points a player scored throughout his career from 1996 to 2019
https://public.tableau.com/app/profile/ace4658/viz/NBADSAI/Story1?publish=yes




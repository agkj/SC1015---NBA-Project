# SC1015 Group 8 SC17
-----------------------------
# Team members:

| Contributor                                            | Contributions                                                   
| ------------------------------------------------------|:---------------------------------------------------------------:|
| Aloysius Tay Zen (U2121353L)https://github.com/Aloyloyloyloy          | Machine Learning + EDA + Data Cleaning |
| Goh Kai Jun, Alger (U2122842K)https://github.com/agkj                  | EDA + Data Cleaning + Github Implementation                    
| Ang Arthur Ace  (U2121103E)https://github.com/ScatteredThunderstorms  | Narration + Script + Tableau                                             | 

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

As our dataset has players who played too little games, affecting the desired output of our predictions. 
Hence, we will be filtering out players who have played in less than 70% of the games played in each season.

By doing so, it will reduce the skewness and increase accuracy of our desired output, allowing us to determine the best and mediocre players in the NBA reliably.

![image](https://user-images.githubusercontent.com/39144132/164891171-e5323d34-1b65-489c-a7b6-fdac6525ff38.png)

-----------------------------
# EDA
Although points is the main factor that determines a player's performance, we will also be comparing it against other variables such as a players:

1. Age (As a person gets older, will he start to score lesser points?)
2. Games Played (Will high number of games played during a season means a player will score more points per game?)
3. Usage rate (As usage rate and games played are not synonymous, will a high usage rate result in a player scoring more points per game?)
4. Net rating (Will a player's presence affect the team's winning chances?)

By understanding how these variables have any effect on a players points per game, we will be able to make better judgement and predict whether a player will be in the first draft round pick or not.

-----------------------------
# Machine Learning
## Plotting out the decision tree 

![image](https://user-images.githubusercontent.com/66772395/164964931-a43c0811-7952-43a3-8068-742115f07808.png)

## Goodness of fit of the model and Confusion Matrix

![image](https://user-images.githubusercontent.com/66772395/164965518-4fc63299-e989-41f2-9782-919a5787cccb.png)

We were able to get similar classification accuracy for both the train and the test dataset.

## Predictions for the best players

![image](https://user-images.githubusercontent.com/66772395/164965144-3adeb6a1-3ae0-482e-9f19-8ba61a900d5d.png)

The trained model was able to accurately predict the draft rounds for all the top players throughout the dataset. 

## Predictions for the worst players


![image](https://user-images.githubusercontent.com/66772395/164965198-a6450202-e4d5-455a-878f-55b5c99fe6c1.png)

However for the worst players, it did not do as well but still managed to maintain an accuracy of about 65%.

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

![image](https://user-images.githubusercontent.com/39144132/164955881-2e5d9643-d1b5-4eb6-b3eb-3a89b4f7fc4d.png)

![image](https://user-images.githubusercontent.com/39144132/164955929-030c3c02-8db6-42ce-a385-82e97743bba6.png)

A majority of the players however are still from North America, but it seems that it is slowly starting to reach out to players of lesser known countries.


![image](https://user-images.githubusercontent.com/39144132/164955895-f7173949-56b8-4d2d-96c3-a69e7bef13c8.png)

This visualisation depicts a players performance across the starting season of our data 1996 to 2019.



https://public.tableau.com/app/profile/ace4658/viz/NBADSAI/Story1?publish=yes




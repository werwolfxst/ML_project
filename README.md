# ML_project
Prediction of value and overall ability of football players

Soccer is one of the most popular sports around the world. Soccer players are paid more money than most of the players in other sport events. According to the data in 2017, the average wage of the 500 most paid soccer players is 109K pound per week, and the number of the 100 most paid soccer players is 208K pound per week. So is there a way of finding # what the relationship is between the player's personal ability and his corresponding value? How do we define the overall abilities of each player? What about a player's preferred position? Our project use Lasso regression, multilinear regression and decision tree to solve these kind of problems.

This project focuses on 2 aspects. A dataset of the overall statistics of many players is used and it is downloaded from 'https://www.kaggle.com/thec03u5/fifa-18-demo-player-dataset/data'. We modefied this dataset a little bit in order to better fit different cases.

The first target of this project is to make the prediction of the player’s actual value to give the managers a criterion of whether a transfer is worthy or not. The prediction is divided into 2 minor parts. The first step is making the prediction of the overall ability based on some vital indicator such as ‘acceleration’, ‘ball control’, ‘heading accuracy’ and so on. The second step is making the prediction of the value based on the overall ability.

The second target is to make the prediction of the player’s favorite position. The dataset has recorded the performance of each player in each different positions of the field. Usually one soccer player should be put in the position which he has the highest performance score, while this is not always the case, since there is correlation between several positions and one can perform better in another position.

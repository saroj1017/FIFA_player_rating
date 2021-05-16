The dataset on which the Exploaitairy Data Analysis is done is SOFIFA based FIFA rating of players in the year 2018.
The source of which is available in kaggle and can be downloaded  from the below URL:
https://www.kaggle.com/karangadiya/fifa19 and was crawled from https://sofifa.com

Ther are lots of attributes capturted on the dataset , starting from name, nation_team , football_club , to positional play of each player

So the intention was here to find the or predict the overall value of a player i.e the FIFA rating of a player based on attributes like pace, dribbling , shooting , skill_moves ,defesive strength , passing _strength etc. 

First the complete dataset was wrangled , cleaned to work on it , upon which the data analysis was done on specific attributes of the player which may impact the player overall value.

Here we have used two algorithm to predict the raitng those are :
* Linear Regression
* XGBoost 

After the model is trained we could observe a accouracy score of around 95% , so we could observe that the model is very well able to precict the rating of a player.

**For Example** :<br>
In the below box plot , i have analysed the working of the two algorithmns Xgboost and Linear_regression and mesaure the aaccourancy to which it predicts the actual player rating and based on the plot we will be able to conclude that XGboost gives a better in this case of prediction.

<img src='images/algorithmns.png' width = 700>


How to Run 
* You can view all the plots and analysis on the below iplython notebook
https://github.com/saroj1017/FIFA_player_rating/blob/main/FIFA_player_rating(xgboost_vs_linear_regression.ipynb




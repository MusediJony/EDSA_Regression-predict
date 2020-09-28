# EDSA_Regression-predict

## This Repository is one created for the Regression project by Explore Data Science Academy.

### The project was conducted on Zindi, https://zindi.africa/, an online platform that hosts competitions. 

Zindi connects professional organisations around the world with a thriving African Data Science community to use machine learning and AI to solve challanges that can help those organisation make professional decisions.

The competition instructs the competitor to predict the time it will take riders to deliver orders for a logistics company called Sendy, by building a machine learning model. 

###### https://zindi.africa/hackathons/edsa-sendy-logistics-challenge

The metric that was used for this this competition is the Root Mean Squared error (RMSE) with a passmark in relation to your RMSE being below 800 (0% achieved if score is above 800, 50% achieved at 799 and 100% achieved for a RMSE of 730 and below). 

I personally obtained an RMSE score of 750 with a position rank of 40 out of 275 individuals/groups that participated in the competion.

The latter link above takes you to the actual competition. You can then click on the leaderboard and see my profile at position 40.

A recorded presentation of the report was also conducted, and submitted and a final mark of 94% was obtained (Evaluated by EDSA).

The report features the general procedure of intro, body and conclusion about the predict/competition, along with the necessary and/or general procedure to conduct a Regression applied project. 

I had built 4 different regression models: Linear, Regression, Lasso and Random forest. 

I chose Random forest as the best performing model due it it giving me the lowesr RMSE score out of all four. Do note however, for that to be achieved, I had to perform hyperparameter tuning, or else it would be the worst performing model.

It's also wise to mentioned that the RMSE score obtained on the report is different to that of the RMSE score obtained on Zindy. This is due to the fact that on the report, cross validation was needed to be conducted on the whole train data set as a guide for our predicted values . 

The predicted values were then submitted to Zindy as a csv file to be compared to the y_test (ground truth) to then obtain our final RMSE score on Zindy.




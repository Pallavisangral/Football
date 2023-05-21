# Football
#Report

Question 1
In first part, EDA is done and Data visualization is also performed.
1. check if there is any null value
2. convert a column containing percentage into floating number.
3. check unique values of players.
4. find information about the datatypes
5. find the summary of data by using describe()
6. find correlation

Data visualization:
1. find number of players in each club and it is observed that maximum number of players are in Arsenal club.
2. find number of players in each club with respect to their position.
3. find Maximum number of players lying in which age using distribution plot.
   it is observed that  Maximum number of players lies in range between 24 to 30
4. find the market value of each club using swarm plot 
   it is observed that maximum market value is chelsea and manchester+united
5. pairplot of data
5. find the top 10 players of league according to market value
   top player is Eden Hazard
6. find the top 10 most viewed players of league 
   top player is Alexis Sanchez
7. average market value of each club 
   manchester+city has highest market value
8. Nationality of players
   maximums players are from england
9. Average fpl points of each club
   maximum fpl points - Chelsea
10. find correlativity using heatmap
11. boxplot for market values with respect to position.

Question 2
1. Linear Regression
   best score:-4.0937
   accuracy: 0.713
   RSME:6.28
   R2 score:0.71

   Lasso
   best score:-4.101
   accuracy: 0.72
   RSME:6.27
   R2 score:0.72

   Ridge
   best score:-4.08
   accuracy: 0.71
   RSME:6.33
   R2 score:0.715

   K nearest regressor
   best score:0.61
   accuracy: 0.541
   RSME:8.22
   R2 score:0.52

   Support vector regressor
   best score:-6.306
   accuracy: 0.27
   RSME:8.8
   R2 score:0.44

   Decision tree regressor 
   best score: -4.78
   accuracy: 0.75
   RSME:6.006
   R2 score:0.743
  
   Random forest regressor
   best score:0.78
   accuracy: 0.80
   RSME:3.45
   R2 score:0.788

   Gradient boost regressor
   best score:-3.47
   accuracy: 
   RSME:5.47
   R2 score:0.78
   
   Question 3
   By hypertuning the above models, it is observed that From all the above models we can observe that the SUPPORT VECTOR REGRESSION, reports us the best results as the R2 value of the SVR is lowest among all other regressions. The Best Score of SVR is -6.099489733412793, Best Hyperparameters: {'gamma': 0.0001, 'kernel': 'rbf', 'max_iter': 100}, Accuracy: 0.2185178234939857, MSE score: 10.47592874913882 and R2 score: 0.39691213061159725


   
   

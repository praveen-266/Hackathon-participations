     
# Football player rating prediction       
                   
## Problem Statement:        
A regression problem is proposed on a set of football scouting data, in which a series of variables are studied by different scout to evaluate the performance of a given player in a match            

The targte variable studied is an overall score from 0 to 10 of the player's performance in a match. We are provided with two sets of data,  a training data set, labelled for training, and test data set, to evaluate the performance of the resulting model.            
## evaluation metric:       
R2_score

# Approach:     
tried different models like lightgbm,randomforest,xgboost,adaboost.Finally ensemble of lightgbm gave better prediction based on the KFold validation    

**Featuere Selection:**              
Tried different approach to select important features.     
    1.Removed features having more than 70% nan values    
    2.removed duplicate and constant features   
    3.removed features using Quasi-constant method     
    
**Feature Transformation:**           
      1. encoded features using lambda function   
      2.and,made "winner" feature as dummies
 **Feature Importance:**          
 ![image](https://user-images.githubusercontent.com/71770999/176739875-f8c98b82-6faf-4b00-83cf-99f34539937d.png)

## LeaderBoard:            
   public LB : 120 / 4695             
   private LB : 143 / 4695

https://datahack.analyticsvidhya.com/contest/football-hackathon/#LeaderBoard


# This Hackathon is coducted by Analytics vidhya community     
## Title: Football player rating prediction       
          

Approach:     
tried different models like lightgbm,randomforest,xgboost,adaboost.Finally ensemble of lightgbm gave better prediction based on the KFold validation    

### Featuere Selection:        
Tried different approach to select important features.     
    1.Removed features having more than 70% nan values    
    2.removed duplicate and constant features   
    3.removed features using Quasi-constant method     
    
### Feature Transformation:        
      1. encoded features using lambda function   
      2.and,made "winner" feature as dummies
 ### Feature Importance:     
 ![image](https://user-images.githubusercontent.com/71770999/176739875-f8c98b82-6faf-4b00-83cf-99f34539937d.png)


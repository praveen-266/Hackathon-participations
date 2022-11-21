# Analytics Vidhya - Loan Default Hackathon         
          
# Problem Statement               
The objective is to build a machine learning model to predict whether an applicant will default on the loan or not in the future           
  
# Dataset       
The train and test set contains the different attributes related to demographic and loan information of the applicants as age, profession, no.of active loans, and default in previous loans. The training set contains the target variable loan_default.         

| Variable    | Description |    
|------  | --------------|
|loan_id| Unique identifier of a loan|       
| age | Age of the applicant|     
| Education| Applicant Education|        
| proof_submitted| Type of proof submitted|
| loan_amount | Loan amount distributed|  
| asset_cost| The total assest value of the applicant|
| no_of_loans| No.of loans taken by the applicant|      
| no_of_curr_loans| No.of active loans held by the applicant|   
| last_delinq_none|  The loan default in at least one of the past loans|           
| loan_default(Target Variable)| 0/1 indicating if an applicant will defaultt the loan or not|             


# Approach     
Tried different models like lightgbm, catboost, randomforest, extrtree, ada boost, svc, etc. Finally ensemble of lightgbm model gave me better classififcation based on CV validation           

## Exploratory Data Analysis        
statistical data analysis performed on data to find if any outlier or missing data are present       
* Education column has null values           

## Feature transformation       
* one hot encoded     
      proof_submitted varaible         

## Feature selection      
Tried lightgbm(plot_importance)  attribute to select importannt features           
**important features:**       
Top 7 features that turned out to be important are:      
 1. Loan_amount     
 2. No.of loans  
 3. No.of curr_loan      
 4. age       
 5. assest_cost        
 6. education        
 7. proof_submitted_Driving           
        
## LeaderBoard :        
public LB : 17/1356   
private LB: 26/1356

https://datahack.analyticsvidhya.com/contest/machine-learning-summer-training-hackathon/#LeaderBoard

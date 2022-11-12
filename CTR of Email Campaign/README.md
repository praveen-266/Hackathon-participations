## Predict CTR of an Email campaign (JOB-A-THON) 
<!--  -->     

### LeaderBoard:    
Public score : 300 / 8235              
Private score : 600 / 8235 

# Problem Statement        
Most organization today relay on email campaigns for effective communication is one of the popular ways to pitch products to user and build trustworthy relationship with them         

Email campaigns contains different types of CTA(Call To Action). The ultimate goal of email campaigns is to maximize the click Through Rate(CTR)    

CTR is a measure of success for email campaign. The higher the click reate, the better your email marketing campaign is . CTR is calculated by the no.of users who clicked on the least one of the CTA divided by the total no.of users the email was delivered to.           

CTR = No.of users who clicked on at least one of the CTA / No.of emails delivered              

CTR depends on multiple factors like design, content, personalization, etc.      
   * How do you design the email content effectively?       
   * What should your subject line look like?        
   * What should be the length of the email?        
   * Do you need images in your email templates?       
As part of the data science team, in this hackathon, you will build a smart sysytem to **predict the CTR for email campaigns** and therefore **identify the critical factors that will help the marketing team to maximize the CTR.**       

# objective 
Your task at hand is to build a machine learning-based approach to predict the CTR of an email campaign.        

# About the Dataset        
You are provided with the information of past email campaigns containing the email length, no. of CTA, data and time of an email, type of the audience, whether its a personalized email or not, etc and the target variable indicating the CTR of the email campaign        

# Daata Dictionary      
|Variable | Description|      
| ---------| -------------|           
| campaign_id| Unique identifer of a campaign|       
| sender| Sender of e-mail|
|subject_len| No. of character in a subject|        
| body_len| No.of character in a email body|   
| mean_paragraph_len| Average no. of character in paragraph of an email|
| day_of_week| Day on which email is sent|         
|is_weekend| Boolean flag indicating if an email is sent weekend or not|        
|time_of_day| Times of day when email is sent: morning,Noon,Evening|
category| Category of the email is related to |
|product| Type of product an email is related to |
| no_of_CTA| No.of Call To Action in an email|
|no_of_CTA_len| Average no. of character in a CTA|
|is_image| No. of images in email|
|is_personalized| Boolean flag indicating if an emailis personalized to the user or not|    
| is_quote| No. of quotes in an email| 
| is_timer| Boolean flag indicating an email contains a timer ot not|
|is_emoticons| No. of emoticons in an email|
|is_discounts| Booelan flag indicating an email contains a discount or not|
|is_price| Boolean flag indicating an email contains price or not|
|is_urgency| Boolean flag indicating an email contains urgency or not|
|target_audience| Cluster label of the target audience|
|click_rate(Target Variable)| click rate of an email campaign|            

# evaluation metric          
The evaluation metric for this hackathon would be **r2_score** and **RMSE**           


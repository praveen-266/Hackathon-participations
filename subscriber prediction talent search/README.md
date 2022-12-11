
# Problrm statement             
This hackathon will try to address the challenges of banking telecallers when they call blindly to people in order to sell term deposit plans.

# Aim of the project   
The aim of this hackathon is to find the most accurate prediction of whether a person to be called will subscribe to the term deposit plan or not using any of the machine learning algorithms.

# about the dataset           
The dataset has 17 features, including 16 input features and 1 output or target feature

variable | Description|      
------------| -------------|
Age| Age of the customer
Job| Type of job of customer
Marital| Marital status of the customer
Education| The education level of the customer
Default| Has credit in default?
Balance| Average yearly balance (in Euros)
Housing| Has a housing loan?
Loan| Has a personal loan?
Contact| Contact communication type
Day| Last contact day of the month
Month| Last contact month of the year
Duration| Last contact duration, in seconds
Campaign| Number of contacts performed during this campaign and for this client
Pdays| Number of days that passed by after the client was last contacted from a previous campaign (-1 means the client was not previously contacted)
Previous| Number of contacts performed before this campaign and for this client|
Poutcome| Outcome of the previous marketing campaign|
# evaluation metric           
The submission will be evaluated using the Log Loss metric. One can use sklearn.metric.log_loss to calculate the same

# credit-risk-classification
##Task: 
- In this Challenge, I have utalised a range of various techniques to train and evaluate a model based on loan risk. 
- By using a [historical lending dataset](Resources/lending_data.csv) from a peer-to- peer lending services company I have built a model that can identify the creditworthiness of borrowers.

##Steps: 
1. Splitting the Data into Training and TEsting Sets
2. Creating a Logistic Regression Model with the Original Data
3. Writing a Credit Risk Analysis [Report](Report.md) .

## Results & Summary (In Report)
Overall the model was seems to perform well with an accuracy score of 99%. 
- Healthy Loans have an f1 score of 1 while;
- High-risk loans have an f1 score of 0.88. 
- Precision also showed significant results with a value of 1 for healthy laons and 0.85 for High-Risk Loans. 
- Recall also showed significant results with a 100% for low irsk and 0.89 gor high risk loans. 

This highlights how the model accurately managed to predict all the healthy loans while predicting 88% of the high-risk loans. under financial diversification standards this high level predictions could be improved but still considered successfull in the prediction of loans. 
# Customer-Churn-Analysis
Customer Churn Analysis using Machine Learning


•	Describe the  problem :

Customer churn means the number of customers moving out of a collective group over a specific period. It is related to the business case of customers that stop buying from us. 'Churn' translates to revenue loss via customer cancellation.
 So churned(1) customer is a loss i.e. negetive(-ve) case from business perspective. The customers who are not churned(0) will not stop buying or, using our product are positive(+ve) case here. If we can predict which customers are going to be churned  in advance, we can provide them several offers to retain those customers, as customer retention is less costly than getting a new customer from business point of view.


•	What is objective :

Here we need to identify the customers who are going to be churned. If we wrongly predict a churned customer as non-churned it will be a great loss, as we will lose that customer. If we wrongly predict a non-churned customer as churned then it will not be a great loss. So we need to reduce wrong prediction of -  
                              churned(1) -> not churned(0)  i.e. (False Negative) 
instead of -  not churned(0) -> churned(1) i.e. (False Positive).
So, here recall metric will be more appropriate.
Recall score = True Positive/ (False Negative + True Positive)
So, when False Negative will decrease Recall Score will increase as False Negative is at the denominator of the Recall score.


•	How are you planning to solve

We will read the dataset i.e. the .csv file using read_csv() function of Pandas. Then we will look which columns are having null values and make the decision of what should we do with those null entries.  
	

This is a Project about the prediction of a churn by Customers in a bank. 
The approach to solving the problem first has to do with obtaining the data relevant to the problem we're trying to solve. Then we perform some EDA and pre-processing on the data.
Then we move to the model building and evaluation. 
For this task, we saw that we clearly had a problem of imbalance in our target variable class. This lead to a bias in our training. Our model really became good at identifying one class and very bad at another.
To solve this problem, we had to do an oversampling and retrain the model. This time, we got better results from our classification report.
Also it is important to note that everything was done using classical ML techniques and AdaBoost with the baseline and little hyperparameters turning. 
To get higher accuracy, we can still experiment with some transformational techniques on our data and tune the hyperparameters

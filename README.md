# Analysis of Optimal Investment Portfolio 
![AI-Stock-750x350.png](AI-Stock-750x350.png)

The goal of this project is to develop a machine learning model which can be used to help us to form the best investment portfolio of the selected stocks to generate the maximum returns.
## Background 
The implementation of machine learning models and algorithmic trading in the financial industry has enabled traders to make faster, more time-efficient transactions with minial human errors. The supervised learning model we chose is not only able to perform more efficiently than human traders, it is able to simplify data based on historical returns, train the model and calculate the predicted output.
## FinTech Techniques Used 
1) Support Vector Regression (SVR)
2) K Neighbors Regresso
## Model Evaluation
- Method:
We validate the performance of our model in two ways - hold-out validation through splitting data into training and testing sets and back testing using a second model.
- Process:

## Conclusion
## Postmortem 
- The first dififculty we encoutered was obtaining stock data using Alpaca API, including issues like expiring secret keys, wrong ticker names and setting up .env file correctly.
- The second problem we had was the conflict between the type of data and the machine learning model. Initially, we selected Support Vector Machine (SVM) as the model for testing and training continuous stock returns data, which proved to be incompatible as SVM could only be applied to categorical data. We solved this problem by switching to another model called Support Vector Regression (SVR).
- The third issue we had was a syntax
## Resources 
1) Alpaca trade api
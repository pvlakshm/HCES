# HCES
Household Consumption Expenditure Survey (HCES)

Steps  
(1) Train a Linear Regression Model (Data: based on MoSPI’s HCES, NSS 68th Round, 2012 [link](https://microdata.gov.in/NADA/index.php/catalog/126))  
(2) Guard against model-overfitting by applying 2 regularizations: LASSO, Ridge  
(3) Use cross validation to systematically optimize "alpha"  
(4) Make predictions using test data.  
(5) Plot co-relation heatmap, the coefficients, and actual vs predicted values


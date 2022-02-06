# CarPricePredictionModel

Data Source- https://www.kaggle.com/goyalshalini93/car-data

Target Variable- price

Predictors Used- 'wheelbase', 'enginesize', 'curbweight', 'carwidth', 'citympg', 'highwaympg', 'carlength', 'boreratio','horsepower'

AIM- Use price and markups on cars in existing dataset to build a model to predict price of a new car with gicen independent variables. 

Model Evaluation and Accuracy-

	          **Random Forest**	  **Ridge Regression**	  **Ridge Regression CV**	   **Lasso Regression**
R2	            0.930000	        0.750000	                0.810000	               0.810000
Adjusted R2	    0.979184	        0.750204	                0.812653	               0.812653
MAE	            1528.790000	      2700.560000	              2390.010000	             2429.580000
MAPE	          12.000000	        21.000000	                20.000000	                20.000000


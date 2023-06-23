# Prediction-of-Car-Prices
#I think Hyper parameter tuning, Feature SelecƟon, Feature Engineering and Feature Scaling have 
helped improve the performance of my model. 
 Hyperparameter Tuning: I have used Grid search for tuning hyper parameters of 
each of my models. (Include models whose performance increased aŌer tuning 
hyperparameters) 
 Feature SelecƟon: I have selected subset of features ‘Year’, ‘Status’, ‘Mileage’ and 
‘Price’ and unused ‘Model’, ‘MSRP’ features for both training and tesƟng my model.
Feature selecƟon has helped in avoiding the curse of dimensionality. It also aided in 
faster training and predicƟon.
 Feature Engineering: I have hot encoded the status column. I have replaced the ‘Not 
Available’ values in the ‘Mileage’ column with the mean of the rest of the values in the 
‘Mileage’ column. I have also extracted ‘Brand’ and ‘model’ features from ‘Model’ 
column and one hot encoded these features, but have unused them for training and 
tesƟng the model, because of the curse of dimensionality. Curse of dimensionality is a 
common problem that occurs in Machine Learning. It occurs when the number of 
features or dimensions in the dataset is very high compared to the number of data 
points. In high-dimensional spaces, data points tend to become more sparse, making it 
harder to esƟmate distances and relaƟonships between them accurately.
 Feature Scaling: I have normalized all the features using Min Max Scaler and all values 
of the features are between 0 and 1. The performance of the models have increased 
significantly aŌer normalizing the features. 

        Model                   Root mean squared error 
Median                          0.00014010648092550523 
Linear Regression               0.012472013610304509 
Polynomial Regression           0.012275530926750797 
Decision Tree Regression        0.011983832023734653 
Random Forest Regression        0.01188988728031725 
Support Vector Regression       0.07362914897886248 

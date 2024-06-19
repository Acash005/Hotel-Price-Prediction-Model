# Hotel-Price-Prediction

Introduction: The primary objective of the project is to predict a new hotel price based on different features such as location, booking policy, etc., using Machine Learning models. Both hotel owners and customers must know about the approximate price of a hotel. I have used linear regression, Lasso, Ridge, and ensemble models like random forest and decision tree regressor to build a model to predict hotel prices (here, log of prices).

Dataset Details: The dataset was taken from Kaggle. The link is given in Dataset.txt. The dataset included 74,112 entries with 29 features. Some features were accommodated, such as type of hotel, no. of beds, etc. Also, the min and max of multiple features were highly varied, so scaling was required.

Preprocessing was done to make the data consistent and remove outliers. Label Encoding and One hot encoding were used as incorporation into ML models is made easy by converting into numeric data. EDA (Exploratory Data Analysis) was done to determine the trends between different features.

Test Data Results:

 Algorithm          |MSE |RMSE|R2|MAE|
| -------------     | -------------   |---------------|----------|------------|
| Linear Regression     | 0.44             |0.66             |0.56        |  0.51  |
| Lasso| 0.46           |0.67             |0.54        |0.52|
| Ridge              | 0.44              |0.66           |0.56       |0.51|
| SVC | 0.42           |0.65             |0.58        |0.50|

 Algorithm          |MSE |RMSE|R2|MAE|
| -------------     | -------------   |---------------|----------|------------|
| Decision Tree     | 0.37             |0.46             |0.63        |  0.61  |
| Random Forest| 0.31           |0.41             |0.69        |0.56|
| XGB Regressor              | 0.30              |0.41           |0.70       |0.55|
| MLP | 0.42           |0.65             |0.57        |0.50|


Conclusion: Traditional models like linear Regression, Lasso, and Ridge performed moderately. Ensemble models like random forest and XGB Regressor displayed better performance. It can be concluded that the project results are enough to understand machine learning models' ability to predict hotel prices. 

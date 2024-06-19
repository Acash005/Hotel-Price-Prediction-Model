# Hotel-Price-Prediction

Introduction: The primary objective of the project is to predict a new hotel price based on different features such as location, booking policy, etc., using Machine Learning models. Both hotel owners and customers must know about the approximate price of a hotel. I have used linear regression, Lasso, Ridge, and ensemble models like random forest and decision tree regressor to build a model to predict hotel prices (here, log of prices).

Dataset Details: The dataset was taken from Kaggle. The link is given in Dataset.txt. The dataset included 74,112 entries with 29 features. Some features were accommodated, such as type of hotel, no. of beds, etc. Also, the min and max of multiple features were highly varied, so scaling was required.

Preprocessing was done to make the data consistent and remove outliers. Label Encoding and One hot encoding were used as incorporation into ML models is made easy by converting into numeric data. EDA (Exploratory Data Analysis) was done to determine the trends between different features.

Test Data Results:

     |  LR  | Lasso | Ridge | SVC |
--------------------------------
MSE  | 0.44 | 0.46  | 0.44  | 0.42 |
RMSE | 0.66 | 0.67  | 0.66  | 0.65 |
R2   | 0.56 | 0.54  | 0.56  | 0.58 |
MAE  | 0.51 | 0.52  | 0.51  | 0.50 |

     |  DT  |  RF   | XGBoost | MLP |
--------------------------------
MSE  | 0.37 | 0.31  |   0.30   | 0.42 |
RMSE | 0.46 | 0.41  |   0.41   | 0.65 |
R2   | 0.63 | 0.69  |   0.70   | 0.57 |
MAE  | 0.61 | 0.56  |   0.55   | 0.50 |

Conclusion: Traditional models like libear Regression, Lasso, Ridge performed moderately. Ensemble models like random forest and XGB Regressor displayed better performance. It can be concluded that the results of the project are enough to understand the ability of machine learning models in predicting hotel proces. 

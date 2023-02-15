# Web-Phishing-Detection-using-Logistic-Regression

This project is about detecting phishing websites using a logistic regression model and feature engineering. Phishing websites are websites that pretend to be legitimate websites and try to get users to enter their personal or financial information. The project uses a data set from the UCI Machine Learning Repository, which has 11,055 website instances with 30 features and a binary label (phishing or legitimate).

The project follows these steps:

- Data preprocessing: The project cleans and transforms the data set to make it suitable for the model. The project removes missing values, outliers, and categorical features. The project also scales and normalizes the features to make them comparable and consistent.
- Feature engineering: The project uses Recursive Feature Elimination (RFE), which is a method that selects the best features for the model by removing the least important ones one by one. RFE improves the model recall score from 89% to 93% by reducing the number of features from 30 to 13.
- Model building: The project builds a logistic regression model, which is a method that predicts the probability of a website being phishing or legitimate. The project splits the data set into a training set and a test set with a 70/30 ratio and uses a 10-fold cross-validation to train and test the model.
- Model evaluation: The project measures the model performance using different metrics, such as accuracy, precision, recall, F1-score, and ROC curve. The model has an accuracy of 94%, a precision of 90%, and a recall of 93% on the test set. The model also has a high ROC curve, which shows how well the model can distinguish between phishing and legitimate websites.
- Classification threshold analysis: The project changes the probability threshold for making a positive prediction. The project sets the threshold to 0.3, which increases the recall to 96% while keeping the precision at 90%. This means that the model is more likely to catch phishing websites and less likely to let them go.

The project shows how to use logistic regression and feature engineering to create a model for web phishing detection. The project also shows how to adjust the probability threshold to optimize the model performance. The project can be extended by trying other methods, such as random forest or neural network, and other feature selection methods, such as PCA or LASSO.

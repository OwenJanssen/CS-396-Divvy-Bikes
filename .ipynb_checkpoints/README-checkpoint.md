Below is a list of files we used to create our final models:

DivvyBikeDataLinearPolynomialRegression_finalproj.ipynb: This file contains the code for the regression models. It contains a Chi-Squared test used to select the features used in the regression models. In this file, a linear model and a polynomial model are created using the scaled features, and they are optimized using Lasso and Ridge regression. (DivvyBikeDataLinearPolynomialRegression.ipynb and DivvyBikeDataLinearPolynomialRegression_updated.ipynb are older versions of the code and can be ignored.)

KNN_and_Decision_Tree.ipynb: This file contains code for KNN and decision tree models. It contains a Chi-Squared test used to select the features used in the models. Additionally, it contains methods for visualizing performance of models and finding optimal parameters for the model. As parameters were optimized they could be added or removed from the grid search manually. 

MergeData.ipynb: This file contains the method used to merge all monthly data files into one file and add additional fields for each ride. Some of these fields are weather data sourced from the chicago_hourly_weather_data.csv file.

K means.ipynb: This file contains the code for the k means clustering model. It uses KMeans, SSE, and graphs of the silhouette scores to determine the best values for k. 

LogRegress_final.ipynb: This file contains the code for the feature engineering and the models for logistic regression used for the final presentation. The models predict whether a ride is round trip and whether its duration is greater than 30 min.

LogRegress_milestone.ipynb: This file contains the code for the feature engineering and the models for logistic regression used for the milestone presentation. The model predicts whether a ride was taken by a member or casual. It also contains EDA



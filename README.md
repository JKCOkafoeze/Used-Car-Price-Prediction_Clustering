This report explores various machine learning techniques for predicting car prices using both supervised and unsupervised models. Regression models, including simple linear regression, polynomial regression, and multiple linear regression, were applied to predict car prices based on numerical variables such as mileage, engine size, and year of manufacture. Among these, year of manufacture emerged as the best predictor in both simple and polynomial regression, with R² scores of 0.61 and 0.67, respectively.

Random Forest regression, both with and without categorical variables, significantly improved accuracy, achieving an R² score of 0.95. Additionally, Artificial Neural Networks (ANNs) were used, with the best-performing model yielding a near-perfect R² score of 0.99.

Clustering techniques, including k-Means and DBSCAN, were also employed. The combination of price and year of manufacture produced the best clustering result in k-Means, while DBSCAN demonstrated superior clustering performance, particularly in the price versus mileage analysis.

Overall, Random Forest regression and ANN with both numerical and categorical variables provided the most accurate predictions, while DBSCAN offered the best clustering performance for grouping similar vehicles.

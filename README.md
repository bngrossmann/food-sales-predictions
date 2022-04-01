# Predicting Food Sales
This project examines food sales data and develops a model for predicting future sales. A brief presentation discussing the analyses and conclusions of a few of points examined is also provided.

## The notebook
The notbook initially explores the available data. There is an examination of the inconsistencies in the formatting of the data and the presence of missing data.

The relationships between the different features of the data are then looked at through graphical representations of the data. The use of a heatmap allows the correlations between data features to be quickly assessed and guide furture invesitgation.

The data is split into training and testing data sets to be analyzed for machine learning. A few models are developed for relating the data features to the sales values. These models include a linear regression, a decision tree, and a random forest.

The linear regression does not perform particulary well; it provides a coefficient of determination of 0.561 and 0.567 for the training and testing data sets. This indicates that the linear regression can only account for about 56% of the variation in the data.

The regression tree and the random forest perform better. The regression tree provides coefficients of determination of 0.604 and 0.595, and the random forest provides values of 0.611 and 0.603. These are approximately 4% to 5% better than the linear regression, with the random forest marginally better than the regression tree. Other metrics of the models are also provided.

## The presentation
The presentation provides a short tour through the analyses of only a few features, focusing on the number of different items available at each outlet type and the number of different items available within each item type category. After reviewing the information and relationship found, recommendations are given.

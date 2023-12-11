# Housing-dataset
# The data set that we used for this assignment is called “house prices advanced regression
# techniques”. The data set that was provided to us by kaggle contains a test and train csv file.
# While looking over the date we saw that there were a lot of fields in the data set that contained
# nulls. So we decided that we need to clean the data first, we decided to use .fillna(a) and the
# variable that we based into the .fillna was based on the data type of the category. For example
# in the category “LotFrontage” we filled the null fields with 0 since the data type for this category
# was integers. We did that for “GarageYrBlt” and “MasVnrArea” filling the null fields with the
# appropriate data types. Some of the challenges that we faced while creating the visualizations
# was that our data set had too many features and not all the features had meaning for our goal of
# comparing price based on features. So we decided to use a feature of sklearn the method called
# Recursive Feature Elimination (RFE) to reduce the features.
# Aside from the challenges we faced during this project, for testing purposes we decided to split
# the given data set into two so that we can test it. The error metrics that we got are: MAE is at
# 47246.476, MSE is at 4404154073.551, and RMSE is at 66363.801.
# Overall, we saw a many correlation of sale price of a property being affected by the features of
# the properties. For example, if a property had a bigger Lot Area the price of the property was
# higher compared to those that are lower. In conclusion we are safe to assume that when a
# property has many features the price of the property is going to be higher compared to
# properties that have much less features.

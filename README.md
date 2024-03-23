# Portfolio
This repository comprises the necessary files for the Portfolio task assigned in COMP2200/6200 S1 2023. 

The dataset (Yelp_Portfolio1_Input.csv
) can be accessed via the link provided at https://github.com/COMP2200-S1-2023/portfolio-part-1-dataset/releases/download/portfolio-dataset-p1/Yelp_Portfolio1_Input.csv

# Portfolio 1
## Analysis on User-generated review on businesses
The dataset (Yelp_Portfolio1_Input.csv
) can be accessed via the link provided at https://github.com/COMP2200-S1-2023/portfolio-part-1-dataset/releases/download/portfolio-dataset-p1/Yelp_Portfolio1_Input.csv
The main idea or learning from this portfolio is that we are learning how to clean the data and randomly select a city from the column, and we are doing analysis on that data. Finally, we are visualizing the data using boxplots and comparing 2 boxplots when the outliers are present and when the outliers are removed.
1. After the dataset is imported we are checking and fill out missing values or remove the fields which have missing values completely.
2. We are randomly selecting a city from a column and doing an analysis of that city. 
3. Visualize the data where we are exploring how each feature behaves. And we are checking the correlation of 2 variables, i.e how one variable has an impact on another variable.


# Portfolio 2
## Analysis of Business Dataset
Dataset = Yelp_portfolio2_input.csv
The portfolio introduces the topic of linear regression, using which we can get insights into the data, and user preferences, and help business improve their services. 
1. Here the dataset is cleaned and we are grouping all the businesses which are unique in a column and getting the count of it.
2. Next step is to remove outliers present in the data, as it may not give us an accurate model. 
3. Running the linear regression model on the filtered data, where we are separating the dataset into train and test. Using the training dataset the model is trained and it will try to predict the value of the test dataset and we can check for the performance of the model.


# Portfolio 3
## Analysis on Homeloan records from Lending Club Dataset
Dataset = Lending club dataset
This portfolio introduces the topic of logistic regression, where we are using credit.policy feature as our dependent variable. Using the correlation matrix we are extracting features that have the closest correlation as our independent variable. 
1. We are filling out missing values in the dataset and removing abnormal data points from the dataset. We are filling out missing values by the mean value of that column.
2. The Next step is to normalize the values of the column so that we can get a better model and increase its accuracy. Using a one-hot encoder we are converting the object type features to numerical values for better assessment of the model.
3. Using logistic regression we are training this model after we normalize the features. Using cross-validation, we will determine a hyper-parameter and validate the model's accuracy.

# Portfolio 4
## Analysis of House pricing prediction
Dataset = House prediction dataset
The main idea behind Portfolio 4 is to predict the housing price based on the features given. We are using linear regression to train the model and later we are using K nearest Neighbors model to train the model.
1. We are visualizing the data for all the columns to check how the distribution of values is across the range.
2. Initially, using linear regression we are training the model on a few of the features we got from the correlation matrix. After training the model the accuracy came down to about 57%.
3. Using KNN neighbors regression, we find out the mean absolute error and root mean squared error of the model, and the accuracy of this model is around 62%.

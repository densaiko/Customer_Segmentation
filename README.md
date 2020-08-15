# Data Science Customer Segmentation: Project Overview
- Created the overall transaction from E-commerce platform between 01/12/2009 until 01/12/2010 using plotly
- Created the map based on the country that doing a transaction in E-commerce platform
- Clustered the products into 5 categories and clustered the customers into 11 categories using KMeans and enhanced it by Silhouette Score
- Created several classification models, test the quality of the models using learning curves and optimized Logistic Regression, Gradient Boosting and KNN Clasifier using Voting Classifier

# Data Cleaning
The data is collected from UCI Machine Learning entitled "Online Retail II Data Set". I made the following changes and create new variables:
- Deleted the 20.5% missing values on CustomerID variables and drop the 50% duplicate values in dataframe
- Deleted the 2.37% data without counterparts that the transaction previously made 
- There are 16 products that contains "Testing Product", so I delete this product
- Added the quantity cancellation and total price that previously grouped by customerID
- Counted the amount of customer who have done several transactions

# Exploratory Data Analyses (EDA)
I create several visualizations that retrieve information about the habit of transaction and the habit of customers

# Module 18: Unsupervised Machine Learning 

# Project Overview 
## Purpose of Module 18 
In this module, we dove deeper into machine learning algorithms where we used unsupervised learning to explore data in which we are not sure what we are looking for and where there are no clear outputs. We explored the requirements for unsupervised learning and preprocessed our data to transform it for analysis. We were introduced to K-Means algorithms for grouping data and discovered the methods to determine the best number centroids for the model. We enhanced the K-Means algorithm with the principal component analysis and visualized our findings with hvPlot and plotly.express. With unsupervised machine learning, we find that we are able to transform our data to create an intuitive representation for analysis or to use in another machine learning model. 

## Overview of Assignment 
The goal of this assignment was to analyze a dataset of cryptocurrencies to discover trends that will potentially convince a firm to invest in cryptocurrencies. To begin our analysis, we preprocessed the data by managing unnecessary columns, removing rows with null values, setting our index, manipulating columns from string to num-type variables, and standardizing our data so it can be used in the clustering algorithm. We then reduced the dimensions for analysis to three principal components using PCA. We then created an elbow curve with hvPlot and found that the best value for K was four. With a known K-value of four, we were able to run the K-means algorithm to make predictions on the clusters for the cryptocurrencies data.  After fitting the model and making predictions, a DataFrame was created to contain the three principal components, the predicted classes, and the columns containing relevant data pertaining to the clusters. We then visualized the cryptocurrency results by creating scatter plots with hvPlot that showed the distinct groups corresponding to the principal components and further reflected this data in a hvPlot table that could be filtered by each column. The data was further scaled on the ‘TotalCoinSupply’ and ‘TotalCoinsMined’ columns so that each feature within the columns is between the given range of zero and one. Lastly, with the scaled data and their corresponding CoinName and Class, a scatter plot was created to show relation between coins mined and their supply by class. 

## Resources 
- crypto_data.csv
- Scikit-learn version 1.0.2
- Conda version 4.11.0
- Python version 3.8.8
- Jupyter version Notebook 6.3.0
- Plotly version 5.6.0
- hvPlot version 0.7.3
- Pandas version 1.3.5
- [PCA Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html)
- [K-Means Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.cluster.KMeans.html)
- [3D Scatter Documentation](https://plotly.com/python-api-reference/generated/plotly.express.scatter_3d.html#plotly-express-scatter-3d)
- [hvPlot Table Documentation](https://hvplot.holoviz.org/reference/pandas/table.html#table)
- [MinMaxScaler Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.MinMaxScaler.html#sklearn.preprocessing.MinMaxScaler.set_params)
- [hvPlot Customization](https://hvplot.holoviz.org/user_guide/Customization.html) 



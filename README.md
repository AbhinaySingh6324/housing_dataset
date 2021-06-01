# Housing dataset
In this project, I applied basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. I first explored the data to obtain important features and descriptive statistics about the dataset. Next, I properly split the data into testing and training subsets, and determine a suitable performance metric for this problem.The Boston housing market is highly competitive, and you want to be the best real estate agent in the area. To compete with your peers, you decide to leverage a few basic machine learning concepts to assist you and a client with finding the best selling price for their home. Luckily, you've come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. Your task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for your clients' homes. Then I analyzed performance graphs for a learning algorithm with varying parameters and training set sizes. This enabled me to pick the optimal model that best generalizes for unseen data. Finally, I tested this optimal model on a new sample and compare the predicted selling price to my statistics. The main techniques used:

Evaluating Model performance,
Model Evaluation & Validation,
Model Optimization.

# Highlights
This project is designed to get you acquainted to working with datasets in Python and applying basic machine learning techniques using NumPy and Scikit-Learn. Before being expected to use many of the available algorithms in the sklearn library, it will be helpful to first practice analyzing and interpreting the performance of your model.

Things you will learn by completing this project:

How to use NumPy to investigate the latent features of a dataset.
How to analyze various learning performance plots for variance and bias.
How to determine the best-guess model for predictions from unseen data.
How to evaluate a model's performance on unseen data using previous data.

# Technology Used
This project applies basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home.

Software and Libraries
This project uses the following software and Python libraries:

* Python 3.9
* NumPy
* pandas
* matplotlib
* scikit-learn
# Model selection
I used different regressors and checked their Root-squared score in the beginning of the project.But slowly visualising the data  and using pairplot and looking at scatter plot of data,I came to conclusion that decision tree regressor will fit best in this kind of dataset.   

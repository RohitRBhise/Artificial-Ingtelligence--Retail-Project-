# Artificial-Ingtelligence--Retail-Project-

PROBLEM STATEMENT: Demand Forecast is one of the key tasks in Supply Chain and Retail Domain in general. It is key in effective operation and optimization of retail supply chain. Effectively solving this problem requires knowledge about a wide range of tricks in Data Sciences and good understanding of ensemble techniques. You are required to predict sales for each Store-Day level for one month. All the features will be provided and actual sales that happened during that month will also be provided for model evaluation.

DATA DESCRIPTION: Training Data Description: Historic sales at Store-Day level for about two years for a retail giant, for more than 1000 stores. Also, other sale influencers like, whether on a particular day the store was fully open or closed for renovation, holiday and special event details, are also provided.
EXPLORATORY DATA ANALYSIS:  
Transform the variables by using data manipulation techniques like, One-Hot Encoding. 
Perform an EDA (Exploratory Data Analysis) to see the impact of variables over Sales.
Apply Linear Regression to predict the forecast and evaluate different accuracy metrices like RMSE (Root Mean Squared Error) and MAE(Mean Absolute Error) and determine which metric makes more sense. Can there be a better accuracy metric?
Train a single model for all stores, using storeId as a feature.
Train separate model for each store.
Which performs better and Why? [In the first case, parameters are shared and not very free but not in second case]
Try Ensemble of b) and c). What are the findings?
Use Regularized Regression. It should perform better in an unseen test set. Any insights?
Open-ended modeling to get possible predictions.

IMPLEMENTING NEURAL NETWORK:
Train a LSTM on the same set of features and compare the result with traditional time-series model.
Comment on the behavior of all the models you have built so far
Cluster stores using sales and customer visits as features. Find out how many clusters or groups are possible. Also visualize the results.
Is it possible to have separate prediction models for each cluster? Compare results with the previous models.

APPLYING ANN:
Use ANN (Artificial Neural Network) to predict Store Sales.
Fine-tune number of layers,
Number of Neurons in each layers.
Experiment in batch-size.
Experiment with number of epochs. Carefully observe the loss and accuracy? What are the observations?
Play with different  Learning Rate  variants of Gradient Descent like Adam, SGD, RMS-prop.
Which activation performs best for this use case and why?
Check how it performed in the dataset, calculate RMSE.

Use Dropout for ANN and find the optimum number of clusters (clusters formed considering the features: sales and customer visits). Compare model performance with traditional ML based prediction models. 

Find the best setting of neural net that minimizes the loss and can predict the sales best. Use techniques like Grid search, cross-validation and Random search.
 

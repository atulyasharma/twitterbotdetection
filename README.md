# Twitter Bot Detection

Data Science project to distinguish bot user accounts from human user accounts on Twitter using various Machine Learning Algorithms

# Dataset Link

https://botometer.iuni.iu.edu/bot-repository/datasets/cresci-2017/cresci-2017.csv.zip

## Step 1 - Data Preprocessing

The initial dataset is cleaned by down to nearly 2k rows by handling missing values and cleaning the data in the form that it will be useful.

## Step 2 - Implementing Logistic Regression

* The data is fit to the model, trained and then it's accuracy is predicted.
* It is then cross validated to check its consistency.
* The final heatmap is generated to show the outcomes.

## Step 3 - Implementing Support Vector Machines (SVM)

* 3 different kernels that were used are Linear, RBF and Polynomial 3 degree.
* Plotting Accuracy V/S C graphs with and without Principal Component Analysis (PCA) done on the dataset.

## Step 4 - Implementing RandomForest

* It is an extension of decision tree model and used multiple decision tree to perform the prediction.
* Heatmap is plotted to show the confusion matrix of the trained and tested accuracies.

## Step 5 - Comparing the models

On comparing the different algorithms used, we have found out the Support Vector Machines (SVM) is the most accurate model for our use case.

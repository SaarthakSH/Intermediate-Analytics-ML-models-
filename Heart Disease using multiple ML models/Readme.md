# How to access and execute RMD file

Installing and loading the necessary libraries and loading the associated data set are prerequisites for running the RMD R file. My recommendation is to make a folder to hold both the dataset and the RMD file when you download both, then inside that folder, make another folder called "DataSets" and put the excel file containing the data set inside of that. All of the work is done in a R Markdown file when you open the RMD file, and you must import the dataset in order to execute it. You can access the data set in the "DataSets" folder or any other name you like from the files tab. The route link for the imported data set must be copied after the data set has been imported since it must run with the installed libraries in order for the code to run. All codes should now run and function correctly after completing that. The codes can be knitted into PDF or HTML files, as desired.

# Heart Disease Analysis using multiple ML models

On data on heart illness that was taken from Kaggle, basic descriptive statistics and exploratory data analysis were performed using R. Regression analysis is performed utilizing data that have been tested, trained, and used. The training and testing data were then subjected to logistic regression analysis, and the ROC value was subtracted. Ridge and lasso regression on the model employing regularization is then performed, and the results are compared to the RMSE value.

Dataset - https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease?select=heart_2020_cleaned.csv

## Skill used – 

R, Regression Analysis, GLM and Logistic Regression, Confusion Matrix, ROC & AUC, Regularization using Ridge and Lasso, Machine Learning.

## Output-

A well-structured report on heart illness that uses several ML models to be objective. Three models were tested using a testing and training data set, and the most preferred model was ultimately chosen.

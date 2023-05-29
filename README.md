# Heart-Disease-Prediction
### Purpose:

To find the correlations between the different attributes available in the dataset with the help of standard Machine Learning methods and then use them efficiently in the prediction of chances of heart disease.

### Problem Statement:

As per the recent study by WHO, heart related diseases are increasing. 17.9 million People die every-year due to this. With growing population, it gets further difficult to diagnose and start treatment at early stage. Early detection and treatment of several heart diseases is very complex because of the lack of diagnostic centers, qualified doctors and other resources that affect the accurate prognosis of heart disease.

### How the problem was efficiently solved:

By building a ML model for heart disease prediction based on the related parameters. Benchmark dataset of UCI Heart disease is used for prediction in the model. Models based on supervised learning algorithms such as Support Vector Machines (SVM), K-Nearest Neighbor (KNN), Logistic Regression, Decision Trees (DT), and Random Forest (RF) were be used for development of model.

### Approach:

#### 1. Data analysis and visualizations: 
Subplots between different independent variables shows the chances of having a heart disease in an Individual based on the value of the independent variable for improved prediction.
#### 2. Correlation and outlier detection: 
a correlation matrix was plotted to determine the correlation between the independent variables, and it is observed that there is not much of correlation.
#### 3. Data modelling: 
Started with data cleaning where outliner detection is performed followed by transformation of some input variable to categorical data.

#### 4. Model training:
For model training the data is split in 70/30 ratio with 30% test data and 70% training data with random state 100 to get same examples every time to reproduce the same results. The model was trained using the training data.

#### 5. Predictions:
Predictions and accuracy scores were calculated using different models to determine the performance of different models and find the model with ML algorithm that gives more accuracy in less time i.e., most efficient.

### Impact:

Generated Python based machine learning model for heart disease prediction on UCI Heart disease dataset with ML algorithms: SVM, Logistic Regression, KNN and Decision Trees which will be helpful to the medical practitioners at their clinic as decision support system to efficiently predict the chances of Heart disease.

### Tools & Tech: Python, Jupyter Notebook

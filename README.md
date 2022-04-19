# Objective
To Cluster the Marketing dataset to effectively design campaigns around target groups/clusters

# Libraries Used
1. Pandas
2. Scikit Learn
3. Matplotlib
4. Numpy
5. Datetime
6. Seaborn
7. Scipy
8. Plotly

# Algorithms Used
1. K Means

# Data cleaning
1. Income Column - Impute by Mean (Normal distribution)
2. Deleting outlier records +- 3 sigma levels

# Feature engineering
1. Adding 'number of children' and 'number of teen' columns to get 'people at home' column
2. Clubbing Marital status into Married and unmarried
3. Dropping irrelevant parameters
4. Calculate Age column from DOB
5. Enrolment duration from customer joining date
6. Creating total spends column from all available spend columns
7. OHE education number column


# Data Transformation
Standard Scaling the parameters (Quantitative)

# Best Model performance
![alt text](https://github.com/sanketmore1234/Predict-service-quality/blob/main/Best%20Model%20performance-%20Ridge.jpg?raw=true)

# Finding optimal K
1. By using Silhouette score
2. By using Elbow method

# EDA
## 1. Visualizing clusters with Income and Age parameters

## 2. Visualizing clusters with Income and Total Age parameters

## 3. Visualizing clusters with Total Spend and Monthly fruit consumption parameters

## 4. Visualizing clusters with Total Spend and Monthly meat consumption parameters

## 5. Visualizing clusters with Total Spend and Monthly sweet consumption parameters

## 6. Visualizing clusters with Income and Total purchases parameters

## 7. Visualizing clusters with Visits per month and age parameters

## 8. Visualizing clusters with Store purchases and age parameters

## 9. Visualizing clusters with Total Spend and Campaign 5 acceptance parameters



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

# Finding optimal K
1. By using Silhouette score
2. By using Elbow method

# EDA
## 1. Visualizing clusters with Income and Age parameters
![alt text](https://github.com/sanketmore1234/Campaign-Market-Clustering/blob/main/cluster_income_age.png?raw=true)

## 2. Visualizing clusters with number of members
![alt text](https://github.com/sanketmore1234/Campaign-Market-Clustering/blob/main/cluster_numbers.png?raw=true)

## 3. Visualizing clusters in 3d
![alt text](https://github.com/sanketmore1234/Campaign-Market-Clustering/blob/main/cluster_3d.png?raw=true)

## 4. Visualizing clusters with Total Spend and Monthly fruit consumption parameters
![alt text](https://github.com/sanketmore1234/Campaign-Market-Clustering/blob/main/Screenshot%202022-04-19%20231052.png?raw=true)

## 5. Visualizing clusters with Total Spend and Monthly meat consumption parameters
![alt text](https://github.com/sanketmore1234/Campaign-Market-Clustering/blob/main/Screenshot%202022-04-19%20231105.png?raw=true)

## 6. Visualizing clusters with Total Spend and Monthly sweet consumption parameters
![alt text](https://github.com/sanketmore1234/Campaign-Market-Clustering/blob/main/Screenshot%202022-04-19%20231116.png?raw=true)

## 7. Visualizing clusters with Income and Total purchases parameters
![alt text](https://github.com/sanketmore1234/Campaign-Market-Clustering/blob/main/Screenshot%202022-04-19%20231127.png?raw=true)

## 8. Visualizing clusters with Visits per month and age parameters
![alt text](https://github.com/sanketmore1234/Campaign-Market-Clustering/blob/main/Screenshot%202022-04-19%20231138.png?raw=true)

## 9. Visualizing clusters with Store purchases and age parameters
![alt text](https://github.com/sanketmore1234/Campaign-Market-Clustering/blob/main/Screenshot%202022-04-19%20231152.png?raw=true)

## 10. Visualizing clusters with Total Spend and Campaign 5 acceptance parameters
![alt text](https://github.com/sanketmore1234/Campaign-Market-Clustering/blob/main/Screenshot%202022-04-19%20231202.png?raw=true)

# Conclusion
### Summarizing the insights --------------------------------------
1. Elite group consists of 460 customers
2. They form 23% of the population
3. Elite cluster spends more, has high income
4. Elite cluster likes Wine, Fruits and other eatables
5. Elite customers purchase more considering all the food, beverage categories
### Response to physical Stores --------------------------------------
Elite customers are more inclined to go to physical stores than web visits
### Campaign Response --------------------------------------------
1. Campaigns 1,3,5 and 6 were the ones where maximum participation was from the Elite class
2. Campaigns 2,4 were the ones where maximum participation was from the Good cluster
### Marketing objectives --------------------------------------------
We need to target the Elite class of customers considering all these attributes. Since this is a small group, we can concentrate our efforts more and have effective offers, discounts to maximize Revenues and overall Profit
We can also target the Good cluster to promote them to the Elite class
For targeting the Elite class, we can focus on campaigns 1,3,5,6 and check what made these campaigns attract the Elite class

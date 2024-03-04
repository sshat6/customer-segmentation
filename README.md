# Customer Segmentation & Hypothesis Testing with KMeans
## Background
Customer segmentation is a powerful marketing tool that involves dividing customers into groups based on common characteristics. This allows companies to tailor their marketing efforts more effectively to various audience subsets. Segmentation criteria often include demographics such as age, gender, marital status, location, life stage, and income.

This project focuses on using unsupervised machine learning, specifically the KMeans Clustering Algorithm, to perform customer segmentation. The goal is to understand customer behaviors and characteristics to identify target customer groups for more effective marketing strategies.

### Data Presentation
#### Context
This dataset is to illustrate customer segmentation or market basket analysis concepts using the KMeans Clustering Algorithm. The dataset includes basic information about customers of a supermarket mall obtained through membership cards, such as Customer ID, age, gender, annual income, and spending score. The spending score is a metric based on customer behavior and purchasing data.

#### Dataset
Mall_Customers.csv: Contains customer information (ID, age, gender, income, spending score).
Problem Statement
The analysis aims to understand the customers who can be easily targeted (Target Customers) so that the marketing team can formulate and plan strategies accordingly.

#### Project Objectives
Implement customer segmentation using the KMeans Clustering Algorithm in Python.
Identify target customers for initiating marketing strategies.
Understand how marketing strategies are applied in the real world.

#### Project Process
##### Step 1: Importing Libraries
##### Step 2: Exploratory Data Analysis (EDA)
Importing Data
Basic EDA (The dataset contains 200 rows and 5 columns)
Univariate Analysis
Bivariate Analysis
Checking for Association between Gender and Score
Checking for Association between Gender and Annual Income
Checking for Association between Annual Income and Score
Checking the Association between Age (Binned) and Spending Score
Checking the Association between Age (Binned) and Annual Income
##### Step 3: Modelling - KMeans
Note:
Any number of features can be considered as input to the Clustering Algorithm, but for visualization purposes, at most three features can be considered.
Gender is deemed the least important feature based on statistical tests and is not considered in the model.
Determining the Optimum Value of K using the Elbow Method
K is a parameter of the KMeans Algorithm indicating the number of clusters to form.
init='k-means++' ensures that initial clusters are chosen smartly, increasing the chances of convergence.
#### Hypotheses
Throughout the project, several hypotheses are tested to understand the relationships between different variables, such as gender, annual income, and spending score, and their impact on customer segmentation.

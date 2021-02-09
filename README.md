# Most Trending YouTube Video Pattern
Just another repository

Hello, this is the project about the most trending YouTube video pattern as we trying to investigate the pattern of trending video through the number of view, likes, dislikes and comments based on three main categories entertainment, music and blog.


# Data Mining Project
# Hypothesis From Datasets
1. What is the average views, likes,dislikes and comments from the datasets?
2. What will happen to the number of views, comments and dislikes if the number of likes is higher?
3. Is the category with high number of views can have high number of comments?
4. Is the category with high number of views can have high number of dislikes?
5. In average, is the category with high number of views can have high number of comments?


# Explatory Data Analysis Steps and Examples
Exploratory Data Analysis or EDA is the first and foremost of all tasks that a dataset goes through. EDA lets us understand the data and thus helping us to prepare it for the upcoming tasks. 

**1. Import the datasets**

**2. Identifying the Summary of the DataFrame**

**3. Visualisations using PowerBI**

**4. Answer the questions based on visualisations**


# Data Preprocessing

1. Data cleaning
-Remove outlier, replace missing values, smoothing noisy data & correcting inconsistent data. Select each attributes in the excel file that need to be cleaned. Click on Data at the above section and enter filter. Select the small box at the attributes and it will shows the list of data for each attributes. Tick the blanks data then click remove data to delete unwanted data in the specific attributes. Continue the process for the next attributes until the last attributes in the Excel file to ensure the next process is smooth and valid.

2. Data integration
-Since the data could be redundant and inconsistent, it would lead to poor accuracy and speed of the model. So, we performed on the attribute which identifies unique entities

3. Data reduction
-Remove unimportant attributes since not all data in the datasets will be used.

4. Data transformation
-Transforming the data into form appropriate for Data Modeling. Split dataset into two separate sets which is training set and test set for machine learning model into 70:30 ratio or any other test size.



# Steps in Developing the Descriptive Data Mining Solution

A descriptive model describes a system or other entity and its relationship to its environment. For my project, I choose clustering method as the method for the process and kMeans is the model of machine learning algorithm. Following are the steps in developing the descriptive data mining solution:

1. Randomly select k centroids, where k is the number of cluster you chose. In our project, we have 3 cluster.
2. Maximization step computes the mean of all the points for each cluster and sets the new centroid.



# Steps in Developing the Predictive Data Mining Solution

Predictive is the process by which information is extracted from existing datasets for determining patterns and predicting the forthcoming trends or outcomes. For this project, I choose classification method as the method for the process with three classifiers. 

1. Import required libraries
2. Import and upload file into Google Colab
3. Load data and read file that has been imported.
4. Divide given columns into two types of variables dependent (or target variable) and independent variable (or feature variables)
5. Import required classifier 
6. Print the accuracy of the model (Decision Tree and Random Forest)
7. Record the result.



# Results & Analysis

We measured the accuracy of each prediction algorithm models which are Random Forest, kNN and Naive Bayes before and after hyperparameter tuning using Rapid Miner & Python. We provide training ratio and test ratio which are 70:30, 50:50 & 30:70 respectively for both Rapid Miner & Python. The results are as follows:

1. Best model accuracy before tuning - Random Forest (both Rapid Miner, Python)
2. Best model accuracy after tuning - Random Forest (Rapid Miner) & kNN (Python)
3. Best model overall - Random Forest with 70% training ratio and 30% training ratio

From the streamlit as data product, we provide the metric for the company to measure the performance of their marketing strategy through YouTube videos. There are 3 metric which are best trending, moderate trending and worst trending. The results are as follows:

1. For the best trending, the minimum for each views, likes, comments and dislikes, are 626794 view, 346 likes, 3 comments and 67 dislikes.
2. For the moderate trending, the minimum for each views, likes, comments and dislikes, are 322079 view, 363 likes, 6 comments and 38 dislikes.
3. For the worst trending, the minimum for each views, likes, comments and dislikes, are 100053 view, 91 likes, 8 comments and 3 dislikes.

# Conclusion 

We provides the full results based on best trending, moderate trending and worst trending that mostly influenced from the views from each videos. The stakeholders can measure the performance of their marketing strategy through YouTube videos as we have provided the accurate metric based on the clusters in this project. 



# Reflection

Personally learning in this course & doing assignments have make me wondering what i have gained through the semester. I am not really good with many data so i tends to be slow in this project. Though that being said, I cannot deny the thrills and challenges from this project, also previous assignments. Thankfully, helps and guidances from team members, supportive friends and also Dr Fadhlina, makes me going throughout the whole semester and project. I wish all the best for all of us, thank you! :)



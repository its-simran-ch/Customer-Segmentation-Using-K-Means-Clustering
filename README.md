# Prodigy_ML_Task_2
Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.


## Task 2: Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

**Dataset:** https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python
<br>

This task is part of my internship at Prodigy InfoTech, where i implemented a K-means clustering algorithm to group customers of a retail store based on their purchase history based on given features like CustomerID, Gender, Age, Annual Income (k$), Spending Score (1-100). 
<br>

**--Project Overview--**
<br>

The goal of this task is to create a K-means clustering algorithm to group customers of a retail store based on their purchase history using a dataset from Kaggle. The dataset includes features such as:
<br>
:) CustomerID : Unique ID assigned to the customer
<br>
:) Gender : Gender of the custome
<br>
:) Age : Age of the customer
<br>
:) Annual Income (k$) : Annual Income of the customee
<br>
:) Spending Score (1-100) : Score assigned by the mall based on customer behavior and spending nature
<br>


**--Tools Used--**
<br>

**Python** : For scripting and implementation.
<br>
**Google Colab** : For writing and running the code in a Jupyter Notebook environment.
<br>

**--Libraries Used--**
<br>

**numpy**: For numerical computations.
<br>
**pandas**: For data manipulation and preprocessing.
<br>
**matplotlib**: A widely used data visualization library.
<br>
**seaborn**: Built on top of Matplotlib, used for statistical data visualization.
<br>
**scikit-learn**: A machine learning library that provides simple and efficient tools for data analysis and modeling.
Includes KMeans for clustering and StandardScaler for feature scaling .
<br>

**--Implementation Steps--**
<br>

(1) **Data Preprocessing**: 
<br>
:) Load the dataset using Pandas.
<br>
:) Remove unnecessary columns like CustomerID and Gender, as they don't contribute to clustering.
<br>
:) Scale numerical features using StandardScaler to normalize values.
<br>


(2) **Finding Optimal Clusters (Elbow Method)** : 
<br>
:) Use the Elbow Method to determine the best number of clusters by plotting inertia (Sum of Squared Errors - SSE).
<br>

(3) **Applying K-Means Algorithm** : 
<br>
:) Train the K-Means model with the optimal number of clusters (determined by Elbow method).
<br>
:) Assign each customer a cluster.
<br>

**--Results & Visualization--** 
<br>
:) The Elbow Method plot suggests the optimal number of clusters is 5.
<br>
:) The final visualization shows customers grouped based on their Annual Income & Spending Score.
<br> 
:) Different clusters indicate different customer behaviors (e.g., high income & high spending vs. low income & low spending).
<br> 


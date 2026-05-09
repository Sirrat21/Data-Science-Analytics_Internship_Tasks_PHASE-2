# Data-Science-Analytics_Internship_Tasks_PHASE-2

**Bank Marketing Prediction Project
Task Objective**
The objective of this project is to predict whether a customer will subscribe to a term deposit based on their personal and campaign-related information.
The task focuses on handling an imbalanced dataset and building a model that can accurately identify potential customers.

**Approach**
1. Data Preprocessing
•	Loaded and explored the dataset
•	Handled missing values (if any)
•	Encoded categorical variables
•	Checked class imbalance in the target variable
2. Feature Selection
•	Selected relevant features affecting customer decisions
•	Removed unnecessary or redundant columns
3. Train-Test Split
•	Split the dataset into training and testing sets (80/20 ratio)
4. Model Building
•	Implemented:
o	Logistic Regression
o	Random Forest Classifier
5. Model Evaluation
•	Used metrics:
o	Accuracy
o	Precision
o	Recall
o	F1-score
6. Model Explainability
•	Applied SHAP
•	Identified important features influencing predictions


**Results and Findings**
•	The dataset was highly imbalanced, with most customers not subscribing
•	Random Forest outperformed Logistic Regression, especially in terms of F1-score
•	Logistic Regression struggled to capture complex relationships
•	SHAP analysis revealed key influencing features such as:

o	Duration of contact
o	Previous campaign outcomes
o	Number of contacts
**




**Task 2: Customer Segmentation Using Unsupervised Learning**

**Objective**

The objective of this project is to segment customers based on their spending behavior using K-Means Clustering.

**Dataset**
Mall Customers Dataset containing:
•	Gender 
•	Age 
•	Annual Income 
•	Spending Score 

**Tools & Technologies**
•	Python 
•	Google Colab 
•	Pandas 
•	NumPy 
•	Matplotlib 
•	Seaborn 
•	Scikit-learn 

**Project Steps**
1.	Loaded and explored the dataset 
2.	Performed Exploratory Data Analysis (EDA) 
3.	Selected important features 
4.	Applied feature scaling 
5.	Used Elbow Method to find optimal clusters 
6.	Applied K-Means Clustering 
7.	Visualized clusters using PCA
    
**Results**
•	Optimal number of clusters found: 5 
•	Customers were divided into different groups based on income and spending habits. 
•	PCA helped visualize the clusters clearly. 

**Marketing Strategies**
•	High spenders → Premium offers & VIP services 
•	Low spenders → Discounts & budget promotions 
•	Average customers → Reward points & regular promotions 

**Conclusion**
K-Means Clustering successfully segmented customers into meaningful groups. These insights can help businesses improve customer targeting and marketing strategies.



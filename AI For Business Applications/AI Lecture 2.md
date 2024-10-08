# 1 Machine Learning
- Artificial Intelligence
	- Machine Learning
		- Deep Learning
![[Pasted image 20240826123214.png|400]]
## 1.1 Why ML?
- Develop strengths for the job market
## 1.2 ML Pipeline

> Way to codify and automate the workflow it takes to produce a machine learning model.

- Model training is only a small piece of the machine learning process
- Creating successful machine learning systems involves a lot more than choosing between a random forest model and a support vector machine model
- E.g.: 
	- Input data: furry + barks
	- Output data: dog
## 1.3 Steps in a ML pipeline
![[Pasted image 20241002162443.png]]
***Problem Definition***
- For a given loan, will it be repaid or not? 
- When will the loan be repaid? 
- How much money will be received from a given loan? 
- What will be the profit made on a given loan? 
- What will be the profit made on a given loan without using disallowed input features?

***Data Ingestion***
- What data provider or vendor should we use? Can they be trusted?
- How will it be ingested?
- Should it be stored as a file or in a database?

***Data Preparation***
- Data cleansing
- Filtration
- Aggregation
- Augmentation
- Consolidation Storage
- Missing values
	- Do nothing
	- Imputation using **Median**
	- Imputation using **Most frequent value**

***Data Segregation***
![[Pasted image 20241008175316.png]]

***Model Training***
![[Pasted image 20241008175412.png]]
## 1.4 Feature Selection
- **Lower the amount of input features**
	- Shorten training time
	- simplify models and make them easier to interpret
	- Enhances testing set performance y reducing overfitting
	- for a model to produce accurate results, you need to make sure it's using the *right* data
	- data with most predictive power
- **Lot of domain knowledge**
	- ML + manual feature selection
- **Limited domain knowledge**
	- automatic feature selection techniques
		- neighborhood component analysis
	- deep learning algorithm
- **Lot of features**
	- Principal component analysis with ML to reduce dimensionality
## 1.5 Domain Knowledge

***Case Description***
>You are HR working for a company that wants to predict employee performance ratings based on various factors. You need to collect data on employees’ basic information and performance metrics. The goal is to build a machine learning model that can predict employees' performance ratings at the end of the year.

***Objectives***
- Identify the problem
- Data preparation

***Data Preparation***
- **Data Selection**
	- Employee Information:
		- Gender
		- Age
	- Work Metrics (domain knowledge):
		- working time
		- project completion rate
		- other aspects
	- Final outcome:
		- Performance rating
- **Data Preparation**
	- Missing values: median value
	- Categorical data: one-hot encoding
	- numerical data: scaling
		- standardscaler or minmaxscaler

***ML Techniques***
- Feature Importance
	- ExtraTreesClassifier & matplotlib
	- provide score for each feature in dataset -> important features
- Univariate selection
	- SelectKBest & chi2
	- provide score for each feature in dataset, can be used to determine which features have strongest correlation to the output variable
- Correlation heatmaps
	- seaborn & matplotlib
	- matrix to show relationship between different values of the features
## Feature Engineering
### Feature Selection vs Engineering
- Selection => remove variables
- Engineering => create new variables to enhance model
- Steps 
	- Brainstorm about which features are relevant; 
	- Decide what features might improve the model performance; 
	- Create new features and determine if you should add them to the model performance (if not, drop them); 
	- Go back to step 1 until the performance of the model meets expectations.
### Data Preparation Techniques
- Imputation
- One-hot encoding
- Scaling
#### Imputation
- Using median values
![[Pasted image 20241008180714.png]]
- Using common values
![[Pasted image 20241008180756.png]]
#### One-hot Encoding
- Transfer text to numerical data

```
［“Life is short, I like python”， "Life is too long, I hate python“］
```
 - Feature names:
	 - hate
	 - is
	 - life
	 - like
	 - long
	 - python
	 - short
	 - too
`[[0 1 1 1 0 1 1 0] [1 1 1 0 1 1 0 1]]
#### Scaling
![[Pasted image 20241008181211.png]]
- minmax
![[Pasted image 20241008181255.png]]
- stdev
![[Pasted image 20241008181330.png]]

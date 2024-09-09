# 1 Supervised VS Unsupervised Learning
- **Supervised:**
	- Pre-labeled data
	- Input and output dataset
	- Classification
	- Regression
- **Unsupervised:**
	- Unlabelled data
	- Input dataset only
	- Hidden features
	- Clustering
# 2 Algorithms Review
## 2.1 Supervised Learning
- **Classification:** 
	- KNN
	- Decision Tree
	- Random Forest
	- SVM
- **Regression:**
	- Logistic Regression
	- Linear Regression
### Case Review
#### Data Selection
- Student Information:
	- Gender
	- Age
- Academic records:
	- Study time
	- Attendance
- Final Outcome:
	- Grade
#### Data Preparation
- Missing Value: 
	- Most frequent value
- Categorical data: 
	- One-hot encoding (gender)
- Numerical data: 
	- Discuss standardization or normalization techniques for numerical features
- Example:
	- StandardScaler or MinMaxScaler for numerical features to ensure they are on a similar scale
> **StandardScaler** transforms the data by removing the mean and scaling to unit variance. It ensures that each feature has a mean of 0 and a standard deviation of 1.

> **MinMaxScaler** scales and translates each feature individually so that it is within a given range, typically between 0 and 1.


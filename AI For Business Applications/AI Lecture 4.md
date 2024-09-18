# 1 Supervised (VS Unsupervised Learning)
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
	- Association
## 1.1 Algorithms Review
### 1.1.1 Supervised Learning
- **Classification:** 
	- KNN
	- Decision Tree
	- Random Forest
	- SVM
- **Regression:**
	- Logistic Regression
	- Linear Regression
#### 1.1.1.1 Case Review
##### 1.1.1.1.1 Data Selection
- Student Information:
	- Gender
	- Age
- Academic records:
	- Study time
	- Attendance
- Final Outcome:
	- Grade
##### 1.1.1.1.2 Data Preparation
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

## 1.2 Confusion Matrix

|                          | Predict Malignant (Positive) | Predict Benign (Negative) |
| ------------------------ | ---------------------------- | ------------------------- |
| **Person has malignant** | True Positive                | False Negative            |
| **Person has benign**    | False Positive               | True Negative             |
# 2 Pattern Recognition
- missed it
- Unsupervised
## 2.1 Pattern Recognition Process
Gather data => Process it (clean out noise) => Examine for similarities => Group into segments => Analyze segments => Implement insights
# 3 Unsupervised Learning
## 3.1 Applications:
- Market segmentation
- Stock markets
- Natural language processing
- Computer vision
## 3.2 Common scenarios
- Data exploration
- Outlier detection
- Pattern Recognition
## 3.3 Strengths
- **Detects Hidden Patterns**: 
	- Identifies complex patterns that are not visible to the human eye, revealing powerful insights.
- **Business Impact**: 
	- Can uncover valuable information, such as fraud detection, customer behaviors, or other impactfull discoveries.
- **Versatile Output**: 
	- The results can be used to make informed decisions, automate processes, or create new business strategies.

## 3.4 Weaknesses
- **Complexity**: 
	- Harder to implement compared to supervised learning due to the lack of labeled data.
- **Costly**: 
	- It may require expert analysis or external resources to interpret and validate the results effectively.
- **Uncertain Usefulness**: 
	- Without labels, it's difficult to confirm the accuracy or relevance of the results, making validation more challenging.

# 4 K-Means
- Clustering algorithm
- Number of clusters is assumed beforehand
- Data segmented into K subgroups using various data attributes
- Number of clusters is fixed and data is classified based on that number
- Update the locations of the centroids with each iteration

> A **centroid** in clustering is the center of a group of data points. Think of it like the "average" location of all the points in that group. In a clustering algorithm like K-means, the goal is to organize data into groups, and each group has a centroid that represents the middle of the group. The algorithm tries to find the best centroids by adjusting them until they are as close as possible to all the points in their group.

![[Pasted image 20240909135443.png]]
# 5 Gaussian Mixture Models
- Type of probability density model where it is assumed that the data is governed by several component distributions
# 6 AP Model

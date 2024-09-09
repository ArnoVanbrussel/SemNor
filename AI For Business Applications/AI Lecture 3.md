# 1 Supervised vs Unsupervised Learning
- Supervised = Task driven (regression/classification)
> Supervised learning refers to the process of building a machine learning model that is based on **labeled training data**

- Unsupervised = Data driven (clustering)
> Unsupervised learning refers to the process of building a machine learning model **without relying on labeled training data**

![[Pasted image 20240902123053.png]]
# 2 Supervised Learning
## 2.1 Classification vs Regression
- **Classification:**
    - Predicts **categorical** outcomes.
    - Output: Discrete labels (e.g., "Spam" vs. "Not Spam").
    - Examples:
        - Email classification (Spam/Not Spam).
        - Disease diagnosis (Benign/Malignant).
    - Common Algorithms: KNN, Decision Trees, Logistic Regression, SVM, Neural Networks.
- **Regression:**
    - Predicts **continuous** numerical outcomes.
    - Output: Continuous values (e.g., House price: $250,000).
    - Examples:
        - Predicting house prices.
        - Estimating temperature or stock prices.
    - Common Algorithms: Linear Regression, Polynomial Regression, Support Vector Regression, Neural Networks.
## 2.2 KNN 
- Classifies data based on closest or neighboring training examples in the given region
- For a new input, the K nearest neighbours are calculated and the majority among the neighbouring data decides the classification for the new input
- A sample has **K** most similar samples in the feature space. If most of these samples belong to a certain category, then the sample also belongs to this category
- K generally equals 3 or 5
### 2.2.1 ML Steps
1. Load the data
2. Preprocess the data
3. Split the data into training and testing sets
4. Standardize the features
5. Train and predict using k-Nearest neighbours
6. Evaluate the model
7. Conduct and adjust
## 2.3 Regression
### Linear vs Logistic regression
- Linear:
	- The relationship between a dependent variable (target) and one or more independent variables (features) is linear
- Logistic:
	- Yes or No
Data Preprocessing Techniques

a. Handling Categorical Variables
Label Encoding: Converted categorical variables into numerical form to ensure compatibility with machine learning models.
One-Hot Encoding: Applied to categorical features to avoid ordinal misrepresentation.
Binary Encoding: Created a y_binary column where 'yes' was mapped to 1 and 'no' to 0, simplifying the classification problem.
b. Feature Scaling: MinMax Scaling: Normalized numerical data to a range of [0,1] to improve model convergence and performance.
c. Handling Imbalanced Data: SMOTE (Synthetic Minority Over-sampling Technique): Applied to balance the dataset by generating synthetic samples for the minority class.

Machine Learning Models: 
a. Random Forest Classifier
An ensemble learning technique that combines multiple decision trees.
Handles missing values well and prevents overfitting by using bootstrap sampling.
Used Gini impurity and entropy-based splits to improve decision-making.
b. XGBoost (Extreme Gradient Boosting) Classifier
A highly optimized gradient boosting algorithm known for its speed and efficiency.
Applied boosting techniques to correct weak predictions iteratively.
Hyperparameters such as learning rate, max depth, and estimators were fine-tuned.

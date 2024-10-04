# supervised-learning

1. Loading and Preprocessing

The breast cancer dataset can be loaded from sklearn.datasets. This dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.

Missing Values: The breast cancer dataset does not contain any missing values, so this step can be skipped.

Feature Scaling: Since the features are on different scales, we will standardize them using StandardScaler. This is important because algorithms like SVM and k-NN are sensitive to the scale of the data. Standardization helps in bringing all features to a similar scale, ensuring that the model training is not biased toward any specific feature.


1. Logistic Regression: Logistic Regression is a linear model used for binary classification. It estimates the probabilities using the logistic function, and is suitable for this dataset as it assumes a linear relationship between the features and the taget

2. Decision Tree Classifier: Decision Trees split the data into subsets based on feature values. They are interpretable and can capture non-linear relationships, making them suitable for this dataset.

3. Random Forest Classifier: Random Forest is an ensemble method that uses multiple decision trees to improve predictive accuracy and control overfitting. It is suitable due to its robustness and ability to handle complex interactions.

4. Support Vector Machine (SVM): SVM finds the hyperplane that best separates the classes in the feature space. It is effective for high-dimensional spaces, making it a good choice for this dataset.

5. k-Nearest Neighbors (k-NN): k-NN is a non-parametric method that classifies based on the majority class of the nearest neighbors. It can capture local structures in the data, making it suitable for this dataset.

# Model performance comparison

From the results, Random Forest and SVM perform well on this dataset due to their robustness and ability to capture complex relationships, while simpler models like Logistic Regression may perform slightly less effectively but are interpretable.

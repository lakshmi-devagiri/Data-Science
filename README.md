1. Linear Regression: Predicting Continuous Data
Linear regression is one of the simplest and most widely used algorithms in data science. It helps predict a continuous target variable based on one or more independent variables. For instance, predicting housing prices based on factors like area, number of rooms, or location. The algorithm assumes a linear relationship between inputs and the output, making it an essential tool for regression tasks.

________________________________________
2. Logistic Regression: Classification Simplified
Despite its name, logistic regression is a classification algorithm used for binary classification tasks (e.g., predicting whether an email is spam or not). By calculating the probability of a certain event happening, logistic regression helps categorize data into two classes using the logistic (sigmoid) function.
________________________________________
3. Decision Trees: Visualizing Decisions
Decision trees are a versatile tool for both classification and regression tasks. They split data into subsets based on the most significant attributes, with each node in the tree representing a feature and each branch representing a decision rule. It's an intuitive, easy-to-understand model that forms the basis of other powerful ensemble methods like Random Forests.
________________________________________
4. Random Forest: Ensemble Power
A Random Forest is an ensemble learning method that builds multiple decision trees and aggregates their results. By averaging predictions, Random Forests improve accuracy and reduce overfitting compared to individual decision trees. It's particularly effective for handling complex datasets with higher dimensionality.
________________________________________
5. Support Vector Machines (SVM): Maximizing Margin
Support Vector Machines are used for classification tasks where the goal is to find the best hyperplane that separates data points into distinct categories. By maximizing the margin between classes, SVM is particularly powerful for datasets that are not linearly separable, thanks to the use of kernel functions.
________________________________________
6. K-Nearest Neighbors (KNN): Classifying by Proximity
KNN is an intuitive algorithm that classifies a data point based on the majority class of its nearest neighbors. It’s ideal for scenarios where the relationship between features and labels is complex or unknown. The algorithm is simple to implement but can become computationally expensive for large datasets.
________________________________________
7. K-Means Clustering: Grouping Data into Clusters
K-Means is a popular clustering algorithm that partitions data into K clusters based on feature similarity. By minimizing intra-cluster variance, it groups similar data points together. It’s widely used in customer segmentation, anomaly detection, and image compression.
________________________________________
8. Principal Component Analysis (PCA): Dimensionality Reduction
PCA is a statistical technique used for reducing the number of variables in a dataset while preserving as much variability as possible. It transforms correlated features into a smaller number of uncorrelated variables (principal components), making it an essential tool for high-dimensional data.
________________________________________
9. Naive Bayes Classifier: Probabilistic Classification
Naive Bayes is a simple but effective probabilistic classifier that applies Bayes’ theorem with the “naive” assumption that features are conditionally independent. It’s fast, requires minimal data preparation, and is especially effective for text classification tasks, such as spam detection and sentiment analysis.

____________________________________________________________________________________________________________
**CNN:**
Convolution Neural NEtwork Including fallowing layers

**1.Convolution Opertaion**:Apply filters to extract features from the input.(EG: Image-->Filter--->O/p ---> Activation function)

Here Padding may Include :To prevent the loss of image padding is on top of the image

**Before Padding** :
n-f+1   n =Size of the Image, f= Size of the filter.

**After Padding**:
n+2p-f+1 p= p: The amount of padding added to the input.

Stride: to the step size with which the filter moves (or slides) over the input data.

**2.Max Pooling**: Down-sample the feature map to reduce its size and keep important features.

Three types of Pooling : Max-Pooling, Avg-Pooling, Min-Pooling

**3.Flattening:** Convert the pooled 2D feature map into a 1D vector.

**4.Fully Connected Layer (ANN)**: Pass the flattened vector through fully connected layers to make predictions.

**5.Output Layer:** Produce the final prediction, typically using softmax (for classification) or no activation (for regression).

Editied by Lakshmi




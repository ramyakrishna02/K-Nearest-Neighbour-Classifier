# K Nearest Neighbour Classifier
The k-nearest neighbors algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point.

The k-nearest neighbor classifier is a machine learning algorithm that assigns a new data point to the class that is most common among its k closest neighbors.
It is based on the idea that similar data points tend to have similar labels. 
The k-nearest neighbor classifier can be used for both classification and regression problems, but it is more commonly used for classification.

## Implementation
- Importing the required Libraries and reading the dataset
- Preforming EDA on the data
- Standardization of the data
- Splitting the data into the Train and the Test data
- Grid Search for Tuning the Algorithm
- Building the K-Nearest Neighbor Model
- Finding the accuracy

## Packages Used
- pandas
- numpy
- matplotlib.pyplot
- seaborn
- warnings
- from numpy import set_printoptions
- from sklearn.preprocessing import StandardScaler
- from sklearn.model_selection import train_test_split
- from sklearn.model_selection import GridSearchCV
- from sklearn.neighbors import KNeighborsClassifier
- from sklearn.metrics import accuracy_score, confusion_matrix, cross_val_score

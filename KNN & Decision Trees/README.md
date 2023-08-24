
#### Libraries: 
- Pandas
- NumPy
- os
- matplotlib 
- Seaborn
- sklearn

#### Methodologies: 
- One-Hot Encoding
- DecisionTree
- GridSearch Cross Validation
- Precision-Recall Curve
- DecisionTreeClassifier
- KNeighborsClassifier
- Accuracy Score

#### Datasets: 
- ["cell2celltrain" ](https://www.kaggle.com/datasets/jpacse/datasets-for-churn-telecom?resource=download)
We have compiled a comprehensive dataset from Cell2Cell Telecom company, which comprises of more than 10 million customers and entails an average monthly churn rate of 4%. More info here: [CELL2CELL: THE CHURN GAME](https://pdfcoffee.com/cell2cell-case-pdf-free.html)

- ["Airbnb NYC listings"](http://insideairbnb.com/new-york-city)
- **CANNOT DOWNLOAD DATA**. This report contains relevant information regarding New York City listings as of December 4th, 2021. For the purposes of predictive analysis, we have omitted any fields containing URLs, descriptions, names, neighborhood overviews, host information, and host locations.


#### Models:

_BuildADecisionTree_: I used "cell2celltrain," a dataset, to convert categorical features to one hot encoded values, split the data into training and test sets, and then fit a decision tree classifier to evaluate the accuracy of its predictions.

_ModelSelectionforKNN_: I also used a "cell2celltrain" dataset containing relevant features and labels with already preprocessed data. Grid search then identifies and fits a cross-validated optimal KNN classifier. The KNN Classifier is fit onto training data to make predictions on the test set, and then I used this data to display a confusion matrix and plot the precision-recall curve for the model.

_TranDTandKNN_: I used the Airbnb listings to convert categorical features into one-hot encoded values. The data is then split into training and test sets to later fit the data into Decision Tree classifiers and KNN classifiers to evaluate the accuracy.

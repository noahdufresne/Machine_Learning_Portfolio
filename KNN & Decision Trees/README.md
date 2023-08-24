# Predictive Analysis with Decision Trees and KNN Classifiers

This folder showcases predictive analysis using Decision Trees and K-Nearest Neighbors (KNN) classifiers. This project utilizes a range of libraries and methodologies to explore and model datasets, aiming to uncover valuable insights and predictions.

#### Libraries: 
- **Pandas**: For efficient data manipulation and analysis.
- **NumPy**: Enabling numerical computations and array operations.
- **os**: Facilitating interaction with the operating system for file handling.
- **matplotlib**: Creating insightful visualizations and plots.
- **Seaborn**: Enhancing the quality and aesthetics of visualizations.
- **sklearn**: Utilized for machine learning algorithms and evaluation metrics.

#### Methodologies: 
- **One-Hot Encoding**: Transforming categorical data into a suitable format for machine learning models.
- **GridSearch Cross Validation**:  Optimizing hyperparameters through grid search and cross-validation.
- **Precision-Recall Curve**: Visualizing precision and recall trade-offs in models.
- **DecisionTreeClassifier**: Utilizing decision tree classifiers for predictive analysis.
- **KNeighborsClassifier**: Leveraging KNN classifiers to analyze patterns in data.
- **Accuracy Score**: Quantifying the accuracy of models through evaluation metrics.

#### Datasets: 
- ["cell2celltrain"](https://www.kaggle.com/datasets/jpacse/datasets-for-churn-telecom?resource=download): 
We have compiled a comprehensive dataset from Cell2Cell Telecom company, which comprises of more than 10 million customers and entails an average monthly churn rate of 4%. More info here: [CELL2CELL: THE CHURN GAME](https://pdfcoffee.com/cell2cell-case-pdf-free.html)

- ["Airbnb NYC listings"](http://insideairbnb.com/new-york-city): **CANNOT DOWNLOAD DATA**. This report contains relevant information regarding New York City listings as of December 4th, 2021. For predictive analysis purposes, we have omitted any fields containing URLs, descriptions, names, neighborhood overviews, host information, and host locations.


#### Models:

_BuildADecisionTree_: I used "cell2celltrain," a dataset, to convert categorical features to one hot encoded values, split the data into training and test sets, and then fit a decision tree classifier to evaluate the accuracy of its predictions.

_ModelSelectionforKNN_: I also used "cell2celltrain" for this model. First, using grid search cross-validation to fit a KNN Classifier later onto training data to make predictions on the test set. Then, I used this data to display a confusion matrix and plot the precision-recall curve for the model.

_TranDTandKNN_: I used the Airbnb listings to convert categorical features into one-hot encoded values. The data is then split into training and test sets to later fit the data into Decision Tree classifiers and KNN classifiers to evaluate the accuracy.

Iris Classification uses the Logistic Regression model in Machine Learning to classify Iris flowers into three species: Setosa, Versicolor and Virginica, based on their Sepal length, Sepal width, Petal length and Petal width.
Iris dataset is loaded from Scikit-learn using load_iris() function. It contains 150 samples, 4 input features, 3 target species and 50 samples per species.
Logistic Regression estimates the probability of a input belonging to a particular class and assigns the class with the highest probability.
Logistic Regression is used since this is a classification problem. It can handle multiclass classification, and is simple, easy to understand and interpret.
The dataset is divided into training and testing sets using 80-20 split, 120 samples for training and 30 samples for testing. 
StandardScaler is used to scale the features before training the model.
The performance of the model is evaluated using the following evaluation metrics: Accuracy score, Confusion matrix and classification report.
Pair Plot and Heatmap are two visualizations created in this project.

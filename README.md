# Iris Species Model

-  The Iris Species Classification Model is a machine learning project designed to classify iris flowers into three different species based on their sepal and petal measurements.

## Dataset
-  The model utilizes the Iris dataset, a classic dataset in the field of machine learning and statistics. This dataset contains 150 samples of iris flowers, each with the following features:
    -  Sepal length
    -  Sepal width
    -  Petal length
    -  Petal width
 
## Model
- The Iris Species Classification Model is implemented using the K-Nearest Neighbors (KNN) algorithm, a simple yet effective method for classification tasks. Here’s a brief overview of how KNN works in this context:
-  ### Training:
      -  During training, the model stores the entire training dataset.
-  ### Prediction:
    -  To predict the species of a new iris flower, the model calculates the distance between the new data point and all other data points in the training set. It then selects the most common species among the nearest neighbors (K nearest data points).

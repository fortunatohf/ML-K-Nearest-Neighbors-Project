# ML-K-Nearest-Neighbors-Project

This Python project employs the K-Nearest Neighbor (KNN) algorithm to predict a "Target Class." While detailed dataset information is not provided here, the core of KNN involves leveraging features, scaling them appropriately, and making predictions based on a specified K value and the proximity between data points.

## Key Highlights

- **Data Scaling:** The project utilizes the `StandardScaler` from `sklearn.preprocessing` to transform and scale data points. Proper data scaling is essential for KNN to produce accurate results.

- **K-Nearest Neighbor Classifier:** The `KNeighborsClassifier` from `sklearn.neighbors` is used to fit the features with the chosen K value. This classifier determines a data point's class based on the classes of its K-nearest neighbors.

- **Optimizing K Value:** To enhance model performance, a custom function is implemented. This function evaluates K values ranging from 1 to 40, calculating error rates for each. Subsequently, the model is re-run with the K value that produces the lowest error rate, leading to improved predictions.

# AI-ML-INTERNSHIP
task-6
____________________________________________________________
🔹 1. Choose a classification dataset and normalize features

Pick a dataset like Iris or Wine from sklearn.datasets or a CSV file.

Split data into features (X) and labels (y).

Normalize features using StandardScaler or MinMaxScaler to ensure equal weight in distance calculations.

🔹 2. Use KNeighborsClassifier from sklearn
Import KNeighborsClassifier from sklearn.neighbors.

Split data into training and testing sets with train_test_split.

Create and train the model using knn = KNeighborsClassifier(n_neighbors=K) and knn.fit().

🔹 3. Experiment with different values of K
Try various K values (e.g., 1 to 20).

For each K, train the model and test its accuracy.

Plot K vs accuracy to identify the best performing value of K.

🔹 4. Evaluate model using accuracy, confusion matrix
Use predict() on the test data.

Calculate accuracy using accuracy_score.

Generate and visualize the confusion matrix with confusion_matrix and seaborn.heatmap.

🔹 5. Visualize decision boundaries
Reduce to two features for 2D plotting.

Create a mesh grid covering the feature space.

Predict over the grid and use contourf to plot regions.

Overlay training points with scatter.

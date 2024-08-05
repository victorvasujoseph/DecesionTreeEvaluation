# DecesionTreeEvaluation
Evaluate overfitting of decision trees in scikit-learn using the max_depth parameter


1.  Loading the Data: The dataset is loaded from the provided file path.
2.  Inspecting the Data: Display the first few rows and data types to understand the structure and identify categorical columns.
3.  One-Hot Encoding: Perform one-hot encoding for the smoker and outcome columns.
4.  Identifying Target Column: Determine the correct target column (outcome_Alive or outcome_Dead).
5.  Defining Features and Target: Include the age column along with the encoded smoker column as features, and set the target variable.
6.  Splitting Data: Split the data into training and test sets.
7.  Training Models: Train decision tree models with different max_depth values and track the accuracy on training and test sets.
8.  Plotting Results: Plot the accuracies to visualize overfitting and underfitting.

Two-Wheeler Loan Application Classification
Project Overview
This project involves determining whether a two-wheeler loan application will be accepted or rejected based on various features provided by the applicant and additional data from third-party sources. The dataset includes labeled training data and unlabeled test data.

Files
Assignment_Train.csv: Contains labeled data with the "Application Status" variable for training the model.
Assignment_Test.csv: Contains unlabeled data for which predictions need to be made.
Assignment_FeatureDictionary.xlsx: Provides details and descriptions of the variables present in the training and test datasets.
Approach
Data Exploration and Preprocessing:

Loaded and examined training and test datasets.
Utilized the feature dictionary to understand each variable.
Handled missing values, performed encoding for categorical variables, and applied necessary data transformations.
Feature Engineering:

Applied feature scaling and encoding techniques.
Engineered new features to enhance model performance.
Model Training:

Tested multiple models including Logistic Regression, Random Forest, and Gradient Boosting.
Tuned hyperparameters to select the best-performing model.
Model Evaluation:

Evaluated the model using Accuracy, Precision, Recall, and F1-Score on the training dataset.
Predictions:

Generated predictions for the test dataset.
Predictions are formatted with UID and the model's classification.

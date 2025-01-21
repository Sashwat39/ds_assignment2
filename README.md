# ds_assignment2
Steps in the Code
Data Loading and Preprocessing

The dataset is loaded into a pandas DataFrame.
The target column (Class) is identified, and the data is split into features (X) and the target variable (y).
Balancing the Data

SMOTE (Synthetic Minority Oversampling Technique) is used to balance the dataset by oversampling the minority class.
Sampling Techniques

Five different sampling techniques are applied:
Random Sampling (multiple sizes)
Stratified Sampling (based on the target class)
Machine Learning Models

Five models are trained using the sampled datasets:
Logistic Regression
Random Forest Classifier
Decision Tree Classifier
Naive Bayes
Support Vector Machine (SVM)
Evaluation

Models are evaluated using accuracy as the metric, and the results are stored in a table format for analysis.


Results
The script generates a table of results (results.csv) with the accuracy of each model for every sampling technique. This allows for a comparison of which sampling method performs best for each model.

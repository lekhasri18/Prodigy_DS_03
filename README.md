This Python script builds and evaluates a decision tree classifier to predict customer drug prescriptions based on demographic and behavioral data. The process involves the following steps:

Loading the Dataset: The dataset is read from a CSV file.

Preprocessing:

Categorical variables (Sex, BP, and Cholesterol) are encoded into numerical values using LabelEncoder.
Splitting Data:

The data is split into features (X) and the target variable (y).
The dataset is further divided into training and testing sets using train_test_split.
Training the Classifier:

A decision tree classifier is initialized and trained using the training data.
Making Predictions:

Predictions are made on the test data.
Evaluating the Model:

The model's performance is evaluated using accuracy score, classification report, and confusion matrix.
Visualizing the Decision Tree:

The trained decision tree is visualized using plot_tree from matplotlib.

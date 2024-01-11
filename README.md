Welcome to the Make Believe's repository!

The repository is organized as follows:
Within the Traditional Machine Learning Approach you can find all materials for that side of the project as well as the original datasets used.

Withing that folder, the python notebooks are organized in cronological order; notebook 1 corresponds to the first step in the project and so on.

Within the Datasets folder, you will find the corresponding data for the two datasets. The Celebrity Dataset folder contains the original dataset, the vectorized data within the Data Transformed folder and the csv file for the normalized data employed for training the models. The Fake News dataset folder contains the original dataset, the preprocessed dataset before feeding it to the TCT, vectorized data in the the Transformed Data folder. Finally, the normalized data used ofr the test is the test_data.csv.

In the Models folder, you will find a zip with all the models we developed. The naming convention they follow is [set of features used for the training]_[machine learning algorithm].sav.

The Models Performance folder contains a zip with the JSON dictionaries with information about the models like: name of the mode, type of ml model, features used for trainig, accuracy, precision, recall and f1 score for each of the tags, confusion matrix, etc, for both the test split of the training data and the final test.

The Results folder contains the exported csv files from the Results notebook. It contains aggregated results, results per set of features, results per algorithm and so on. 

Finally, the Visualizations folder contains the EDA distribution plots mentioned in the report and the visualizations for the Data Normalization Mitigation section.
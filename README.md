# Machine_Learning
Machine Learning project exploring dataset preprocessing, splitting train test set and model training, along with performance optimization using python. 


Dataset description : Dataset had 37 features and 1977 samples. It's a multiclass classification problem. Features were about a student's daily life and their stress anxiety level. The label was depression.

Data Preprocessing :  preprocessed the data to remove duplicate datas and missing values. Replaced missing values with most frequent value. we used one-hot encoding to convert categorical values to binary expressions.

Dataset splitting : splitted into 80/20 train test set. Both Supervised and Unsupervised learning model was chosen.  supervised learning : decision tree, logistic regression, NN, KNN. Upsupervised learning : K-mean clustering. NN performed the best.

Model training : 
Supervised : Decision Tree, Logistic Regression, K-Nearest Neighbours (KNN), Neural Network (NN). 
Unsupervised : K-Means Clustering

Performance Comparison : 
based on Accuracy, Precision, Recall, F1 score, ROC-AUC - Logistic Regression and Neural network achieved the highest accuracy of 95.19%. The Neural Network performed best overall, with an F1-score of 95.23% and ROC-AUC of 99.78%.

K-Means clustering identified three clusters corresponding mainly to mild, moderately severe and severe depression. Due to class imbalance, multiple evaluation metrics were considered alongside accuracy. 


# Kaggle Competition Submission - Binary Classification with a Bank Churn Dataset (KNN, XGBoost, RFC, Soft Voting)

## Team Members: Atul Parida

## Competition Overview:
- The purpose of the competition is to use binary classification to predict the likelihood of a bank customer churning (leaving the bank's services) given information about various indicators such as balance, estimated salary etc.

## Data:
- I have used the provided dataset of 112,023 rows and their corresponding labels.
- The dataset contains 10 columns of numerical features relating to account data and several text/categorical features.

## Approach:
- I began by doing minimal exploration and visualisation of the dataset to gain insights into the distribution of elements per class.
- As the dataset is relatively clean with no missing elements and very little collinearity observed between features, not much preprocessing needed to be conducted aside from feature normalization.
- Balancing was required as the churning class was underrepresented in the dataset, as a result of which I implemented SMOTE to rebalance the training sets.
- I implemented an ensemble of K-Nearest Neighbours, Random Forest Classifiers and XGBoost Classifiers through a Voting Classifier implementing soft voting, which achieved an accuracy of ```0.95``` on the test set.
- Model hyperparameters were tuned primarily using cross-validation.
- I evaluated the models based on area under the ROC curve as specified in the competition evaluation criteria, and chose to use ensembles.

## Code:
- You can find my code for this competition in the notebook titled ```submission_v1.ipynb``` associated with this repository.

## Results:
- The final submission achieved an accuracy of ```0.86057``` on the test set. This is due to possible overfitting of data caused by the use of SMOTE to balance the training set.
- I had a great learning experience participating in this competition, and it was a good opportunity to apply basic ML techniques to a public dataset.
- I would like to express my gratitude to the competition hosts for providing the dataset and the platform for this competition.

## How to Replicate My Submission:
- You can replicate my results by following the code available in the repository's .ipynb notebook.


## Acknowledgements:
- We would like to thank Kaggle for providing the dataset and the platform for this competition.

Feel free to reach out to us if you have any questions or would like to collaborate on future projects. Thank you for reviewing our submission!

Competition Link: [Binary Classification with a Bank Churn Dataset](https://www.kaggle.com/competitions/playground-series-s4e1/overview)

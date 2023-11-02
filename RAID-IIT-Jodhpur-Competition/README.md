# Kaggle Competition Submission - RAID IIT Jodhpur Competition (Scikit-Learn)

## Team Members: Atul Parida

## Competition Overview:
- The purpose of the competition is to make you explore ML algorithms so please use only Machine Learning to crack the pattern in the given dataset.

## Data:
- I have used the provided dataset of 4,200 rows and their corresponding labels.
- The dataset contains 26 columns of numerical features with a label belonging to one of five different classes.

## Approach:
- I began by doing minimal exploration and visualisation of the dataset to gain insights into the distribution of elements per class.
- As the dataset is relatively clean with no missing elements and very little collinearity observed between features, not much preprocessing needed to be conducted aside from feature normalization.
- I experimented with various machine learning algorithms and classification models, including but not limited to Logistic Regression, Random Forest and GaussianNB.
- Model hyperparameters were tuned primarily using cross-validation.
- I evaluated the models based on F1 score as specified in the competition evaluation criteria, and chose to use ensembles.

## Code:
- You can find my code for this competition in the notebook titled ```submission_v4.ipynb``` associated with this repository.

## Models:
- I have trained multiple models and structures and fine-tuned them for multiclass classification accuracy.
- Initially using only a Naive Bayes model, I used a stacking classifier comprised of a Random Forests Classifier, a Naive Bayes classifier, a Logistic Regression classifier and a Support Vector Classifier for the final submission.

## Results:
- The final submission achieved an accuracy of ```0.8900``` on the test set.
- I had a great learning experience participating in this competition, and it was a good opportunity to apply basic ML techniques to a public dataset.
- I would like to express my gratitude to IIT Jodhpur's Artificial Intelligence and Data Science Society and Kaggle for hosting this competition.

## How to Replicate My Submission:
- You can replicate my results by following the code available in the repository's .ipynb notebook.


## Acknowledgements:
- We would like to thank Kaggle and the competition hosts for providing the dataset and the platform for this competition.

Feel free to reach out to us if you have any questions or would like to collaborate on future projects. Thank you for reviewing our submission!

Competition Link: [Week of ML Kaggle Competition](https://www.kaggle.com/competitions/week-of-ml-kaggle-competition)

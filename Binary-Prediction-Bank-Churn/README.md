# Kaggle Competition Submission - Binary Prediction of Smoker Status using Bio-Signals (TensorFlow, Keras)

## Team Members: Atul Parida

## Competition Overview:
- The purpose of the competition is to use binary classification to predict a patient's smoking status given information about various other health indicators.

## Data:
- I have used the provided dataset of 4,200 rows and their corresponding labels.
- The dataset contains 23 columns of numerical features relating to bio-signals.

## Approach:
- I began by doing minimal exploration and visualisation of the dataset to gain insights into the distribution of elements per class.
- As the dataset is relatively clean with no missing elements and very little collinearity observed between features, not much preprocessing needed to be conducted aside from feature normalization.
- I implemented a deep learning model using TensorFlow and Keras, which achieved an accuracy of ```0.8395``` on the test set.
- Model hyperparameters were tuned primarily using cross-validation.
- I evaluated the models based on F1 score as specified in the competition evaluation criteria, and chose to use ensembles.

## Code:
- You can find my code for this competition in the notebook titled ```smoker_bio_pred_v1.ipynb``` associated with this repository.

## Results:
- The final submission achieved an accuracy of ```0.83568``` on the test set.
- I had a great learning experience participating in this competition, and it was a good opportunity to apply basic ML techniques to a public dataset.
- I would like to express my gratitude to the competition hosts for providing the dataset and the platform for this competition.

## How to Replicate My Submission:
- You can replicate my results by following the code available in the repository's .ipynb notebook.


## Acknowledgements:
- We would like to thank Kaggle for providing the dataset and the platform for this competition.

Feel free to reach out to us if you have any questions or would like to collaborate on future projects. Thank you for reviewing our submission!

Competition Link: [Binary Prediction of Smoker Status using Bio-Signals](https://www.kaggle.com/competitions/playground-series-s3e24/overview)

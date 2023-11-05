# Kaggle Competition Submission - Halloween Monster Classification 2023 (Tensorflow)

## Team Members: Atul Parida

## Competition Overview:
- A just-for-fun competition using completely fabricated data on classic Halloween monsters. Try to build the model that most accurately classifies monsters as Ghost, Mummy, Vampire, Witch, or Zombie. 

## Data:
- I have used the provided training dataset of 37497 rows and their corresponding labels.
- The dataset contains 6 columns of features, with one categorical feature and five numerical features, and a label belonging to one of five different classes.

## Approach:
- I began by doing minimal exploration and visualisation of the dataset to gain insights into the distribution of elements per class.
- As the dataset is relatively clean with no missing elements and very little collinearity observed between features, not much preprocessing needed to be conducted aside from feature normalization.
- I experimented with various machine learning algorithms and classification models, including but not limited to Logistic Regression, Random Forest and GaussianNB. I chose deep learning models as they were able to achieve the highest accuracy.
- Model hyperparameters were tuned primarily using cross-validation.
- I evaluated the models based on classification accuracy as specified in the competition evaluation criteria.

## Code:
- You can find my code for this competition in the notebook titled ```halloween-2023.ipynb``` associated with this repository.

## Models:
- I have trained multiple models and structures and fine-tuned them for multiclass classification accuracy.
- Initially using only a Random Forests model, I used a Tensorflow deep learning model with two layers of 128 and 64 neurons respectively, with a dropout layer in between along with one hidden layer.

## Results:
- The final submission achieved an accuracy of ```0.8912``` on the test set.
- I had a great learning experience participating in this competition, and it was a good opportunity to apply deep learning techniques to a public dataset.
- I would like to express my gratitude to Adam Gilbert and Kaggle for hosting this competition.

## How to Replicate My Submission:
- You can replicate my results by following the code available in the repository's .ipynb notebook.


## Acknowledgements:
- We would like to thank Kaggle and the competition hosts for providing the dataset and the platform for this competition.

Feel free to reach out to us if you have any questions or would like to collaborate on future projects. Thank you for reviewing our submission!

Competition Link: [Halloween Monster Classification 2023](https://www.kaggle.com/competitions/halloween-monster-classification-2023/)

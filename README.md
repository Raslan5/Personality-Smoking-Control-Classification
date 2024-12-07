## Personality-Smoking-Control-Classification

This project aims to classify the ability of user to control over him/herself to smoke or not depending on personal traits. Using the manipulated dataset (personality_traits.csv) which its original is (personality_individual_characteristics.csv)
and Jupyter Notebooks (Personality Smoking Control Classification.ipynb (1), Personality + Characteristics Smoking Control Classification.ipynb (2)), analyzing trends, preprocessing data, and building predictive neural network feed-forward models.
We aimed as well to check if characteristics other than personal traits could evolve or not the accuracy of the model.

## Dataset Reference
 `rb
  https://scholarworks.aub.edu.lb/handle/10938/24277
 `
## Team Members
- `Ahmad Bassam El Bizri`
- `Mohamad Raslan`

## Files
- `personality_individual_characteristics.csv`: The original dataset that was sampled.
- `personality_traits.csv`: The manipulated from the original dataset that is used for training and testing the neural network model.
- `Personality Smoking Control Classification.ipynb`: The Jupyter Notebook that used the dataset to predict and train the model for the test dataset using only the personal traits.
- `Personality + Characteristics Smoking Control Classification.ipynb`: The Jupyter Notebook that used the dataset to predict and train the model for the test dataset using both personal traits in addition to other characteristics.
- `README.md`: Detailed guide file for the project.

 ## Download the files
 ```rb 
  git clone https://github.com/Raslan5/Personality-Smoking-Control-Classification.git
 ```
 ## Requirements
 Install please the following libraries:
  - `pandas`
  - `numpy`
  - `scikit-learn`
  - `torch`
  - `tensorflow`
 ## Usage
 After downloading the required libraries, run the code by opening the Jupyter Notebook in your favorite IDE, start by "Personality Smoking Control Classification.ipynb" then 
 "Personality + Characteristics Smoking Control Classification.ipynb" to compare the accuracy differences due to adding extra features to the model.

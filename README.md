# Autism_Prediction_using_classification_models
# Machine Learning Project: Autism Detection using Classification Models

Welcome to the "Autism Detection using Classification Models" project! This repository contains the code and resources for building and evaluating machine learning models to predict whether an individual has autism based on various features, including age, gender, jaundice, and the results of 10 autism-related tests.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Models Used](#models-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)

## Project Overview

The goal of this project is to develop and compare the performance of different classification models in predicting whether an individual has autism based on a set of features. Autism spectrum disorder (ASD) is a complex neurodevelopmental condition that affects social interaction, communication, and behavior. Early diagnosis and intervention can significantly improve outcomes for individuals with ASD.

We have explored three classification models: Logistic Regression, Decision Tree, and Random Forest. These models are trained on a labeled dataset containing information about individuals' age, gender, jaundice history, the results of 10 autism-related tests, and their class label (autism or not).

## Dataset

The dataset used in this project consists of the following features:

- Age
- Gender
- Jaundice history
- Results of 10 autism-related tests

The target variable is:

- Class label (1 for autism, 0 for non-autism)

The dataset has been preprocessed and split into training and testing sets. It is stored in the `data` directory within the repository.

## Models Used

We have implemented the following classification models:

1. **Logistic Regression**: A linear regression model that predicts the probability of an individual having autism.

2. **Decision Tree**: A tree-based model that makes decisions based on a series of questions to classify individuals.

3. **Random Forest**: An ensemble model that consists of multiple decision trees and provides more robust predictions.

## Getting Started

To get started with this project, follow these steps:

1. Clone this repository to your local machine using:
   ```
   git clone https://github.com/Abhay14tyagi/Autism_Prediction_using_classification_models.git
   ```

2. Navigate to the project directory:
   ```
   cd Autism_Prediction_using_classification_models
   ```

3. Install the required dependencies using:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Explore the dataset: You can find the preprocessed dataset in the `data` directory. Use Jupyter Notebook or any preferred IDE to open and examine the dataset.

2. Model Training: The models are implemented  Python file 'autism-prediction.ipynb'

3. Model Evaluation: Use the evaluation script 'autism-prediction.ipynb' to assess the performance of the trained models on the test dataset.
## Contributing

Contributions to this project are welcome! If you have suggestions for improvements or new features, feel free to submit a pull request.

We hope this README provides a comprehensive understanding of the project. Feel free to reach out if you have any questions or feedback. Happy coding!

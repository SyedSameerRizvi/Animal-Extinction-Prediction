# Extinct Species Prediction 

This project is focused on building a machine learning model to predict the risk of species extinction. The model leverages various features (e.g., habitat, population size, human interaction) to classify species as endangered or not. It includes data preprocessing, model training, evaluation, and making custom predictions.

**You can find the Dataset here:** [Animal Extinction Dataset](https://www.kaggle.com/datasets/umeradnaan/extinction-of-a-species-data/data)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Model Overview](#model-overview)
- [Results](#results)
- [Conclusion](#conclusion)
- [Contributing](#contributing)

## Installation

To run this project locally, you need to have the following dependencies installed:
```bash
pip install -r requirements.txt
```

## Usage
- Preprocess the dataset and split it into training and testing sets.
- Train the model by running the Jupyter Notebook extinct_prediction.ipynb.
- Evaluate the model's performance using accuracy scores, confusion matrix, and other evaluation metrics.
- Use the custom prediction function to make predictions on new data.

## Model Overview
The machine learning model is trained using `Random Forest Classifier` and tuned to predict whether a species is at risk of extinction. It utilizes classification techniques and standard evaluation metrics like confusion matrix, precision, recall, and accuracy scores.

## Results
The model achieved an accuracy score of 100% on the test set. Below is a confusion matrix that summarizes the performance:

![image](https://github.com/user-attachments/assets/7da9de6b-5247-4f44-97c5-7ebafe0e9831)


## Conclusion
The model performed well with the given dataset, showing good predictive capabilities in distinguishing endangered species from others.

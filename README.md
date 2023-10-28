# Gender Prediction Model

This repository contains a Python-based gender prediction model that uses Support Vector Machine (SVM) and TF-IDF (Term Frequency-Inverse Document Frequency) features to predict the gender of individuals based on their names. The model has achieved an accuracy of 80.28% on a larger and more diverse dataset.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Data](#data)
- [Model Training](#model-training)
- [Interactive Prediction](#interactive-prediction)


## Introduction

Gender prediction based on names is a common task in natural language processing and machine learning. This project demonstrates the process of building and training a gender prediction model using a Support Vector Machine (SVM) classifier and TF-IDF feature extraction.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/your-username/gender-prediction-model.git
   ```

2. Install the required dependencies:

   ```bash
   pip install pandas scikit-learn
   ```

3. Download the dataset from the following URL: [Gender by Name Dataset](https://archive.ics.uci.edu/dataset/591/gender+by+name). Save it as 'larger_dataset.csv' in the project directory.

4. Replace 'larger_dataset.csv' in the code with your dataset path.

## Usage

Once you have set up the project, you can use it to predict gender based on names. To use the model:

1. Run the `gender_prediction.py` script to train the SVM classifier and evaluate its accuracy.

2. After training, you can interactively predict the gender of a name by running the script and providing a name as input.

## Data

The model uses a dataset of names and their associated genders. The dataset was obtained from the following source: [Gender by Name Dataset](https://archive.ics.uci.edu/dataset/591/gender+by+name).

Ensure that the dataset is in CSV format with 'Name' and 'Gender' columns.

## Model Training

The SVM classifier is trained using the provided dataset and TF-IDF features. You can customize the model's hyperparameters, such as the choice of kernel and regularization parameter, by modifying the code in `gender_prediction.py`.

## Interactive Prediction

The model allows for interactive gender prediction based on user input. Run the script, and when prompted, enter a name to get a gender prediction. Enter 'exit' to quit the interactive prediction mode.

## Contributing

Contributions to this project are welcome! You can contribute by:

Adding new features to improve the model's accuracy.
Enhancing the dataset or using a more diverse dataset for training.
Fixing bugs or improving code quality.


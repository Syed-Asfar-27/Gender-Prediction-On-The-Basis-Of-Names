# Gender Prediction Model

This repository contains a Python-based gender prediction model that uses Support Vector Machine (SVM) and TF-IDF (Term Frequency-Inverse Document Frequency) features to predict the gender of individuals based on their names. The model has achieved an accuracy of 80.28% on a larger and more diverse dataset.

## Table of Contents

- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Model Training](#model-training)
- [Interactive Prediction](#interactive-prediction)


## Introduction

Gender prediction based on names is a common task in natural language processing and machine learning. This project demonstrates the process of building and training a gender prediction model using a Support Vector Machine (SVM) classifier and TF-IDF feature extraction.

## Getting Started

To get started with this project, follow these steps:

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/Syed-Asfar-27/Gender-Prediction-On-The-Basis-Of-Names.git
   ```

2. Install the required dependencies:

   ```bash
   pip install pandas scikit-learn
   ```

3. Download the dataset from the following URL: [Gender by Name Dataset](https://archive.ics.uci.edu/dataset/591/gender+by+name). Save it as 'name_gender_dataset.csv' in the project directory.

4. Replace 'name_gender_dataset.csv' in the code with your dataset path.

## Usage

Once you have set up the project, you can use it to predict gender based on names. To use the model:

1. Run the scripts to train the SVM classifier and evaluate its accuracy.

2. After training, you can interactively predict the gender of a name by running the script and providing a name as input.

## Model Training

The SVM classifier is trained using the provided dataset and TF-IDF features. You can customize the model's hyperparameters, such as the choice of kernel and regularization parameter, by modifying the code.

## Interactive Prediction

The model allows for interactive gender prediction based on user input. Run the script, and when prompted, enter a name to get a gender prediction. Enter 'exit' to quit the interactive prediction mode.


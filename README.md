# Password Strength Prediction using Machine Learning

This repository contains the code and resources for a machine learning project that predicts the strength of passwords based on various features extracted from the password text. The project uses a combination of text processing techniques, feature extraction, and ensemble learning algorithms to classify passwords into weak, medium, or strong categories.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

In today's digital age, passwords play a crucial role in securing our online identities. This project aims to provide users with a tool that helps them assess the strength of their passwords and make informed decisions about their online security. By leveraging machine learning techniques, the project provides real-time predictions and educates users on password best practices.

## Features

- Text processing and feature extraction using TF-IDF (Term Frequency-Inverse Document Frequency).
- Ensemble learning models, including Random Forest Classifier and Gradient Boosting Classifier, for accurate strength prediction.
- User-friendly UI for password input and real-time strength assessment.
- Educational resources on password security and best practices.

## Dataset

The dataset used for training and evaluating the models consists of a collection of passwords along with their corresponding strength labels. The dataset was obtained from [kaggle](https://www.kaggle.com/datasets/bhavikbb/password-strength-classifier-dataset) and was preprocessed to remove duplicates and irrelevant entries.

## Installation

1. Clone this repository: `git clone https://github.com/Suket-Shubhankar/Password-Strength-Classifier.git`
2. Navigate to the project directory: `cd password-strength-prediction`
3. Install the required dependencies: `pip install -r requirements.txt`

## Usage

1. Run the code cells in this notebook to train the models and preprocess the data.
2. Open the `Password_strength.ipynb` notebook to access the user interface for real-time password strength assessment.

## Results

The trained models demonstrate strong predictive capabilities, accurately classifying passwords into different strength categories. You can input passwords and receive instant strength classification from the three models used.

## Contributing

Contributions to this project are welcome! If you have ideas for improvements or new features, feel free to open an issue or submit a pull request.

---

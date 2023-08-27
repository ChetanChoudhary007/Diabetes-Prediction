
---

# Diabetes Prediction System

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTBwEu-pYxjO9zOG9HP-lc-lfokB8XQjhaX8w&usqp=CAU" alt="Diabetes Prediction" width="500" height="268">

This project focuses on predicting the likelihood of diabetes in individuals using machine learning techniques. It utilizes the Support Vector Machine (SVM) algorithm to classify the input data as either indicating diabetes (1) or not (0).

## Table of Contents

- [Introduction](#introduction)
- [Dependencies](#dependencies)
- [Dataset](#dataset)
- [Data Preprocessing](#data-preprocessing)
- [Model Training](#model-training)
- [Making Predictions](#making-predictions)
- [Usage](#usage)
- [Contributions](#contributions)
- [License](#license)

## Introduction

The aim of this project is to predict the presence or absence of diabetes in individuals based on various health-related features. The Support Vector Machine (SVM) algorithm is used for classification, and the dataset is preprocessed to ensure optimal model performance.

## Dependencies

This project requires the following Python libraries:

- `numpy`
- `pandas`
- `scikit-learn`

You can install these dependencies using the following command:

```bash
pip install numpy pandas scikit-learn
```

## Dataset

The dataset used for this project can be found at `/content/diabetes.csv`. It contains various features related to health and diabetes outcomes for individuals.

## Data Preprocessing

- The dataset is loaded using the `pd.read_csv()` function.
- Null values are checked using `dia_dataset.isnull().sum()`.
- Features and labels are separated. The features are standardized using `StandardScaler()`.

## Model Training

- The SVM classifier with a linear kernel is used for training.
- The model is trained using the `classifier.fit(X_train, y_train)` function.

## Making Predictions

- Predictions are made on both the training and testing datasets.
- User input data can also be provided to the model for prediction.

## Usage

1. Install the required dependencies using the provided command.
2. Ensure that the dataset is available at `/content/diabetes.csv`.
3. Run the code provided in your preferred Python environment.
4. The model's accuracy on both training and testing data will be displayed.
5. You can input data for prediction and receive a result indicating the likelihood of diabetes.

## Contributions

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.

## License
ect is licensed under the [MIT License](LICENSE).

---

# Breast Cancer Classifier

## Overview
The Breast Cancer Classifier is a machine learning model designed to predict whether breast cancer is benign or malignant based on various input features. The model is trained using Logistic Regression and achieves over 90% accuracy on both the training and testing datasets.

## Features
The model uses the following input features from the Wisconsin Breast Cancer Dataset:

- Mean radius
- Mean texture
- Mean perimeter
- Mean area
- Mean smoothness
- Other statistical measures related to cell nuclei present in breast cancer biopsies

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/18Aswin/Breast-Cancer-Classifier.git
    cd breast-cancer-classifier
    ```
2. Set up a virtual environment (optional but recommended):

3. Install the required dependencies:

## Project Structure

```
breast-cancer-classifier/
├── data/                 # Directory to store dataset
│   └── breast_cancer.csv
├── models/               # Directory to save trained model
│   └── breastcancer_predictor.sav
├── ipynb/                  # Source code for the project

```

## Requirements

- Python 3.11
- Pandas
- NumPy
- Scikit-learn
- Jupyter (optional, for running notebooks)

Install all dependencies using:

## Performance

The Logistic Regression model achieves over 90% accuracy on both the training and testing datasets, making it a reliable tool for predicting the nature of breast cancer based on the input features.

## Contributing
If you wish to contribute to this project, please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature-branch`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## Acknowledgments

- The Wisconsin Breast Cancer Dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+(Diagnostic)).
- Scikit-learn library for providing the tools to build the model.

## About

Breast Cancer Classifier is developed and maintained by Aswin A Nair. Feel free to reach out with any questions or feedback.

---

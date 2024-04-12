# Breast-cancer-detection-using-Machine-learning-Models

## Overview
This repository contains the code and analysis for a machine learning project focused on the detection of breast cancer using fine needle aspirate (FNA) images. The project explores the performance of various machine learning models in distinguishing between benign and malignant cases based on characteristics extracted from cell nuclei.

## Dataset
The dataset used in this project originates from Kaggle and the [UCI Machine Learning Repository](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data). It comprises characteristics of cell nuclei extracted from fine needle aspirate (FNA) images. The dataset used in this project consists of ten real-valued features per cell nucleus, including radius, texture, perimeter, area, smoothness, compactness, concavity, concave points, symmetry, and fractal dimension. It comprises a mix of benign and malignant cases, with a total of 569 instances.

## Models Explored
1. **Logistic Regression**: A linear model used for binary classification, known for its simplicity and interpretability.
2. **Random Forest**: An ensemble learning method that constructs multiple decision trees during training and outputs the mode of the classes (classification) or the mean prediction (regression) of the individual trees.
3. **XGBoost**: An optimized gradient boosting library that provides parallel tree boosting for highly efficient and accurate machine learning.

## Results
After thorough hyperparameter tuning and cross-validation, the models achieved the following performance metrics:

| Model               | Accuracy | Precision | Recall | F1-score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 97.37%   | 95.45%    | 97.67% | 96.55%   |
| Random Forest       | 96.49%   | 97.56%    | 93.02% | 95.24%   |
| XGBoost             | 96.49%   | 97.56%    | 93.02% | 95.24%   |

### Key Observations:
- **Logistic Regression**: Demonstrated the highest recall, making it suitable for scenarios prioritizing sensitivity in detecting malignancy.
- **Random Forest and XGBoost**: Exhibited higher precision, indicating proficiency in correctly classifying positive cases.

## Usage
- Clone the repository:
   ```bash
   git clone https://github.com/your_username/breast-cancer-detection.git
   ```
## Contributors
- [Ashaduzzaman Sarker](https://github.com/ashaduzzaman-sarker)

## Acknowledgments
- This project is based on the breast cancer dataset from Kaggle and the [UCI Machine Learning Repository](https://www.kaggle.com/uciml/breast-cancer-wisconsin-data).

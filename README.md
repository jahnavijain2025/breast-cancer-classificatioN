# Breast Cancer Classification Using Machine Learning

## Project Overview
This project uses machine learning to classify breast tumors as benign or malignant based on numerical measurements computed from cell images.

Two beginner-friendly classification algorithms, Decision Tree and K-Nearest Neighbors (KNN), are trained and evaluated using accuracy scores and confusion matrices.

## Objective
The objective is to understand the basic machine learning workflow, including data preparation, model training, prediction, evaluation, and comparison.

## Dataset
- **Name:** Wisconsin Diagnostic Breast Cancer (WDBC)
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- **Samples:** 569
- **Features:** 30 numerical features
- **Target:** Benign or Malignant

The notebook uses the dataset included in scikit-learn, so no manual CSV download is required.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Installation and Setup

Install the required libraries using:

```bash
python -m pip install pandas numpy matplotlib scikit-learn
```

Open `breast_cancer_classification.ipynb` in Jupyter Notebook or JupyterLab and run all cells from top to bottom.

## Methodology
1. Loaded the Wisconsin Diagnostic Breast Cancer dataset.
2. Inspected the dataset and checked for missing values.
3. Separated the features and target variable.
4. Split the data into 80% training data and 20% testing data.
5. Trained Decision Tree and K-Nearest Neighbors classifiers.
6. Evaluated both models using accuracy scores and confusion matrices.

The train-test split used `random_state=42` and stratification to preserve the class proportions.

## Results

The models were evaluated on the same test set of 114 samples.

| Model | Accuracy |
|---|---:|
| Decision Tree | 92.98% |
| K-Nearest Neighbors (KNN) | 95.61% |

KNN achieved higher accuracy on this test set, outperforming the Decision Tree by approximately 2.63 percentage points.

## Conclusion
This project demonstrates how to prepare numerical data, train classification models, and evaluate their predictions using accuracy and confusion matrices.

I learned how to inspect data for missing values, separate features and targets, split data into training and testing sets, and compare two machine learning algorithms. I also learned that standardization is important for distance-based algorithms such as KNN because features can have different numerical scales.

Based on the test results, KNN performed better than the Decision Tree model in this experiment. However, these results are based on a single train-test split and may vary with different data splits or model settings.

## Disclaimer
This project is for educational purposes only. It is not intended for medical diagnosis or clinical decision-making.

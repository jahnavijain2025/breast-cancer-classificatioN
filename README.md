# Breast Cancer Classification Using Machine Learning

## Project Overview
This project uses machine learning to classify breast tumors as benign or malignant based on numerical measurements computed from cell images.

Two beginner-friendly classification algorithms, Decision Tree and K-Nearest Neighbors (KNN), are trained and evaluated using accuracy scores and confusion matrices.

## Objective
To understand the basic machine learning workflow, including data preparation, model training, prediction, and evaluation.

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

Open `breast_cancer_classification.ipynb` in Jupyter Notebook or JupyterLab and run the cells from top to bottom.

## Results

| Model | Accuracy |
|---|---:|
| Decision Tree | 92.98% |
| K-Nearest Neighbors (KNN) | 95.61% |

KNN achieved higher accuracy on the test set used in this experiment.

## Conclusion
This project demonstrates how to prepare numerical data, train two classification models, and evaluate their predictions using accuracy and confusion matrices. It also illustrates why standardization is useful for distance-based models such as KNN.

## Disclaimer
This project is for educational purposes only. It is not intended for medical diagnosis or clinical decision-making.
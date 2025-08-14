# CodeAlpha_IrisFlowerClassification

Iris Flower Classification project for CodeAlpha internship using Python, Pandas, Scikit-learn.

## Overview
Classifies Iris flowers into Setosa, Versicolor, Virginica based on sepal and petal measurements.

## Files
- `iris_classification.ipynb`: Main code with EDA, preprocessing, model training, and predictions.
- `iris_classifier.pkl`: Saved Logistic Regression model.
- `scaler.pkl`: Saved StandardScaler for feature scaling.
- `plots/`: Visualizations (pairplot, countplot, confusion matrix).

## How to Run
1. Clone: `git clone https://github.com/your-username/CodeAlpha_IrisFlowerClassification.git`
2. Install: `pip install pandas scikit-learn matplotlib seaborn joblib`
3. Run `iris_classification.ipynb` in Colab/Jupyter.

## Results
- Accuracy: ~95-98%.
- Sample Prediction: `[5.1, 3.5, 1.4, 0.2]` → Setosa.
- Visualizations: See `plots/`.

## Screenshots
![Species Distribution](plots/countplot.png)
![Feature Relationships](plots/pairplot.png)
![Confusion Matrix](plots/confusion_matrix.png)

## Acknowledgments
Thanks to CodeAlpha for this opportunity!

# Logistic Regression Classification: Breast Cancer Dataset

## Objective
Build a binary classifier using Logistic Regression to predict whether a tumor is malignant or benign.

## Tools
- Python
- Scikit-learn
- Pandas
- Matplotlib

## Steps
1. Load Breast Cancer Wisconsin dataset from sklearn.
2. Split into training and testing sets (80/20).
3. Standardize features using StandardScaler.
4. Fit a Logistic Regression model.
5. Evaluate using:
   - Confusion Matrix
   - Precision & Recall
   - ROC-AUC Curve
6. Visualize performance with a ROC curve.

## Results
- ROC-AUC Score: ~0.99
- High precision and recall indicate the model is performing well.

## Dataset Info
- 30 features
- 2 classes: Malignant (0), Benign (1)

## Run the Notebook
```bash
jupyter notebook classification_logistic_regression.ipynb
```
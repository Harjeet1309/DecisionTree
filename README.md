#Decision Trees & Random Forests

## Dataset

- **File**: `heart.csv`
- **Source**: Heart Disease Dataset
- **Target (Classification)**: `condition` (1 = disease, 0 = no disease)
- **Target (Regression)**: `chol` (serum cholesterol level)

---

## Tasks Covered

### ✅ Classification
- Decision Tree Classifier (Full Depth)
- Pruned Decision Tree (max depth = 4)
- Random Forest Classifier
- Accuracy, Confusion Matrix, Cross-Validation
- Feature Importance Visualization

### ✅ Regression
- Decision Tree Regressor
- Random Forest Regressor
- Metrics: MAE, MSE, R²
- Feature Importance Visualization

---

## Tools Used
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn`

---

## Results

| Task              | Model                  | Metric        | Score     |
|-------------------|------------------------|---------------|-----------|
| Classification    | Pruned Decision Tree   | Accuracy      | ~83%      |
| Classification    | Random Forest          | Accuracy      | ~87%      |
| Classification    | Random Forest          | Cross-Validation | ~85%   |
| Regression        | Decision Tree Regressor| R² Score       | ~0.12     |
| Regression        | Random Forest Regressor| R² Score       | ~0.41     |

---

## Insights
- Random Forest consistently outperforms a single Decision Tree in both tasks.
- Important features for predicting heart disease: `cp`, `thalach`, `oldpeak`.
- Important features for predicting cholesterol: `age`, `trestbps`, `oldpeak`.

---

## Visuals

- Decision Tree Diagram (Full + Pruned)
- Confusion Matrix
- Feature Importances (Bar Charts)



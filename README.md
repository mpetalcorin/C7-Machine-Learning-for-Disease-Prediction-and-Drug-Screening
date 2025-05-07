# Machine-Learning-for-Disease-Prediction-and-Drug-Screening
A collection of Jupyter notebooks and Python scripts showcasing advanced machine learning techniques for disease prediction, cancer metabolic drug screening, k-fold cross-validation, and handling imbalanced datasets using SMOTE and SVM.
# Advanced Machine Learning for Disease Prediction and Regression
This repository provides advanced machine learning techniques in disease prediction, regression modeling, performance evaluation, and handling imbalanced datasets.
## Included Modules

### 1. Advanced Performance Evaluation
- **Goal:** Create and evaluate an imbalanced disease prediction dataset.
- **Steps:**
  - Simulate an imbalanced classification dataset.
  - Apply stratified sampling (`train_test_split`).
  - Use SMOTE to oversample minority classes.
  - Explain VC dimension and model complexity (e.g., Logistic Regression vs. SVM).
  - Perform stratified K-fold cross-validation.
  - Compare performance before and after oversampling.
**Tools:** `scikit-learn`, `imbalanced-learn`, `matplotlib`
### 2. Cancer Metabolic Disease Screening
- **Goal:** Perform regression modeling on cancer metabolic disease data to predict IC50 values.
- **Approach:** Use feature selection and machine learning models like Decision Trees, Random Forest, XGBoost, and ElasticNet to evaluate predictive performance.
### 3. K-Fold Cross Validation
- **Goal:** Learn K-fold cross-validation using two regression models:
  - Kernel Ridge Regression
  - Regression Decision Trees
- **Steps:**
  1. Write a function to split data into k folds.
  2. Calculate RMSE as the performance metric.
  3. Run cross-validation.
  4. Measure runtime for `k = 2` to `k = 100`.
  5. Reflect and answer discussion questions.
**Dataset:** Diabetes progression dataset from `scikit-learn`
### 4. Handling Imbalanced Data with SMOTE and SVM
- **Goal:** Improve classification of rare diseases in a synthetic dataset.
- **Steps:**
  1. Generate synthetic imbalanced data.
  2. Split into train/test sets.
  3. Train SVM without oversampling.
  4. Apply SMOTE to balance classes.
  5. Retrain SVM on balanced data.
  6. Compare performance with bar plots.
**Metrics:** Confusion matrix, precision, recall, F1 score
### 5. Oversampling and Class Imbalance
- **Goal:** Understand the impact of oversampling on rare class prediction.
- **Steps:**
  1. Train models with random sampling.
  2. Train models with stratified (balanced) sampling.
  3. Compare solutions and reflect in markdown.
**Data Simulation:** `sklearn.make_classification`
## Requirements
- Python 3.x
- scikit-learn
- imbalanced-learn
- pandas
- matplotlib
- seaborn
- numpy
Install all dependencies:
```bash
pip install -r requirements.txt
```
## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/yourrepo.git
   ```
2. Navigate into the directory:
   ```bash
   cd yourrepo
   ```
3. Open the notebooks in Jupyter:
   ```bash
   jupyter notebook
   ```
## References
- scikit-learn documentation: https://scikit-learn.org/
- imbalanced-learn documentation: https://imbalanced-learn.org/
- SMOTE paper: https://doi.org/10.1613/jair.953
## Contributing
Contributions, issues, and pull requests are welcome!  
Feel free to submit improvements, bug fixes, or additional modules.
## License
This project is licensed under the MIT License.\

Copyright (c) 2025 Mark Petalcorin

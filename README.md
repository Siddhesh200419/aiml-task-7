# Task 7: Support Vector Machines (SVM) - AI & ML Internship

## 📌 Objective
To use SVM for binary classification using linear and non-linear (RBF) kernels and evaluate its performance.

## 🧰 Tools Used
- Python
- Scikit-learn
- NumPy
- Matplotlib

## 📊 Dataset
- Breast Cancer Dataset from `sklearn.datasets`

## 🔍 Steps Performed
1. Loaded and normalized the dataset.
2. Trained SVM with:
   - Linear Kernel
   - RBF Kernel
3. Evaluated using accuracy and confusion matrix.
4. Tuned hyperparameters using GridSearchCV.
5. Visualized decision boundaries using PCA-reduced 2D data.

## 📈 Results
- Linear SVM Accuracy: ~97%
- RBF SVM Accuracy: ~98%
- Best parameters via GridSearch: `{'C': 1, 'gamma': 'scale', 'kernel': 'rbf'}`



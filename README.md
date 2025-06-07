# Task 7: Support Vector Machines (SVM)

This task demonstrates how to use Support Vector Machines for classification using the Breast Cancer Dataset.

## 🔧 Tools Used
- Python
- scikit-learn
- NumPy
- Matplotlib
- Seaborn

## 📁 Dataset
- [Breast Cancer Dataset (sklearn)](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)

## 🧠 Approach
1. Loaded and standardized the Breast Cancer dataset.
2. Applied PCA to reduce dimensionality for visualization.
3. Trained and evaluated SVM classifiers with:
   - Linear Kernel
   - RBF Kernel
   - RBF Kernel with GridSearchCV tuning (for `C` and `gamma`)
4. Visualized decision boundaries using 2D PCA projections.
5. Reported accuracy and selected best model.

## 📊 Results
- **Linear SVM Accuracy:** ~99.12%
- **RBF SVM Accuracy:** ~96.49%
- **Best RBF (GridSearchCV) Accuracy:** ~97.37%
- **Best Parameters:** C = 10, gamma = 0.01

---

✅ **Task Completed Successfully**

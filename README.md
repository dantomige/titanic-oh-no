# Titanic Survival Prediction 🚢

Some practice working with datasets, levereging KNN and PCA, and implementing supervised learning algorithms.

## 📊 Model Performance

Our benchmarks show that **XGBoost** currently leads in accuracy, while **PCA** helps linear models like Logistic Regression find a cleaner mathematical solution by reducing feature noise.

| Model | Dataset | Accuracy |
| :--- | :--- | :--- |
| **XGBoost** | Original | **82.12%** |
| **Logistic Regression** | PCA-transformed | **81.01%** |
| **Random Forest** | Original/PCA | **80.45%** |
| **Logistic Regression** | Original | **80.45%** |
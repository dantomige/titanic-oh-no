# Titanic Survival Prediction 🚢

Some practice working with datasets, levereging KNN and PCA, and implementing supervised learning algorithms.

## 📊 Model Performance

Our benchmarks show that **XGBoost** currently leads in accuracy, while **PCA** helps linear models like Logistic Regression find a cleaner mathematical solution by reducing feature noise.

| Model | Dataset | Accuracy |
| :--- | :--- | :--- |
| **RandomForest** | Original | **84.92%** |
| **XGBoost** | Original | **82.12%** |
| **RandomForest** | PCA-transformed | **81.56%** |
| **Logistic Regression** | PCA-transformed | **81.01%** |
| **Logistic Regression** | Original | **80.45%** |
| **XGBoost** | PCA-transformed | **79.89%** |